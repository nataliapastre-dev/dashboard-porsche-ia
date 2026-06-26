# 🚗 Dashboard Porsche IA

Análise e tratamento de dados utilizando Python, focado na construção de um pipeline de ETL (*Extraction, Transformation, and Load*) automatizado para organização, limpeza e padronização de dados automotivos.

---

## 📊 Objetivo do Projeto

O principal objetivo deste projeto é estruturar um fluxo de dados robusto e eficiente que elimine processos manuais de manipulação de planilhas. O pipeline foi desenhado para:
* **Extração:** Carregamento automatizado de planilhas Excel complexas (`.xlsx`).
* **Transformação:** Limpeza profunda, eliminação de redundâncias e padronização de tipos de dados via módulos dedicados.
* **Carga:** Geração e exportação de uma base de dados 100% processada, confiável e pronta para alimentação de dashboards ou ferramentas de Analytics (Power BI, Tableau, etc.).

---

## ⚙️ Tecnologias e Ferramentas

* **Python:** Linguagem base para a construção do pipeline e lógica dos agentes.
* **Pandas:** Manipulação, limpeza e análise estruturada de dados de alta performance.
* **OpenPyXL:** Engine integrada para leitura e escrita otimizada de arquivos Excel.
* **Git & GitHub:** Controle de versão e documentação das boas práticas de desenvolvimento.

---

## 🧠 Estrutura do Repositório

O projeto foi modularizado seguindo boas práticas de arquitetura de software para garantir escalabilidade e fácil manutenção:

```text
dashboard-porsche-ia/
│
├── data/
│   ├── raw/              # Planilhas originais (dados brutos e não tratados)
│   └── processed/        # Arquivos finais gerados após a execução do pipeline
│
├── agents/               # Módulos com regras de negócio e tratamento de dados
├── utils/                # Funções utilitárias e auxiliares reutilizáveis
│
├── main.py               # Arquivo principal que orquestra a execução do pipeline (ETL)
└── README.md             # Documentação oficial do projeto
