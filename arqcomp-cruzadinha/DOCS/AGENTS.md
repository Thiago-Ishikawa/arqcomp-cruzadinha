# AGENTS.md

## Visão geral

Você vai criar um jogo de cruzadinha que roda no navegador para treinar os termos da aula de Tópicos de Arquitetura Computacional. Quem jogar lê a pista e descobre a palavra. Para escrever uma boa pista, você precisa entender o conceito, e é exatamente isso que esta atividade treina. No fim, o seu jogo estará publicado na internet, com o código versionado no GitHub, como acontece
em projetos reais.

## Tecnologias

Construir uma página em HTML, CSS e JavaScript que funcione no navegador, não utilize API's ou outras bibliotecas que estão fora do escopo.

## Comandos

### Versionamento com Git
- `git init` — Inicializa o repositório Git.
- `git add .` — Adiciona os arquivos para versionamento.
- `git commit -m "Descrição da alteração"` — Registra as modificações.

## Arquitetura

1. Tabuleiro com no mínimo 12 palavras da lista, cruzadas entre si: cada palavra cruza com pelo menos uma outra. As 12 palavras a serem adivinhadas são: RAM, ROM, EEPROM, FLASH, CACHE, MEMORIADEMASSA, DMA, ADDRESSBUS, DATABUS, MICROCONTROLADOR, DUALCORE e QUADCORE.
2. Pistas numeradas e separadas em Horizontais e Verticais de maneira organizada e integrada.
3. O jogador digita as letras direto nas casas do tabuleiro.
4. Botão Conferir, que mostra quais palavras estão certas e quais estão erradas.
5. Contador de acertos, por exemplo: "8 de 12 palavras".
6. Botão Reiniciar, que limpa o tabuleiro.
7. Feito em HTML, CSS e JavaScript puros, com o arquivo index.html na raiz do projeto.

## Restrições

• No máximo 15 palavras por pista
• A pista não pode conter a resposta, nem parte dela, nem a sigla por extenso;
• A pista precisa estar correta segundo o e-book e levar a uma única resposta.