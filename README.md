# Coleta dos dados de Declarações de Imposto de Renda

## Objetivo

O objetivo é coletar todos os dados presentes no site: https://servicos.receita.fazenda.gov.br/publico/EstatisticaIRPF/totaisDIRPF_UF.HTML no qual podem ser utilizados para diversas análises, tais como quantidade de declarações por ano, UF, Cidade, meio de declaração, tipo de tributação, resultados e restituições. 

Com essas informações consolidadas em apenas um único local, todo o processo de análise torna-se mais rápido e menos burocrático. 

## Estrutura do repositório

O repositório segue estruturado conforme abaixo

.<br>
├── data<br>
│   ├── dados_consolidados<br>
│   │   └── dados_imposto_de_renda.xlsx<br>
│   └── dados_historicos<br>
│       └── UF_ANO.txt<br>
├── imgs<br>
├── report<br>
├── requirements<br>
├── coleta_imposto_de_renda.ipynb<br>
└── README.MD<br>

## Sobre o site

O site divulga as informações em telas separadas, no qual podem ser utilizadas lógicas de programação bem como a investigação do comportamento dessas telas para então realizar a consolidação de todos os dados. 

![Alt text](imgs/Screenshot_1.png?raw=true "Exemplo de tela")


Para isso, foram capturadas e utilizadas as variáveis de controle Ano e UF. 

Todos os detalhes podem ser visto no código: https://github.com/AfonsoFeliciano/Python-Web-Scrapping-Declaracoes-Imposto-de-Renda/blob/main/coleta_imposto_de_renda.ipynb

## Melhorias

Após realizar todas as coletas, realizou-se a criação de um Dashboard utilizando conceitos de modelagem dimensional no software Power BI. 

Com esse Dashboard, torna-se possível aumentar o nível de detalhamento e riqueza nas análises facilitando a tomada de decisão. 

### Tela Geral

![Alt text](imgs/Screenshot_2.png?raw=true "Tela Geral")



### Tela de Detalhamento

![Alt text](imgs/Screenshot_3.png?raw=true "Tela de Detalhamento")