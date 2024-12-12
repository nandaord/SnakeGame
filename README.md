# SnakeGame 

🎮 **Um clássico jogo da cobrinha com funcionalidades extras**, desenvolvido em C. O objetivo é guiar a cobra para comer frutas e crescer, enquanto evita colidir com as paredes. A cada nova jogada, sua pontuação é registrada, permitindo competir com amigos para ver quem consegue a maior pontuação!


## 📜 Descrição

SnakeGame é uma versão do clássico jogo da cobrinha, mas com funcionalidades extras que tornam a jogabilidade mais interessante:

- A cobra cresce a cada fruta consumida, o que aumenta a dificuldade.
- Você pode competir com seus amigos para ver quem consegue a maior pontuação.
- O jogo termina se a cobra colidir com as paredes do tabuleiro.
- Sua pontuação é registrada, permitindo ver o seu desempenho ao longo do tempo.
- A velocidade da cobra aumenta e novos desafios surgem conforme o jogo avança. Teste seus reflexos e veja quanto tempo consegue sobreviver enquanto a cobra vai ficando cada vez maior!


## 💻 Instalação

### 🔧 Pré-requisitos

- **Compilador C**: Para compilar o código.
- **Biblioteca ncurses**: Necessária para manipulação de tela no terminal.

Instale o compilador C e a biblioteca ncurses com os seguintes comandos:

#### Para sistemas baseados em Debian (Ubuntu, etc.)

```bash
sudo apt-get install build-essential libncurses5-dev
````

#### Para sistemas baseados em Red Hat (Fedora, CentOS, etc.)

```bash
sudo dnf install ncurses-devel
```


## ⚙️Compilação

1. Clone o repositório:
```bash
git clone https://github.com/xTvini/snakegame.git
```
2. Navegue até o diretório do projeto:
```bash
cd snakegame/snake
```
3. Compile o código-fonte:
```bash
gcc -I./include src/*.c -o main
```


## 🚀Execução
Após a compilação, você pode rodar o jogo com o comando:
```bash
./main
```


## 🎮 Controles
- **W**: Mover para cima
- **S**: Mover para baixo
- **A**: Mover para a esquerda
- **D**: Mover para a direita
- **ESC**: Sair do jogo


## ⚡ Funcionalidades Extras
- **Níveis de Dificuldade**: Escolha entre fácil, médio e difícil, o que ajusta a velocidade da cobra.
- **Inversão da Cobra**: A cada fruta consumida, a cobra inverte a direção. Por exemplo, se estiver indo para cima e pegar uma fruta, ela começará a se mover para baixo.
- **Ranking**: Sua pontuação é salva e você pode competir com seus amigos.


## 👥 Equipe
- **Kauane Melo**: KauaneMelo
- **Maria Fernanda Ordonho**: nandaord
- **Vinícius Diniz**: xTvini
