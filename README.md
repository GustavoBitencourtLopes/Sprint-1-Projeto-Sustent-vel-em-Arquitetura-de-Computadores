# Sistema de Autenticação Otimizado para Eletropostos

Gustavo Bitencourt - RM:568885  
Daniel Vieira - RM:573326  
Leonardo Takachi - RM:569066  
Giovane Salazar - RM:570396  

## Problema

Os eletropostos utilizam sistemas computacionais baseados em linguagens de alto nível e hardware genérico, o que pode causar consumo desnecessário de energia e baixa eficiência no processamento de tarefas simples, como autenticação de usuários.  
Esses sistemas executam um grande número de instruções para operações básicas, aumentando o uso da CPU.  
Como consequência, há desperdício de energia computacional e redução da eficiência geral do sistema.

## Justificativa

Com o aumento do uso de veículos elétricos, é essencial que os sistemas de carregamento sejam eficientes não apenas no consumo de energia elétrica, mas também no uso de recursos computacionais.  
A melhoria na eficiência do processamento reduz o consumo energético dos dispositivos embarcados.  
Isso contribui diretamente para a sustentabilidade e para a escalabilidade de soluções em mobilidade elétrica.

## Proposta de Solução

A proposta consiste em desenvolver um sistema de autenticação de usuários utilizando linguagem Assembly, permitindo maior controle sobre o hardware e redução do número de instruções executadas.  
Ao trabalhar em baixo nível, é possível otimizar operações críticas e eliminar comandos desnecessários.  
Isso torna o sistema mais rápido, eficiente e com menor consumo de energia computacional.

## Arquitetura Utilizada

A solução se baseia em uma arquitetura do tipo RISC, que utiliza instruções simples e rápidas.  
Esse tipo de arquitetura reduz a complexidade das operações e melhora a execução em sistemas embarcados.  
Além disso, o uso de menos ciclos por instrução contribui diretamente para a eficiência energética do sistema.

## Exemplo de Código em Assembly

LOAD R1, USER_INPUT  
COMPARE R1, VALID_USER  
JUMP_IF_EQUAL AUTHORIZED  
JUMP NOT_AUTHORIZED  

Esse exemplo demonstra uma verificação simples de autenticação utilizando poucas instruções.  
A lógica reduz o número de ciclos de processamento, tornando a execução mais rápida e eficiente.  
Com menos operações, há menor consumo de energia por parte do processador.

## Impactos Esperados

- Redução do consumo de energia computacional  
- Processamento mais rápido  
- Melhor uso de hardware embarcado  
- Maior eficiência nos eletropostos  

Com a redução do número de instruções executadas, o sistema se torna mais leve e econômico.  
Isso permite que dispositivos com menor capacidade de hardware sejam utilizados sem perda de desempenho.  

## Sustentabilidade

A otimização do código reduz o uso da CPU, diminuindo o consumo de energia.  
Esse fator é especialmente importante em larga escala, onde múltiplos eletropostos operam simultaneamente.  
Dessa forma, a solução contribui para sistemas mais sustentáveis e melhor aproveitamento de energias renováveis.
