
# PowerBI e DAX *Cheat sheet*
<p> Nesta pasta vou inserir meus estudos sobre PowerBI e DAX. O ponto de partida será utilizando um banco de dados que se chama Adventure Works que estão disponiveis
	no site da Microsoft. <a href="https://www.microsoft.com/en-us/download/details.aspx?id=49502">Link</a></p>

# Mapa mental de estudos

<p align="center">
  <img src="https://raw.githubusercontent.com/vitorfraga/Learn2/master/Power%20BI%20e%20DAX/imagens/mapa_mental_power_bi.PNG"/>
</p>




# Modelagem de dados

Modelagem de dados é um **conjunto de tabelas** conectadas por **relações entre colunas**, que tem o objetivo de responder a questões de negócio.

# DAX 

É a linguagem do Power Pivot e Power BI  e uma peça fundamental de um modelo de dados.

 - Permite cálculos extremamente avançados e complexos em poucas linhas de código
 - Simples, porém não é trivial
 - Relativamente fácil de aprender, porém dificil de "masterizar."
 - Conceito de contexto de avaliação.

DAX (DATA ANALYSIS EXPRESSIONS) : Coleção de funções. operadores e constantes que podem ser usados em uma fórmula ou expressão, para cálcular e retornar um ou mais valores.

# Coluna calculada x Medida
| Coluna calculada | Medida |
|--|--|
|Contexto de linha  | Contexto de filtro |
|Valor calculado para cada linha da tabela  | Calculada somente para células que são usadas na tabela dinâmica ou gráfico dinâmico |
|Utilizado quando se deseja expor os valores em um eixo do gráfico.  | Mais eficientes computacionalmente |
|Consomem memória e são recalculadas a cada atualização | Utiliza sempre que tivermos valores para expor em um gráfico |

# Principais funções DAX
| Nome| O que faz?  Exemplo em
|--|--|--|--|
|Filter()| Filtra uma tabela com condições inseridas, é mais performático que usar o IF() em iterações como SUMX |Adventure Works: Aba "Filter e IF"
|IF()| Realiza teste lógico através de condições, em iterações como SUMX, é melhor utilizar o Filter | Adventure Works: Aba "Filter e IF"
|CALCULATE()| o que deve fazer | Adventure Works: Aba "xxx"
|ALL()| o que deve fazer | Adventure Works: Aba "xxx"
|ALLSELECTED()| o que deve fazer | Adventure Works: Aba "xxx"
|VALUES()| o que deve fazer | |Adventure Works: Aba "xxx"
|HASONEVALUE()| o que deve fazer | Adventure Works: Aba "xxx"
|SELECTEDVALUE()| o que deve fazer | Adventure Works: Aba "xxx"
|SUMX()| o que deve fazer | Adventure Works: Aba "xxx"
|AVERAGEX()| o que deve fazer | Adventure Works: Aba "xxx"
|MAXX()| o que deve fazer | Adventure Works: Aba "xxx"
|TOTALYTD()| o que deve fazer | Adventure Works: Aba "xxx"
|DATEADD()| o que deve fazer | Adventure Works: Aba "xxx"
|SAMEPERIODLASTYEAR()| o que deve fazer | Adventure Works: Aba "xxx"
|DATESBETWEEN()| o que deve fazer | Adventure Works: Aba "xxx"
|DATAESINPERIOD()| o que deve fazer | Adventure Works: Aba "xxx"
|LASTDATE()| o que deve fazer | Adventure Works: Aba "xxx"
|LASTNOBLANK()| o que deve fazer | Adventure Works: Aba "xxx"
|RANKX()| o que deve fazer | Adventure Works: Aba "xxx"
|TOPN()| o que deve fazer | Adventure Works: Aba "xxx"
|ADDCOLUMNS()| o que deve fazer | Adventure Works: Aba "xxx"
|SUMMARIZECOLUMNS()| o que deve fazer | Adventure Works: Aba "xxx"
|USERRELATIONSHIP()| o que deve fazer | Adventure Works: Aba "xxx"
