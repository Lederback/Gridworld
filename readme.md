# Gridworld
Este repositório contém um código Python que implementa um algoritmo para encontrar o melhor caminho em uma grade de 8x8, usando iteração de valor para determinar os valores de cada célula da grade e uma busca gulosa para encontrar o melhor caminho de entrada para saída.

## Descrição
O código consiste em várias funções:

gridCreation(): Gera uma grade aleatória de 8x8 com obstáculos e posições de entrada e saída.

valuesGridCreation(): Inicializa uma grade de valores com zeros.

getGridPlot(grid): Plota a grade.

getReward(grid, i, j): Retorna a recompensa de uma célula da grade.

getActionsValues(valuesGrid, grid, i, j, gamma): Calcula os valores das ações possíveis para uma célula da grade.

getStateRewards(theta, policy, gamma, delta, grid, valuesGrid): Iteração de valor para calcular os valores das células da grade.

greedySearch(grid, valuesGrid): Busca gulosa para encontrar o melhor caminho.
createPathingGrid(grid, bestPath): Marca o caminho encontrado na grade.