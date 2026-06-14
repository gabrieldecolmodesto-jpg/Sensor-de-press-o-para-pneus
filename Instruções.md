Items Necessarios:

ESP32 c/ display oled

Sensor De pressão SMP3011 - 500kpa

Sensor barometria BMP260

cabo micro USB VS

protoboard 400 pontos

kit barra de pinos - cabos


Software Necessario

Microsoft Visual Studio Code

ESP IDF 5.3.5

Driver do respectivo ESP32

FreeRTOS

Instruções

Monte o projeto conforme a imagem "Montagem.png" anexada

Baixe e instale o driver respectivo do seu esp32


Baixe o programa FreeRTOS em seu computador/notebook no site https://www.freertos.org/

Baixe e instale o Microsoft Visual Code

Instale o ESP IDF 5.3.5 na aba extensões do Microsoft Visual Code e use a opção instalação customizada para poder instalar a versão 5.3.5, nao é necessario instalar opçoes adicionais

Configure o ESP IDF no modo "express"

abra o CMD de seu computador/notebook com privilegios de administrador e rode os seguintes codigos:

git clone https://github.com/eng-software/TreinamentoESP32_Medidor.git --recursive
 
git clone https://github.com/eng-software/TreinamentoESP32_Medidor.git CPP --recursive -b CPP

git clone https://github.com/eng-software/TreinamentoESP32_Medidor.git MUTEX --recursive -b MUTEX


Crie um projeto novo no esp idf dentro do microsoft visual studio

cole o codigo do arquivo Codigo Pronto do sensor no projeto criado e rode o codigo em seu ESP32
