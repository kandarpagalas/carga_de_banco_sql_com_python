# Projeto prático da disciplina de Linguagens de Programação para o MBA em Engenharia de dados

## Objetivos
- Coletar as fontes de dados que totalizam mais de 100milhões de linhas e conseguir ler os arquivos
- Construir uma lógica em python, sem o uso de pandas ou spark, para juntar esses dados
- Persistir os dados em uma base de dados como postgresql, mysql etc.
- Escrever quais pontos de dificuldade e quais os pontos a favor da
técnica usada. Indique soluções de mercado através de uma pesquisa,
quais ferramentas facilitariam essa jornada?

## Pontos de dificuldade e quais os pontos a favor da técnica usada.
### Vantagens
- A utilização apenas de pacotes nativos do python para manipulação de arquivos reduz a dependência de pacotes de terceiros resultando em maior conpatibilidade, principalmente em ambientes com bastante restrição de recursos
- Tem-se maior controle sobre as etapas que são executadas

### Dificuldades
- É necessário conhecimento em um número maior de recursos do python.
- Não temos as abstrações implementadas por pacotes especializados, nem suas otimizações
- Passamos a ser responsáveis por todo o processo, de forma mais detalhada

## Soluções de mercado que facilitariam essa jornada?
- Airbyte
- Pacote Pandas
- Pyspark

## Logs
<img src="./img/tempo_de_carga.png" alt="drawing" width="600"/>
