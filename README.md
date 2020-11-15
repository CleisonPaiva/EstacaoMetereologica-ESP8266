# Estacao-Metereologica-ESP8266

Projeto de uma estação metereologica com ESP8266 enviando dados para a plataforma DOJOT atraves do protocolo MQTT</br>
Projeto academico para a disciplina de IOT na faculade UCL</br>
Aluno:Cleison Mendes Paiva</br>
Curso:Sitemas de Informação</br>

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

![Screenshot](Dados_dojot.png)

