Jogo de corrida 3D inspirado em Mario Kart 64

https://www.youtube.com/watch?v=hxk2yPg_yoU

# INF Kart 3D

## 1. Descrição da Aplicação

Este projeto consiste no desenvolvimento de uma aplicação gráfica 3D interativa inspirada em jogos de corrida como Mario Kart. O usuário controla um veículo em uma pista tridimensional com o objetivo de completar voltas enquanto evita colisões com obstáculos presentes no ambiente.

A aplicação possui lógica de controle não-trivial, incluindo movimentação do veículo, detecção de colisões, controle de câmeras e animação de objetos no ambiente.

## 2. Interação com o Usuário

A interação será realizada através de teclado e mouse:

Teclado:

W / S: acelerar / frear

A / D: virar esquerda / direita

C: alternar entre câmeras

R: reiniciar posição do veículo

## 3. Câmeras Virtuais

Serão implementados dois tipos de câmera:

**Câmera em terceira pessoa (look-at):**

Posicionada atrás do veículo, acompanhando sua movimentação

**Câmera livre:**

Movimentação independente controlada pelo usuário via mouse e teclado

## 4. Objetos Virtuais

A cena conterá os seguintes objetos:

Veículo controlado pelo jogador

Pista de corrida

Obstáculos (paredes, cones)

Objetos decorativos (árvores)

## 5. Transformações Geométricas

Serão aplicadas transformações geométricas nos objetos:

Translação: movimentação do veículo

Rotação: orientação do veículo ao virar

Escala: ajuste de tamanho de objetos da cena

## 6. Testes de Intersecção (Colisão)

Serão implementados testes de colisão entre:

Veículo do jogador e paredes da pista

Veículo do jogador e obstáculos

As colisões impedirão o atravessamento dos objetos, contribuindo para a lógica do jogo.

A implementação será realizada no arquivo separado 

7. Modelos de Iluminação

Todos os objetos da cena utilizarão um modelo de iluminação não-trivial.

Luz ambiente

Luz difusa

Luz especular

## 8. Mapeamento de Texturas

Todos os objetos da cena terão suas cores definidas por texturas.

Textura da pista (asfalto)

Textura do veículo

Textura dos objetos decorativos (árvores, obstáculos)

## 9. Curvas de Bézier

Um objeto (um veículo NPC) terá sua movimentação definida por uma curva de Bézier cúbica.

## 10. Animação Baseada no Tempo

Todas as movimentações da aplicação serão baseadas no tempo (Δt), garantindo comportamento consistente independente da taxa de quadros (FPS).

## 11. Objetivo da Aplicação

O objetivo do usuário será controlar o veículo e percorrer a pista evitando colisões, podendo reiniciar e explorar a cena utilizando diferentes câmeras.

## 12. Funcionalidades Extras

## 13. Considerações Finais

O projeto será desenvolvido em linguagem C++ utilizando OpenGL, com foco em desempenho e interação em tempo real. O desenvolvimento seguirá boas práticas de versionamento com commits incrementais no Git.
