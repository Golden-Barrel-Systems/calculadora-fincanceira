# Simulador de Maturação de Whisky

## Descrição
Esse simulador consiste em calcular a perda de volume na maturação do whisky ao longo do tempo devido à evaporação (conhecida como *angel’s share*), além de estimar o valor final do barril.

O simulador também demonstra o impacto de uma solução tecnológica capaz de reduzir essas perdas, permitindo visualizar o ganho financeiro ao longo dos anos.

## Objetivo
O objetivo do simluador é mostrar, de forma prática e visual, como o controle de variáveis ambientais pode reduzir perdas na maturação do whisky e gerar economia.

## Funcionamento

O usuário informa:

- Tempo de maturação (anos)
- Volume inicial (litros)
- Taxa de evaporação (% ao ano)
- Valor por litro (R$)

Com base nesses dados, o simluador calcula:

### Cenário sem sistema
- Volume final após evaporação
- Valor final do barril

### Cenário com sistema
- Redução da taxa de evaporação em **15%**
- Novo volume final
- Novo valor estimado

### Economia
- Diferença entre o valor final com e sem o sistema

##  Lógica utilizada

A perda de volume é calculada com base na taxa de evaporação anual:

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript

## Conclusão

O simulador evidencia que pequenas melhorias no controle do ambiente podem gerar ganhos financeiros significativos ao longo do tempo, tornando o processo de maturação mais eficiente.
