# Sudoku Metaheuristics

Este repositório contém as implementações dos algoritmos meta-heurísticos utilizados no desenvolvimento do Trabalho de Conclusão de Curso (TCC), aplicados à resolução de problemas de Sudoku 9×9.

## Algoritmos

Foram implementados e avaliados três algoritmos:

- IPSO (Integer-valued Particle Swarm Optimization)
- ACO (Ant Colony Optimization)
- GA (Genetic Algorithm)

## Objetivo

O objetivo do projeto é comparar o desempenho dos três algoritmos na resolução de instâncias de Sudoku com diferentes níveis de dificuldade.

A comparação considera critérios como:

- qualidade da solução obtida;
- número de avaliações da função objetivo;
- tempo de execução;
- taxa de sucesso.

## Implementação

Os algoritmos foram implementados em Python e executados utilizando o Google Colab.

Principais bibliotecas utilizadas:

- NumPy
- random
- copy
- time

## Experimentos

Cada algoritmo é executado sob o mesmo orçamento máximo de 400.000 avaliações da função objetivo, permitindo uma comparação mais justa entre os métodos.

Os experimentos são realizados em diferentes instâncias de Sudoku e repetidos utilizando diferentes sementes para os geradores de números aleatórios.

## Estrutura do repositório

- `IPSO_Sudoku.ipynb` — implementação do IPSO
- `ACO_Sudoku.ipynb` — implementação do ACO
- `GA_Sudoku.ipynb` — implementação do GA

## Autor

Gabriel Marques

Trabalho de Conclusão de Curso.
