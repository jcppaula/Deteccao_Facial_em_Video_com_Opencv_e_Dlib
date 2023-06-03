[![author](https://img.shields.io/badge/author-juliocezar-red.svg)](https://www.linkedin.com/in/j%C3%BAlio-c%C3%A9zar-de-paula-0b64b8226) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/jcppaula/data_science/issues)

# Detecção Facial em vídeo usando OpenCV e Dlib

Este é um projeto de um Detector Facial. O programa utiliza técnicas de Visão Computacional e Aprendizado de Máquina para identificar e localizar pontos específicos no rosto de uma pessoa, como os olhos, nariz e boca em um fluxo de vídeo em tempo real.

<p align="center">
  <img src="deteccao_facial_video.gif" >
</p>

## Estrutura do Projeto

A estrutura do projeto é a seguinte:
```
.
├── main.py
├── requirements.txt
└── shape_predictor_68_face_landmarks.dat
```

## Descrição dos arquivos:

* `main.py`: script Python principal que contém a lógica do detector facial.
* `requirements.txt`: arquivo que lista as dependências necessárias para executar o programa.
*  `shape_predictor_68_face_landmarks.dat`: shape_predictor_68_face_landmarks.dat - [baixe por esse link](https://github.com/italojs/facial-landmarks-recognition/raw/master/shape_predictor_68_face_landmarks.dat)

#Pré-requisitos
Para executar este projeto, você precisa ter o Python instalado em seu sistema, eu estou usando a versão *3.8.5*. As dependências do projeto são listadas no arquivo requirements.txt e podem ser instaladas com o seguinte comando:

```
pip install -r requirements.txt
```

## Detalhes do Projeto

Este programa detecta os marcos faciais no rosto de uma pessoa em um fluxo de vídeo. O processo ocorre nas seguintes etapas:

1. Captação do fluxo de vídeo em tempo real através da webcam.
2. Detecção de rostos na imagem utilizando o detector de rostos do dlib.
2. Detecção dos marcos faciais usando o preditor de marcos faciais do dlib.

O programa utiliza o detector de marcos faciais do dlib para determinar a posição dos olhos, olhos nariz e boca da pessoa. 








**Sobre mim:**
* [LinkedIn](https://www.linkedin.com/in/j%C3%BAlio-c%C3%A9zar-de-paula-0b64b8226/)
* [Medium](https://medium.com/@jcp.paula17)
* [Portfólio](https://github.com/jcppaula/Portfolio)
