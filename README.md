# Estacao-Metereologica-ESP8266

Projeto de uma estação metereologica com ESP8266 enviando dados para a plataforma DOJOT atraves do protocolo MQTT</br>
Projeto academico para a disciplina de IOT na faculade UCL</br>
Aluno:Cleison Mendes Paiva</br>
Curso:Sitemas de Informação</br>

Materiais Utilizads:
1 Placa ESP8266(Com modulo wifi integrado) </br>
1 Sensor de temperatura e umidade DHT11(DHT22 tambem funciona)</br>
1 Sensor de luminosidade BH1750</br>
1 Senso de Chuva(Com modulo) </br>
1 Sensor de Barometrico BME280</br>
2 Protoboard de 830 pontos</br>
Cabos jumpers</br>

Bibliotecas Utilizadas:
<ESP8266WiFi.h> </br>
<PubSubClient.h></br>
<Wire.h></br>
<ErriezBH1750.h> </br>
<Adafruit_Sensor.h></br>
<Adafruit_BME280.h></br>
"DHT.h"</br>

Instalando as bibliotecas e executando o codigo "Principal_v1" podemos obter no serial os valores de medição dos sensores conforme a imagem de exemplo abaixo.

![Screenshot](Dados_simples.png)

Instalando as bibliotecas e executando o codigo "Principal_v2_dojot" podemos obter no serial os valores de medição dos sensores conforme a imagem de exemplo abaixo,esses valores estão sendo enviados para a plataforma DOJOT.

![Screenshot](Dados_Envio_mqtt.png)

Dados sendo apresentados na plataforma DOJOT.

![Screenshot](Dados_dojot.png)


Fontes:
https://techtutorialsx.com/2017/04/09/esp8266-connecting-to-mqtt-broker/</br>
https://dojotdocs.readthedocs.io/pt_BR/latest/

