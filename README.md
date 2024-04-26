# Leitor de Carteira de Investimentos em Excel

Bem-vindo ao meu primeiro projeto aqui no GitHub!

## Origem do Projeto

Ao me inscrever para uma vaga de estágio em Dados em uma empresa de investimentos, me deparei com um teste desafiador. O desafio consistia em criar uma base de dados a partir de uma carteira de investimentos, chamada "carteira_explodida", para ser analisada no Power BI.

## Desafio e Solução

O teste demandava uma compreensão detalhada das informações contidas na carteira de investimentos. A primeira aba do Excel continha a "carteira base", que incluía informações sobre cada gestor, o valor total da carteira e a porcentagem de participação em cada gestor. As outras abas continham ações específicas de cada gestor, com o valor total da ação e a porcentagem de participação.

Para criar a base de dados necessária, precisei calcular o valor real de cada ação e sua porcentagem de participação. Por exemplo, se a carteira base "Cotas de INVESTMENTO ALPHA FI AÇÕES" valia R$589320,75 e eu possuía 45% dela, e na ação "VORTEX TECH ON NM - VRTX3" possuía 42%, o cálculo seria: R$589320,75 * 45% * 42% = R$111381,62175.

Fazer esses cálculos manualmente para uma carteira com várias linhas seria ineficiente, então criei um programa em Python para automatizar o processo. O código está comentado para facilitar o entendimento do raciocínio por trás dos cálculos.

![](https://img.hotimg.com/Captura-de-tela-2024-04-26-114710.png#vitrinedev)

## Funcionalidades do Projeto

- **Automatização dos Cálculos**: O programa em Python calcula o valor real de cada ação e sua porcentagem de participação, gerando a carteira_explodida automaticamente.

## Exemplos de Uso

Para usar o programa:

1. Clone o repositório.
2. Execute o programa em Python.
3. Verifique a carteira_explodida gerada pelo programa.

