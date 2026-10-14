# Binawar

O **Binawar** é um jogo educativo desenvolvido como um projeto de extensão ludológica, com o objetivo de tornar o aprendizado do sistema de numeração binário mais interativo e acessível. Utilizando Arduino, uma tela LCD e botões físicos, o jogo desafia os participantes a converter números decimais para suas respectivas representações binárias.

## Como funciona?

O sistema gera aleatoriamente um número decimal e o apresenta na tela LCD. O jogador deve realizar a conversão dentro do tempo estabelecido, utilizando os botões do tabuleiro para navegar entre os bits e alternar seus valores entre `0` e `1`. Ao finalizar a resposta, o sistema verifica automaticamente se a conversão está correta e registra o resultado da jogada.

## Modos de jogo

- **Individual:** um jogador realiza cinco conversões durante a partida.
- **1v1:** dois jogadores alternam seus turnos, realizando cinco conversões cada, totalizando dez desafios.

Ao final, o sistema apresenta a quantidade de acertos e erros de cada participante. No modo competitivo, vence quem obtiver mais acertos. Em caso de igualdade, a partida termina em empate.

## Componentes e funcionamento

- **Arduino:** executa a lógica principal do jogo.
- **Tela LCD:** apresenta os números decimais, as informações dos bits e os resultados.
- **Botões físicos:** permitem navegar pelas posições e alterar os valores binários.
- **Sistema de controle:** gerencia os turnos, as rodadas, a validação das respostas e a pontuação.

O Binawar foi planejado para funcionar sem depender de internet, celular ou computador durante as partidas. Cartas poderão ser utilizadas apenas como material de apoio em caso de falhas nos componentes eletrônicos.

## Objetivo educacional

O projeto busca estimular o raciocínio lógico e facilitar a compreensão da conversão entre os sistemas decimal e binário por meio da prática. A proposta também considera a acessibilidade e a facilidade de interação, permitindo que os participantes aprendam com seus erros e concluam todas as rodadas.

## Desenvolvimento

O projeto contempla a modelagem do circuito no Tinkercad, a programação do Arduino e os testes de funcionamento do protótipo. Os níveis de dificuldade, o tempo de resposta e outros detalhes da dinâmica serão ajustados durante o desenvolvimento.
