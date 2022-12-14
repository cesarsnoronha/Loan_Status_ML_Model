# Nome do PROJETO

Sobre o projeto

- Dados sobre o que escolheram trabalhar?
    Loan Approval Prediction: Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form.
- Onde encontro a base de dados original?
    https://www.kaggle.com/code/ajaymanwani/loan-approval-prediction/notebook

## Integrantes

- Quem são os participantes?
    César Augusto Noronha
## Organização do projeto

- Onde estão as bases de dados?
    datasets/raw/train_u6...
- Tem dados processados? Onde?
    Os dados são processados na criação de cada gráfico, pois alguns dados precisam de formatos diferentes.
- Onde estão os Notebooks com as Análises Exploratórias?
    report.ipynb
- Onde está o Notebook com as comparações entre modelos?
    report.ipynb
## Setup

- Como instalar as bibliotecas?
    Rodar no terminal:
    conda env create environment.yml
    conda activate .grupo-01-venv

    
    Caso aconteça algum erro:
    conda env update environment.yml 

- Como baixar os dados?
    Os dados estão no arquivo Projeto_analise_credito/main/datasets/raw/train_u6lujuX_CVtuZ9i.csv
    e podem ser baixados com a função:
    df = pd.read_csv('../datasets/raw/train_u6lujuX_CVtuZ9i.csv')

- Onde armazenar a base de dados?
    Em uma pasta na área de trabalho

# Loan_Status_ML_Model
