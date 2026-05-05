# Sistema de Autenticação Otimizado para Eletropostos

Gustavo Bitencourt-RM:568885
Daniel Vieira-RM: 573326
Leonardo Takachi-RM: 569066
Giovane Salazar-RM: 570396

## Problema

Os eletropostos utilizam sistemas computacionais baseados em linguagens de alto nível e hardware genérico, o que pode causar consumo desnecessário de energia e baixa eficiência no processamento de tarefas simples, como autenticação de usuários.

## Justificativa

Com o aumento do uso de veículos elétricos, é essencial que os sistemas de carregamento sejam eficientes não apenas no consumo de energia elétrica, mas também no uso de recursos computacionais. Melhorar a eficiência do processamento contribui diretamente para a sustentabilidade.

## Proposta de Solução

A proposta consiste em desenvolver um sistema de autenticação de usuários utilizando linguagem Assembly, permitindo maior controle sobre o hardware e redução do número de instruções executadas. Isso torna o sistema mais rápido e energeticamente eficiente.

## Arquitetura Utilizada

A solução se baseia em uma arquitetura do tipo RISC, que utiliza instruções simples e rápidas. Essa escolha permite maior eficiência energética e melhor desempenho em sistemas embarcados.

## Exemplo de Código em Assembly

LOAD R1, USER_INPUT
COMPARE R1, VALID_USER
JUMP_IF_EQUAL AUTHORIZED
JUMP NOT_AUTHORIZED

## Impactos Esperados

- Redução do consumo de energia computacional
- Processamento mais rápido
- Melhor uso de hardware embarcado
- Maior eficiência nos eletropostos

## Sustentabilidade

A otimização do código reduz o uso da CPU, diminuindo o consumo de energia. Isso contribui para sistemas mais sustentáveis e melhor aproveitamento de energias renováveis.

