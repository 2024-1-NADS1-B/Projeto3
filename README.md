# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# Medbox

## Grupo 3

## Integrantes:Adriano Xu ,Bruna Farias , Déborah Pavanelli

## Professores Orientadores: Rodnil da Silva

## Descrição:
![Medbox (1)](https://github.com/2024-1-NADS1-B/Projeto3/assets/171097024/81a85ccd-cec5-4137-ae52-c1edec48056a)

O Medbox é uma caixa inteligente composta por seções de gavetas, cada uma equipada com um LED, um módulo sensor magnético e um display de relógio, todos conectados ao Arduino Uno. Um módulo RTC é utilizado para atualizar o horário do display e programar os horários de abertura de cada gaveta. Quando chega o horário programado para cada gaveta, um buzzer emite um som de notificação e o LED da gaveta correspondente acende. Se a gaveta errada for aberta, o som do buzzer aumenta, mas ao abrir a gaveta correta, o LED e o som do buzzer param. Além disso, um ESP32 com sensor de presença dentro da caixa detecta a presença de medicamentos e suas quantidades, conectando-se ao sistema Blynk para monitoramento remoto.


## 🛠 Estrutura de pastas

-Raiz<br>

|-->documentos<br>
  &emsp;|-->Medbox.pdf
  
|-->imagens<br>
  |-->Medbox (1).jpg
  
|-->src<br>
  &emsp;|-->Frontend<br>
  &emsp;|-->Codigo ESP32-Medbox
  &emsp;|-->Codigo arduino uno-Medbox
  
|readme.md<br>

## 🛠 Instalação

Smartphone

Baixe o aplicativo Blynk. 
Abra o projeto no Blynk e copie o Token de Autenticação. 
Configure os widgets desejados. 
Insira o Token de Autenticação no código do dispositivo.
Carregue o código no dispositivo e inicie o projeto no Blynk.

Computador

Baixe e instale a IDE do Arduino no computador. 
Conecte o Arduino ao computador via USB. 
Escreva o código no IDE do Arduino. 
Configure o horário do display.
Configure o Horário para cada gaveta.
Verifique o código e faça o upload para o Arduino. 
Observe a execução do código no Arduino.
## 💻 Configuração para Desenvolvimento

Para desenvolvimento utilize o Arduino IDE 1.8.0, linguagem C++ e as seguintes bibliotecas:

#include <WiFi.h>
#include <WiFiClient.h>
#include <BlynkSimpleEsp32.h>
#include <Wire.h>
#include <LiquidCrystal_I2C.h>
#include <RTClib.h>
#include <myPushButton.h>

## 🗃 Histórico de lançamentos

A cada atualização os detalhes devem ser lançados aqui.

* 0.0.5- 29/05/2024
    Atualização de docs (código do módulo permanece inalterado)
* 0.0.4 - 25/05/2024
    Apresentalçao do projeto
* 0.0.3 - 22/05/2024
    Montagem do projeto
    Execução de códigos
* 0.0.2 - 25/04/2024
    Apresentação do projeto
* 0.0.1 - 04/04/2024
    Planejamento do projeto
    Compra de materiais
    Criação de códigos


## 📋 Licença/License

Medbox by FECAP, Adriano XU, Bruna Farias , Deborah Pavanelli is licensed under Creative Commons Attribution 4.0 International


## 🎓 Referências

https://www.youtube.com/watch?v=wljjjGLW29A

https://examples.blynk.cc/?board=ESP32&shield=ESP32%20WiFi&example=GettingStarted%2FBlynkBlink

https://www.youtube.com/watch?v=DZoFp4sguh8


