---
title: "[Sucesso]-macOS-Ventura-13-0-Gigabyte-B460M-DS3H-RX-580-i7-11700. Boot de 22 segundos"
header:
  teaser: /assets/images/detalheMacOsVenturaTeaser.jpg
excerpt_separator: "<!--more-->"
categorias:
  - Blog
  - TI
  - SO
tags:
  - Hackintosh
  - macOS Ventura
  - DIY
  - Faça você mesmo
---

![Imagem da instalação](/assets/images/detalheMacOsVenturaTeaser.jpg){: .align-center}

Um brother tava precisando atualizar seu hackintosh para testar as features novas dos seus apps preferidos. Não conseguindo atualizar, ele me mandou a maquina pra eu fazer o update. Ao final da instalação, a maquina estava dando boot de 22 segundos.

Nesse artigo vou compartilhar o passo a passo de como eu instalei e configurei esse pce considerações sobre o processo de instalação e sobre a importancia de compartilhar conhecimentos na perspectiva de contribuir para o avanço social, científico e tecnológico da humanidade.


![Imagem do hardware](/assets/images/hardware.jpg){: .align-center}

Vamos ao hardware da maquina.

|Placa mãe|Gigabyte B460M DS3H|
|CPU|Intel i7-11700|
|RAM|Corsair DDR4 2666 MHz 16GB Dual channel total 32GB|
|GPU|AMD RADEON XFX RX 580|
|ROM| SanDisk SSD PLUS 480GB SATA|

Hora do passo a passo

Primeiramente precisamos de um pendrive de pelo menos 16GB
(É fundamental efetuar backup de todos seus arquivos, pois esse processo irá apagar seu pendrive)

Vamos preparar o pendrive.
Esse processo poderar ser feito em macos, windows ou distribuições linux.

1. Baixe a imagem raw --VENTURA Olarila-- do site Olarila <a href="https://www.olarila.com/topic/6278-hackintosh-and-macintosh-olarila-vanilla-images-macos-installer/" target=_blank>Clique aqui</a><br>Considere pingar algum clicando em um dos botões de doação. O trabalho deles tornou a instalação do pendrive tão simples quanto instalar uma iso linux/windows.
![Imagem da tela de Download do site Olarila](/assets/images/olarila.jpg){: .align-center}

2. Baixe o Balena Etcher para o seu sistema operacional <a href="https://www.balena.io/etcher/" target=_blank>Clique aqui</a>
![Imagem da tela de Download do Balena Etcher](/assets/images/balenaEtcherDownload.jpg){: .align-center}

3. Execute o Balena Etcher <br>
  3.1 Clique em Flash from file, aponte para o arquivo "Olarila Ventura.raw" que você baixou do site Olarila
  ![Imagem da tela inicial do Balena Etcher](/assets/images/balenaEtcherFlashFromFile.jpg){: .align-center}<br>
  3.2 Clique em Select target para selecionar o pendrive
  ![Imagem da tela do Balena Etcher](/assets/images/balenaEtcherSelectTarget.jpg){: .align-center}<br>
  3.3 Escolha o pendrive e clique em Select.
  ![Imagem da tela de seleção do Balena Etcher](/assets/images/balenaEtcherSelectTarget2.jpg){: .align-center}<br>
  3.4 Clique em Flash.
  ![Imagem da tela do Balena Etcher](/assets/images/balenaEtcherFlash.jpg){: .align-center}<br>
  3.5 Aguarde o processo de instalação.
  ![Imagem da tela do Balena Etcher](/assets/images/balenaEtcherFlashing.jpg){: .align-center}<br>
  3.6 Ao final seu pendrive está pronto. Feche o Balena Etcher, remova o pendrive com segurança e bora para a maquina.
  ![Imagem da tela do Balena Etcher](/assets/images/balenaEtcherFlashed.jpg){: .align-center}<br>

4. Coloque o pendrive e ligue o computador, configure sua bios para inicializar pelo pendrive (pesquise sobre "Boot usb + o modelo da sua placa mãe ou notebook" para saber como), salvar e sair, o computador deverá reiniciar e carregar o boot loader pelo pendrive

5. Na tela do boot loader verifique se está selecionado Install macOS Ventura.
![Imagem da tela do Boot loader](/assets/images/bootLoader.jpg){: .align-center}<br>

6. Por fim, basta seguir os passos da instalação.