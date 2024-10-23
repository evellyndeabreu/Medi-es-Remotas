# Medi-es-Remotas
Este projeto tem como objetivo desenvolver um sistema de medição de temperatura utilizando o sensor DS18B20 para obter leituras precisas e o módulo Bluetooth HC-05 para transmitir os dados para um smartphone. A interface permite visualizar as leituras de temperatura em tempo real por meio de uma aplicação serial no celular.

Este projeto tem como objetivo desenvolver um sistema de medição de temperatura utilizando o sensor DS18B20 para obter leituras precisas e o módulo Bluetooth HC-05 para transmitir os dados para um smartphone. A interface permite visualizar as leituras de temperatura em tempo real por meio de uma aplicação serial no celular.

Funcionalidades:
Leitura de temperatura: Utiliza o sensor DS18B20 para medições precisas.
Transmissão via Bluetooth: Os dados são transmitidos sem fio usando o módulo HC-05.
Monitoramento em tempo real: Visualização das leituras de temperatura através de um aplicativo no celular.
Componentes:
Arduino Uno R3
Sensor de Temperatura DS18B20
Módulo Bluetooth HC-05
Protoboard, Jumpers, Resistores
Software:
O código foi desenvolvido em C++ utilizando as bibliotecas:

OneWire.h e DallasTemperature.h para comunicação com o sensor DS18B20.
SoftwareSerial.h para a comunicação com o módulo Bluetooth HC-05.
Como funciona:
O sensor DS18B20 coleta a temperatura ambiente e envia os dados para o Arduino.
O Arduino Uno processa as informações e as transmite via Bluetooth para um smartphone, onde as temperaturas podem ser monitoradas em tempo real por meio de uma interface serial simples.
Desafios e Aprendizados:
Integração do sensor DS18B20 e configuração do protocolo 1-Wire.
Estabilização da comunicação Bluetooth.
Criação de uma interface intuitiva para visualização dos dados.
Como usar:
Monte o circuito conforme o diagrama.
Carregue o código no Arduino.
Conecte o módulo Bluetooth ao seu smartphone e abra um aplicativo serial para monitorar a temperatura em tempo real.
