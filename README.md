# Pong Game

## Descrição

Este é um simples jogo Pong implementado em p5.js, uma biblioteca JavaScript para criação de gráficos e interações. O jogo consiste em uma bolinha que rebata entre duas raquetes. O jogador controla uma das raquetes e compete contra uma raquete controlada pelo computador. O objetivo é fazer com que a bolinha passe pela raquete do oponente para marcar pontos.

## Instruções de Uso

1. **Movimentação da Raquete:** Utilize as teclas de seta para cima (UP_ARROW) e para baixo (DOWN_ARROW) para mover a sua raquete para cima e para baixo, respectivamente.

2. **Pontuação:** O jogo marca pontos sempre que a bolinha ultrapassa a raquete do oponente. Os pontos são exibidos no canto superior esquerdo do canvas.

3. **Fim do Jogo:** O jogo não possui um fim definido. Os pontos continuam a ser acumulados à medida que a bolinha ultrapassa as bordas do canvas.

## Variáveis Principais

- **xBolinha, yBolinha:** Coordenadas da bolinha.
- **velocidadeXBolinha, velocidadeYBolinha:** Velocidade da bolinha nos eixos x e y.
- **xRaquete, yRaquete:** Coordenadas da raquete do jogador.
- **xRaqueteOponente, yRaqueteOponente:** Coordenadas da raquete do oponente.
- **meusPontos, pontosDoOponente:** Contagem de pontos do jogador e do oponente.
- **chanceDeErrar:** Probabilidade do oponente errar ao tentar rebater a bolinha.

## Funções Principais

- **mostraBolinha():** Desenha a bolinha na posição atual.
- **movimentaBolinha():** Atualiza as coordenadas da bolinha com base nas velocidades definidas.
- **verificaColisaoBorda():** Verifica se a bolinha atingiu as bordas do canvas e inverte sua direção, se necessário.
- **mostraRaquete(x, y):** Desenha uma raquete nas coordenadas fornecidas.
- **movimentaMinhaRaquete():** Controla a movimentação da raquete do jogador com base nas teclas pressionadas.
- **verificaColisaoRaquete(x, y):** Verifica se a bolinha colidiu com a raquete do jogador e inverte sua direção, se necessário.
- **movimentaRaqueteOponente():** Controla a movimentação da raquete do oponente com base na posição da bolinha.
- **incluiPlacar():** Exibe a contagem de pontos na tela.
- **marcaPonto():** Atualiza os pontos quando a bolinha ultrapassa as bordas do canvas.
- **calculaChanceDeErrar():** Calcula a probabilidade de o oponente errar ao tentar rebater a bolinha.
- **bolinhaNaoFicaPresa():** Garante que a bolinha não fique presa no lado esquerdo do canvas.

## Como Executar

1. Certifique-se de ter p5.js instalado ou incluído em seu projeto.
2. Copie e cole o código em um arquivo JavaScript.
3. Abra o arquivo HTML correspondente no navegador para executar o jogo.

Divirta-se jogando Pong!
