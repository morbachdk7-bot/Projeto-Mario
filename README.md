# 🎮 Mario Jump

Um jogo inspirado no clássico **Super Mario** desenvolvido com **HTML, CSS e JavaScript**. O objetivo é controlar o personagem e fazê-lo pular para evitar os obstáculos que aparecem no cenário.

## 📌 Sobre o projeto

O projeto foi desenvolvido como uma aplicação web interativa para praticar conceitos fundamentais de desenvolvimento front-end, como:

- Estruturação de páginas com HTML;
- Estilização e posicionamento com CSS;
- Animações utilizando CSS;
- Manipulação do DOM com JavaScript;
- Eventos de teclado;
- Detecção de colisões;
- Controle de animações em tempo real.

O cenário possui um fundo com gradiente, nuvens em movimento, obstáculos e o personagem principal.

## 🕹️ Como jogar

O jogo possui um comando simples:

**⬆️ Pressione qualquer tecla do teclado para fazer o personagem pular.**

O JavaScript adiciona temporariamente a animação `jump` ao personagem, fazendo com que ele alcance uma determinada altura e depois retorne ao chão.

### 🎯 Objetivo

Evite que o personagem colida com o cano.

Quando o personagem se aproxima do obstáculo e sua posição vertical não é suficiente para evitar a colisão, o jogo é encerrado e a imagem do personagem é alterada para `game-over.png`.

## ✨ Funcionalidades

- 🏃 Personagem com movimento de pulo;
- 🟩 Obstáculo em movimento;
- ☁️ Nuvens animadas no cenário;
- 🌤️ Cenário com fundo em gradiente;
- 💥 Sistema de detecção de colisão;
- 🛑 Tela de Game Over;
- ⌨️ Controle através do teclado;
- 🔄 Animações contínuas.

O obstáculo possui uma animação que o movimenta da direita para a esquerda, enquanto as nuvens atravessam o cenário continuamente.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Utilização |
|---|---|
| **HTML5** | Estrutura do jogo |
| **CSS3** | Layout, estilos e animações |
| **JavaScript** | Interação, pulo e colisões |

## 📂 Estrutura do projeto

```text
mario-jump/
│
├── index.html
├── style.css
├── script.js
│
└── images/
    ├── mario.gif
    ├── pipe.png
    ├── clouds.png
    └── game-over.png
```

> A estrutura acima considera os arquivos de imagem referenciados pelo projeto.

## ⚙️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/mario-jump.git
```

### 2. Acesse a pasta

```bash
cd mario-jump
```

### 3. Execute o projeto

Abra o arquivo:

```text
index.html
```

Você também pode utilizar uma extensão como **Live Server** no Visual Studio Code para executar o projeto localmente.

## 🧠 Funcionamento

O JavaScript monitora continuamente a posição do obstáculo e do personagem. Quando os valores indicam uma possível colisão, as animações são interrompidas e o personagem é substituído pela imagem de Game Over.

O pulo é controlado através da classe CSS `.jump`, que utiliza uma animação de aproximadamente **500 ms** para movimentar o personagem para cima e depois fazê-lo retornar ao chão.

## 📚 Objetivo de aprendizagem

Este projeto tem como objetivo colocar em prática conceitos básicos de **desenvolvimento web**, principalmente a integração entre HTML, CSS e JavaScript para criar uma aplicação interativa.

## 🚀 Possíveis melhorias

Algumas funcionalidades podem ser adicionadas futuramente:

- Sistema de pontuação;
- Contagem de recorde;
- Botão de reiniciar;
- Tela inicial;
- Aumento progressivo da velocidade;
- Sons e efeitos;
- Diferentes obstáculos;
- Sistema de vidas;
- Compatibilidade aprimorada com dispositivos móveis.

## 👨‍💻 Autor

**Rafael Morbach**

Projeto desenvolvido para fins de estudo e prática em desenvolvimento web.