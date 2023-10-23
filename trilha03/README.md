# Trilha 03 - Template de Projeto

Para esta trilha, use a seguinte estrutura para criação do projeto da **Trilha 03** (exclusivamente para a trilha 3!). 

- **README.md**: o arquivo com as instruções do seu projeto.
- Pasta `data/`: colocar aqui arquivos .CSV ou .xlsx que foram utilizados neste projeto.
    - `raw/`: arquivo bruto, sem nenhum processamento.
    - `processed`: arquivos limpos ou processados, após o processo de carregar.
- Pasta `src/`:
    - `extract/`: caso seu proejto envolva um processo de coletar dados da internet, o arquivo `extract_data.py` deve conter um código Python que realize este processo de coletar os dados (vide aula de API). 
    - `transform/`: caso seu proejto envolva um processo de transformar dados, coloque o código Python em `transform_data.py`.
    - `load/`: para carregar dados de um arquivo .CSV ou banco de dados.
- Pasta `docs/`: caso seu projeto tenha documentos sobre o processo, coloque aqui algum arquivo markdown ou .PDF.

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
├── docs/
│   ├── ETL-Process-Documentation.md
│   ├── Data-Dictionary.md
│   └── ...
│
├── requirements.txt
└── LICENSE
```
