Autores
Este projeto foi desenvolvido por:

Felipe Otávio Garcia Madeira RM: 563521
Murilo Macedo Pina RM: 563397
Diego Bondezan Yonamine RM: 562013
Alexandre Martins Lucas RM: 561732
Vitor Carvalho Alexandre RM: 562298

CP1 EDGE COMPUTING AND COMPUTER SYSTEMS
Descrição do projeto
Desenvolvemos um sistema prático de monitoramento ambiental com Arduino para ser utilizado na Vinheria Agnello. O sistema possui como objetivo garantir que as condições de luminosidade estejam adequadas para preservar a qualidade do vinho. Para isso, utilizamos um sensor LDR (Light Dependent Resistor), que é um componente eletrônico que varia sua resistência de acordo com a intensidade da luz: quanto mais claro o ambiente, menor a resistência; quanto mais escuro, maior a resistência. Isso permite ao Arduino "medir" o nível de luminosidade.
    Com base nisso, implementamos em nosso sistema de alarme visual e sonoro. Um LED verde acende quando os níveis de luz estão adequados ao Arduino, o LED amarelo indica um nível de alerta e o LED vermelho aponta uma condição crítica. O LED fica vermelho quando o nível de alerta é atingido, com isso o sistema aciona um buzzer por 3 segundos para sinalizar o problema.

Dependências do projeto
Componentes de Hardware
-- Placa Arduino.
-- Resistores (Para formar divisor de tensão com o LDR).
-- Buzzer.
-- LEDs (1 vermelho, 1 amarelo, 1 verde).
-- Fios e protoboard.
-- Sensor LDR.

Software:
--Tinkercad.

Reprodução do projeto
Passo a Passo
1- Montamos o circuito conforme foi pedido no CP.
2- Fizemos o código dentro do Tinkercad.
3- Simulamos o código diversas vezes.
4- Testamos a variação de luz no sensor e observamos a reação dos LEDs e do buzzer.
5- Corrigimos os erros do código para que o sistema funcione perfeitamente.

![Circuito Arduino](circuitoArduinoCP1EdgeComputing)