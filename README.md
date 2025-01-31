# Desafio Lighthouse - Indicium

Este repositório refere-se ao **Desafio Lighthouse da Indicium** sobre **Ciência de Dados**, com o objetivo de realizar uma **Análise Exploratória de Dados (EDA)** do banco de dados fornecido e desenvolver um **modelo de machine learning** para previsão de preços de apartamentos.

## Estrutura do Projeto

O repositório está organizado da seguinte forma:

```
|— Arquivo_PKL/
|   |— link do arquivo PKL.txt  # Melhor modelo salvo para previsão, esse arquivo contém um link do google drive onde contém o arquivo, deve ser feito o download e colocado na pasta.
|   |— exemplo_predicao.ipynb  # Script demonstrando como rodar o modelo
|— Scripts/
|   |— EDA e script do projeto.ipynb  # Notebook contendo a análise exploratória dos dados e 
|   |— dados.csv  # Arquivo de dados utilizado no projeto
|— requisitos.txt  # Lista de dependências para execução do projeto
|— README.md  # Documentação do projeto
```

## Instalação

Para executar este projeto, siga os passos abaixo:

### 1. Clonar o repositório
```sh
git clone https://github.com/Filipeafq/indicium-projeto.git
cd desafio-lighthouse
```

### 2. Criar um ambiente virtual (recomendado)
```sh
python -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate
```

### 3. Instalar dependências
```sh
pip install -r requisitos.txt
```

## Execução

### 1. Análise Exploratória de Dados (EDA) e treinamento do modelo 
Abra o **EDA e script do projeto.ipynb** para visualizar a exploração dos dados e treinar o modelo:
```sh
jupyter notebook Scripts/EDA e script do projeto.ipynb
```


### 2. Teste do Modelo Treinado
Para testar o modelo salvo, abra o **Rodar arquivo Pickle.ipynb**:
```sh
jupyter notebook Arquivo_PKL/Rodar arquivo Pickle.ipynb
```

**Nota:** O arquivo **dados.csv** está disponível na pasta **Scripts/**. Como o processo de treinamento pode ser computacionalmente custoso, recomenda-se apenas testar o modelo já salvo.

## Dependências

As dependências do projeto estão listadas no arquivo **requisitos.txt**. Caso precise instalar manualmente, seguem as principais bibliotecas utilizadas:

```
pandas==1.5.3
numpy==1.23.5
seaborn==0.12.2
matplotlib==3.6.3
scikit-learn==1.2.2
xgboost==1.7.3
```


