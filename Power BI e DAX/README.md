# PowerBI e DAX
<p> Nesta pasta vou inserir meus estudos sobre PowerBI e DAX. O ponto de partida será utilizando um banco de dados que se chama Adventure Works que estão disponiveis
	no site da Microsoft. <a href="https://www.microsoft.com/en-us/download/details.aspx?id=49502">Link</a></p>


# Modelagem de dados

Modelagem de dados é um **conjunto de tabelas** conectadas por **relações entre colunas**, que tem o objetivo de responder a questões de negócio.

# DAX 

É a linguagem do Power Pivot e Power BI  e uma peça fundamental de um modelo de dados.

 - Permite cálculos extremamente avançados e complexos em poucas linhas de código
 - Simples, porém não é trivial
 - Relativamente fácil de aprender, porém dificil de "masterizar."
 - Conceito de contexto de avaliação.

DAX (DATA ANALYSIS EXPRESSIONS) : Coleção de funções. operadores e constantes que podem ser usados em uma fórmula ou expressão, para cálcular e retornar um ou mais valores.

# Medida x Coluna calculada
| Medida | Coluna Calculada |
|--|--|
|Contexto de linha  | Contexto de filtro |
|Valor calculado para cada linha da tabela  | Calculada somente para células que são usadas na tabela dinâmica ou gráfico dinâmico |
|Utilizado quando se deseja expor os valores em um eixo do gráfico.  | Mais eficientes computacionalmente |
|Consomem memória e são recalculadas a cada atualização | Utiliza sempre que tivermos valores para expor em um gráfico |