# Análise estatística de base de dados de diabetes

O diabetes é uma doença crônica grave na qual os indivíduos perdem a capacidade de regular efetivamente os níveis de glicose no sangue e pode levar a uma redução na qualidade de vida e na expectativa de vida.

O Sistema de Vigilância de Fatores de Risco Comportamentais (BRFSS) é uma pesquisa telefônica relacionada à saúde que é coletada anualmente pelo CDC (Centro de Controle e Prevenção de Doenças dos Estados Unidos). A cada ano, a pesquisa coleta respostas de milhares de americanos sobre comportamentos de risco relacionados à saúde, condições crônicas de saúde e o uso de serviços preventivos. Para este projeto, foi utilizado conjunto de dados disponível no Kaggle para o ano de 2015.

![imagem](imagens/diabetes.jpg)

## Organização do projeto

```
├── .gitignore         <- Arquivos e diretórios a serem ignorados pelo Git
├── ambiente.yml       <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE            <- Licença de código aberto (MIT)
├── README.md          <- README principal para desenvolvedores que usam este projeto.
|
├── dados              <- Arquivos de dados para o projeto.
|
|
├── notebooks          <- Jupyter Notebooks.
│                         
│
|   └──src             <- Código-fonte para uso neste projeto.
|      │
|      ├── __init__.py  <- Torna um módulo Python
|      ├── config.py    <- Configurações básicas do projeto
|      └── estatistica.py  <- Funções criadas especificamente para este projecto.
|
├── referencias        <- Dicionários de dados.
|
├── imagens         <- Imagens utilizadas no projeto.
│       
```

## Configuração do ambiente


1. Faça o clone do repositório.

    ```bash
    git clone git@github.com:marcelochioca12/Projeto_modelo.git
    ```

2. Crie um ambiente virtual para o seu projeto utilizando o conda de ambientes de sua preferência.


      ```bash
      conda env create -f ambiente.yml --name estatistica
      ```

## Um pouco mais sobre a base

[Clique aqui](referencias/01_dicionario_de_dados.md) para ver o dicionário de dados da base utilizada.

## Resumo dos principais resultados

A FAZER
