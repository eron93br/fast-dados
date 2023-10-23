# Trilha 03 - Template de Projeto

Para esta trilha, use a seguinte estrutura para criação do projeto da **Trilha 03** (exclusivamente para a trilha 3!). 

```
Projeto-ETL-Template/
│
├── README.md
├── .gitignore
│
├── data/
│   ├── raw/
│   │   ├── source_data_1.csv
│   │   └── ...
│   │
│   ├── processed/
│   │   ├── cleaned_data.csv
│   │   └── transformed_data.csv
│
├── src/
│   ├── extract/
│   │   ├── extract_data.py
│   │   └── ...
│   │
│   ├── transform/
│   │   ├── transform_data.py
│   │   └── ...
│   │
│   ├── load/
│   │   ├── load_data.py
│   │   └── ...
│   │
│   ├── main.py
│   └── ...
│
├── config/
│   ├── config.yml
│   ├── secrets.yml (encrypted or managed securely)
│   └── ...
│
├── docs/
│   ├── ETL-Process-Documentation.md
│   ├── Data-Dictionary.md
│   └── ...
│
├── requirements.txt
└── LICENSE
```
