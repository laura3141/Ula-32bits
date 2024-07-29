# ULA 32 Bits em VHDL 

## Descrição
Este projeto implementa uma Unidade Lógica Aritmética (ULA) de 32 bits utilizando VHDL. A ULA é responsável por executar operações aritméticas e lógicas básicas em dois operandos de 32 bits e produzir um resultado de 32 bits. As operações suportadas incluem adição, subtração, AND, OR e NOT.

## Funcionalidades

### Operações Aritméticas
-Adição
-Subtração

### Operações Lógicas
- AND
- OR
- NOT

## Arquitetura

A ULA é composta pelos seguintes componentes principais:

### Entradas:

- A, B: Operandos de 32 bits
- Sel: Sinal de controle para selecionar a operação desejada
- SelB: Sinal de controle para inverter um dos operandos
- Cin: Bit de entrada para operações de adição/subtração

### Saídas:

- Cout: Bit de saida para operações de adição/subtração
- Result: Resultado da operação de 32 bits
- Overflow: Indicador de estouro para operações aritméticas

Componentes Internos:

- Multiplexadores para seleção da operação
- Blocos de lógica para operações aritméticas e lógicas

## Implementações futuras
- Operações de comparação
- Operações de shift
