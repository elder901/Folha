# DNA da Folha

Dashboard gerencial para análise da folha de pagamento da rede, com visão por loja, departamento e competência.

## Objetivo

Transformar os dados mensais da folha de pagamento em informações gerenciais para acompanhamento de:

- quadro de funcionários;
- salário-base médio;
- remuneração média;
- total de vencimentos;
- custo econômico de pessoal;
- custo médio por funcionário;
- encargos patronais estimados;
- provisões de férias e 13º salário;
- desempenho por loja;
- desempenho por departamento;
- responsabilização dos líderes;
- variações e anomalias mensais.

## Visões disponíveis

### Visão executiva

Apresenta os principais indicadores consolidados da rede:

- funcionários com movimento;
- salário-base médio;
- vencimentos;
- custo econômico estimado;
- variação em relação ao mês anterior.

### Análise por loja

Permite comparar:

- quantidade de funcionários;
- salário médio;
- vencimentos;
- custo econômico;
- custo por funcionário.

### Análise por departamento

Permite acompanhar os custos e a estrutura dos departamentos, facilitando a gestão e a responsabilização dos respectivos líderes.

### Parametrização

O sistema permite cadastrar os percentuais utilizados no cálculo estimado de:

- INSS patronal;
- RAT;
- FAP;
- terceiros;
- FGTS;
- provisão de férias;
- terço constitucional;
- provisão de 13º salário.

## Metodologia inicial

O custo econômico é estimado pela seguinte composição:

```text
Vencimentos
+ FGTS
+ INSS patronal
+ RAT ajustado pelo FAP
+ terceiros
+ provisão de férias
+ provisão do terço constitucional
+ provisão de 13º salário
+ encargos sobre provisões
= custo econômico estimado

https://elder901.github.io/Folha/
