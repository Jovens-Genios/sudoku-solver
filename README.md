# Sudoku Solver
Neste projeto, você terá que criar um solucionador de Sudoku usando reconhecimento e processamento de imagens!

O Sudoku é um jogo clássico baseado na colocação lógica de números. O objetivo do jogo é a colocação de números de 1 a 9 em cada uma das células vazias numa grade de 9x9, constituída por 3x3 subgrades chamadas regiões. [https://pt.wikipedia.org/wiki/Sudoku](https://pt.wikipedia.org/wiki/Sudoku)

![Sudoku](https://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/Sudoku-by-L2G-20050714.svg/375px-Sudoku-by-L2G-20050714.svg.png)

Até ai tudo bem, nada de novo, né? Agora começa a brincadeira! Para este projeto, você terá que fazer uma aplicação que encontra sozinha a solução para um tabuleiro de Sudoku a partir de uma imagem! Nesta pegada aqui: https://www.linkedin.com/feed/update/urn:li:activity:6712399648167870464/.

## Habilidades desenvolvidas

Você desenvolverá as seguintes habilidades:
* Compreender processamento de imagens por computadores.
* Compreender reconhecimento de dígitos por computadores.
* Escolher e utilizar algoritmos para o reconhecimento de bordas em uma imagem.
* Escolher e utilizar algoritmos para o reconhecimento de dígitos em uma imagem.

## Requisitos e entregáveis

* Reconhecer as bordas de uma tabela de Sudoku a partir de uma imagem.
* Reconhecer os dígitos já preenchidos em cada célula a partir de uma imagem.
* Resolver quais números faltantes devem entrar em cada célula.
* Retornar uma imagem final com os números faltantes preenchidos nela (com a solução do Sudoku).

Bônus:
* Fazer todas essas funcionalidades acontecerem em tempo real ao mostrar um tabuleiro de Sudoku incompleto na câmera. Como neste vídeo: https://www.linkedin.com/feed/update/urn:li:activity:6712399648167870464/.

## Stack

Você pode alcançar esses resultados de distintas formas. No entanto, sugiro a seguinte stack e conjunto de ferramentas:
* Python
* OpenCV (para reconhecimento das bordas).
* Keras ou OpenCV (para reconhecimento dos dígitos).

## Materiais e recomendações

Como este é um projeto grande, você pode pensar nele como 3 projetos ou fases separadas: reconhecimento de bordas, reconhecimento de dígitos e algoritmo para resolver o Sudoku. Recomendo que faça cada uma dessas etapas separadamente. Cada uma é uma vitória!

Além disso, crie um repositório no Github para este projeto, com boa documentação. Se você ainda não sabe como utilizar o Git para fazer controle de versão no seu código, esta é uma boa [Introdução ao Git](https://blog.dankicode.com/introducao-ao-git-e-github/).

### Materiais recomendados

* [LEARN OPENCV in 3 HOURS with Python | Including 3xProjects | Computer Vision](https://www.youtube.com/watch?v=WQeoO7MI0Bs)
