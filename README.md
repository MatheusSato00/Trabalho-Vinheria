# Monitor de Luminosidade - Vinheria Agnello

Projeto desenvolvido para monitorar a luminosidade em uma adega, evitando a exposição excessiva à luz que pode prejudicar a qualidade dos vinhos.

## Descrição

Utiliza um sensor LDR conectado ao Arduino para medir a luz do ambiente e indicar o nível através de LEDs. Em situações críticas, um buzzer é acionado como alerta.

## Estados do Sistema

* Baixo (Ideal) - LED Verde
* Médio (Alerta) - LED Amarelo
* Alto (Crítico) - LED Vermelho + Buzzer (3s)

## Hardware

* A0 → LDR
* D13 → LED Verde
* D12 → LED Amarelo
* D11 → LED Vermelho
* D04 → Buzzer

## Peças 

1x Arduino Uno
1x Protoboard (breadboard)
1x LDR (sensor de luz)
💡 LEDs
1x LED verde
1x LED amarelo
1x LED vermelho
🔊 Som
1x Buzzer (ativo ou passivo, depende do seu modelo)
⚡ Resistores
3x resistores de 220Ω → usados para cada LED (limita corrente e evita queimar os LEDs)
1x resistor de 10kΩ → usado no LDR (formando o divisor de tensão)
1x resistor de 110Ω → usado no Buzzer 


## Execução

 Você pode testar entrando nesse link: https://www.tinkercad.com/things/cKeSP0uu1Nn-powerful-fyyran/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard%2Fdesigns%2Fcircuits&sharecode=5rmbV0ZV8_zDU5R0Gx0yOygeddJf7-7uQ-Ntq7nl5Js

## Video 
https://youtube.com/shorts/p5R6nx8DuHo?si=J37dNlv_vwY93JVH

## Conclusão

Este projeto demonstra, de forma simples e prática, como a tecnologia pode ser aplicada para resolver problemas reais, como a conservação adequada de vinhos. Utilizando conceitos de Edge Computing, o sistema realiza o monitoramento em tempo real, garantindo respostas rápidas e maior controle sobre o ambiente. Além disso, evidencia o potencial do uso de Arduino em soluções acessíveis e eficientes.

## Integrantes

* Nome: Matheus Mendes Duarte da Silva — RM569559
* Nome: Matheus Sato Oliveira do Prado — RM569392
