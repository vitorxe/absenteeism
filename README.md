# Absenteeism

Análise exploratória de dados (EDA) e ETL sobre uma base de absenteísmo no trabalho, com relatórios e notebooks de apoio.

## Estrutura do projeto

```
.
├── data/
│   ├── raw/            # dados originais (csv, sas7bdat)
│   └── processed/      # dados tratados, prontos para análise
├── notebooks/          # ETL e notebooks de EDA
├── reports/            # relatórios finais (docx, pdf)
├── images/             # gráficos e imagens usados neste README
├── requirements.txt
└── README.md
```

## Como rodar

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

Notebooks principais em `notebooks/`:

- `etl.ipynb` — extração e tratamento dos dados brutos
- `eda_1.ipynb`, `eda_2.ipynb` — análise exploratória
- `parte_2.ipynb` — continuação da análise

## Gráficos

Coloque os `.png` gerados pelas análises em `images/` e referencie-os aqui com um link relativo — o GitHub renderiza a imagem automaticamente na página do repositório:

```markdown
![Descrição do gráfico](images/nome-do-grafico.png)
```

Exemplo:

![Distribuição de horas de ausência](images/distribuicao_horas_ausencia.png)

Se preferir um link absoluto (por exemplo, para usar fora do GitHub), use o formato `raw.githubusercontent.com`:

```
https://raw.githubusercontent.com/vitorxe/absenteeism/main/images/nome-do-grafico.png
```
