# Desafio Cartas Super Trunfo - Batalha Naval com Habilidades Especiais

Este projeto foi desenvolvido como parte do desafio final da disciplina **Introdução à Programação de Computadores** da Estácio. O objetivo é aplicar conceitos de vetores e matrizes para simular habilidades especiais em um jogo de Batalha Naval.

## 🎯 Objetivo

Implementar habilidades com áreas de efeito distintas sobre um tabuleiro 10x10, utilizando estruturas de repetição e condicionais para construir e aplicar as matrizes de forma dinâmica.

## 🧠 Habilidades Implementadas

O programa define três tipos de habilidades especiais, cada uma com uma matriz de área de efeito:

- **Cone**: Área em forma de triângulo invertido, com origem no topo.
- **Cruz**: Área em forma de cruz, com origem no centro.
- **Octaedro**: Área em forma de losango, simulando a vista frontal de um octaedro.

Cada matriz utiliza `1` para indicar posições afetadas e `0` para posições não afetadas.

## 🛠️ Como Executar

### Requisitos

- Compilador C (ex: GCC)

### Compilação

```bash
gcc main.c -o batalha
./batalha
