# Pinguim Batedor (Flappy Penguin)

Cena ilustrada e animada construída com **HTML5** e **CSS3** puro como parte da trilha de **Web Design Responsivo** do [freeCodeCamp](https://www.freecodecamp.org/).

## Visão geral

O projeto monta uma composição em camadas (`position`, `z-index`, gradientes e formas geométricas com `border-radius` e `transform`), adiciona uma animação contínua de aceno no braço esquerdo com `@keyframes` e aplica interação de escala e cursor ao pressionar o pinguim (`:active` + `transition`).

## Destaques técnicos

- **Variáveis CSS (`:root`):** centralização de cores do personagem (`--penguin-face`, `--penguin-picorna`, `--penguin-skin`).
- **Camadas e posicionamento:** composição do cenário (`sun`, `left-mountain`, `back-mountain`, `ground`) e do personagem (`penguin-head`, `penguin-body`, `arm`, `foot`) com controle de profundidade via `z-index`.
- **Animação e interatividade:** keyframes em `wave` com `transform-origin`, `rotate()` e `scaleX(-1)`, feedback em `.penguin:active` com `scale(1.5)` e `cursor: not-allowed`, transição suave com `transition` e altura dinâmica do solo com `calc(100vh - 300px)`.

## Como visualizar

1. Clone ou baixe o repositório:
   ```bash
   git clone [https://github.com/savioo-dev/pinguim-batedor.git](https://github.com/savioo-dev/pinguim-batedor.git)
