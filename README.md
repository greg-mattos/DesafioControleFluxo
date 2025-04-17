# Desafio Controle de Fluxo

Este projeto é destinado a demonstrar os conceitos de controle de fluxo em programação. O objetivo é criar um programa simples que exerça o uso de sentenças `if-else` e loops.

## Visão Geral do Projeto

O projeto consiste em uma classe Java única, `Contador.java`, que solicita ao usuário dois inteiros como entrada. O programa então utiliza essas entradas para contar a partir do primeiro número até (mas não incluindo) o segundo número.

## Como Funciona

O programa usa um bloco `try-catch` para verificar se o segundo parâmetro é maior ou igual ao primeiro. Se essa condição for satisfeita, uma exceção é lançada e o programa imprime uma mensagem de erro. Caso contrário, o programa entra em um loop `for` que imprime cada número do primeiro ao segundo.

## Características

- **Sentenças Condicionais:** Demonstra sentenças `if-else` usando blocos `try-catch`.
- **Loops:** Exerce o uso de loops `for` para repetir ações específicas.

## Para Executar o Programa

1. Compile a classe `Contador.java` utilizando um compilador Java (por exemplo, `javac Contador.java`)
2. Execute o programa usando a runtime Java (por exemplo, `java Contador`)

## Exemplo de Entrada/Saída

**Entrada:** `3, 6`
**Saída:**
Imprimindo o número 4
Imprimindo o número 5
Imprimindo o número 6