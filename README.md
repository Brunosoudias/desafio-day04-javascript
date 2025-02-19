
# Jogo da Velha

Este é um simples jogo da velha (tic-tac-toe) implementado em HTML, CSS e JavaScript.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- index.html: Contém a estrutura HTML do jogo.
- style.css: Contém os estilos CSS para o layout e aparência do jogo.
- script.js: Contém a lógica JavaScript para o funcionamento do jogo.

## Como Jogar

1. Abra o arquivo index.html em um navegador web.
2. O jogo será exibido com um tabuleiro 3x3.
3. Clique em qualquer célula vazia para fazer sua jogada.
4. O jogo alternará automaticamente entre os jogadores "X" e "O".
5. O jogo detectará automaticamente quando houver um vencedor ou um empate.
6. Clique no botão "Resetar" para reiniciar o jogo a qualquer momento.

## Funcionalidades

### HTML (`index.html`)

- Estrutura básica do documento HTML.
- Contém o tabuleiro do jogo, informações sobre o jogador atual e o vencedor, e um botão de reset.
- Inclui o arquivo CSS (`style.css`) e o arquivo JavaScript (`script.js`).

### CSS (`style.css`)

- Define o layout e a aparência do jogo.
- Estiliza o tabuleiro, as células, as informações do jogo e o botão de reset.
- Utiliza flexbox e grid para o layout responsivo.

### JavaScript (`script.js`)

- Define a lógica do jogo, incluindo a alternância de jogadores, verificação de vencedor e reinicialização do jogo.
- Manipula o DOM para atualizar o tabuleiro e as informações do jogo.

#### Variáveis Globais

- `quadro`: Objeto que representa o estado atual do tabuleiro.
- `playing`: Booleano que indica se o jogo está em andamento.
- `vez`: String que indica o jogador atual ("x" ou "o").
- `warning`: String que armazena a mensagem de aviso (vencedor ou empate).

#### Funções

- `reset()`: Reinicia o jogo, define o jogador inicial aleatoriamente e limpa o tabuleiro.
- `renderQuadro()`: Atualiza o tabuleiro com base no estado atual.
- `renderInfo()`: Atualiza as informações do jogador atual e do vencedor.
- `togglePlayer()`: Alterna entre os jogadores "x" e "o".
- `checkGame()`: Verifica se há um vencedor ou empate.
- `checkWinnerFor(i)`: Verifica se o jogador `i` venceu.
- `isFull()`: Verifica se o tabuleiro está cheio (empate).

## Como Executar

1. Clone este repositório ou baixe os arquivos.
2. Abra o arquivo index.html em um navegador web.
3. Jogue o jogo da velha!

## Autor

Criado por Bruno Sousa.

