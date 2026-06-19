# Acidentes de trânsito por ocorrência

Esse projeto se trata de um estudo de análise de dados sobre os dados que a Polícia Federal Rodoviária disponibilizou sobre os acidentes ao longo de 2007-2016. Acredito que há pontos de melhoria, que vou implementar na segunda parte dos dados 2016-202x, técnicas a serem testadas e entender mais de perto, além de expandir para um projeto de ciência, aplicando alguma ténica de ML.

Voltando sobre o projeto, se concentram nos dois primeiros arquivos:

- treatment-for-before-2016
- analysis.ipynb
- requirements.txt
- README.md

Falando em ordem de citação:
- Como se trata de dados que não foram tratados, peguei para realizar o tratamento de dados faltantes, limpeza, aplicações de ténicas e por fim criação de colunas que facilitem na análise futuramente;
- Se trata de um notebook onde faço a análise dos dados efetivamente limpos. Tento trazer algumas perguntas e as respostas através dos dados que são disponibilizados logo abaixo da própria explicação, quando não há um gráfico que se explique por si só;
- Se trata das versões a serem instaladas para rodar localmente na máquina de outra pessoa;
- Documentação do projeto. 

## Instalação

Use o gerenciador de projeto [pip](https://pip.pypa.io/en/stable/) para baixar os pacotes.

```bash
pip install -r requirements.txt
```

## Uso

Basta preparar seu local para o processamento. Caso já tenha instalado algum outro pacote, basta criar um kernel novo/temporário com:

```bash
python -m venv venv
```

Isso vai criar um ambiente virtual, isto é, separado da sua máquina, e então você pode instalar as depedências sem se preocupar com um conflito com os seus de outros projetos.

Os dados foram coletados do seguinte link: [dados](https://dados.gov.br/dados/conjuntos-dados/sinistros-de-transito-agrupados-por-ocorrencia). Como dito anteriormente, consiste nos dados de 2007-2016.

Após baixar, recomendo por no caminho: ```data/after-2016/```. Com isso você não precisará inserir nenhuma modificação no código como todo.

Após isso, você precisa realizar o processamento do tratamento e por fim, o da análise.

## Próximos passos

Apesar de ser um notebook de estudo, tentei deixar o mais completo possível, mas acredito que ainda há muitas melhoras, e seguindo do princípio que caso eu quisesse "concluir" isso só deixando o projeto perfeito eu nunca o concluiria. Tirando isso, acredito que vou realizar outros estudos futuramente, inclusive com a base de dados dos próximos anos da PRF e talvez eu volte para realizar algumas modificações com a experiência que eu for pegando.

