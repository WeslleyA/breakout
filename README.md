# 🧱 Breakout Game (30 Fases)

Uma versão moderna e cheia de recursos do clássico jogo *Breakout* / *Arkanoid*, desenvolvida em HTML5 Canvas e JavaScript puro (Vanilla JS), com 30 fases progressivas, sistema de *power-ups*, efeitos visuais avançados e efeitos sonoros sintéticos com a Web Audio API.


---

## 📌 Sobre o Projeto

Este projeto é uma recriação robusta e interativa do jogo arcade *Breakout*. O jogo conta com um ciclo de 30 fases de dificuldade progressiva, alterando formações de blocos, velocidade das bolas, blocos móveis, explosivos, blocos que caem e uma série de *power-ups* que modificam a jogabilidade em tempo real.

### 🚀 Funcionalidades

- **30 Fases Únicas e Progressivas:**
  - Formações variadas de blocos (Grade, Pirâmide, Diamante, X, Xadrez, Túnel, Bordas).
  - Blocos com múltiplos pontos de vida (HP 1, 2 e 3).
  - Blocos móveis que deslizam lateralmente e blocos que caem ao serem destruídos.
  - Blocos explosivos 💥 que causam dano em área nos blocos adjacentes.
- **Sistema Completo de Power-ups:**
  - `<==>` **Expandir Raquete:** Aumenta o tamanho da raquete temporariamente.
  - `=><=` **Encolher Raquete:** Diminui o tamanho da raquete.
  - `+1` **Vida Extra:** Adiciona 1 vida ao jogador.
  - `🐢` **Bola Lenta:** Reduz a velocidade de todas as bolas em jogo.
  - `⚡` **Bola Rápida:** Aumenta a velocidade das bolas.
  - `🔄` **Controles Invertidos:** Inverte temporariamente a direção das teclas de movimento.
  - `3x` **Multi-Bolas:** Multiplica o número de bolas em cena.
- **Áudio Sintético (Web Audio API):**
  - Efeitos sonoros retro sem a necessidade de arquivos externos de áudio (rebatidas, explosões, *power-ups*, vitória e derrota).
- **Juice & Efeitos Visuais:**
  - *Screen Shake* (tremor de tela) em colisões fortes e explosões.
  - Sistema de partículas dinâmicas para explosões de blocos.
  - Indicador visual em tempo real dos efeitos ativos na tela.
- **Persistência de Recorde (`localStorage`):**
  - O recorde histórico de pontuação fica salvo no navegador do usuário.

---

## 🎮 Controles

| Ação | Teclas / Comandos |
| :--- | :--- |
| **Mover Raquete para Esquerda** | `Seta para Esquerda` ou `A` |
| **Mover Raquete para Direita** | `Seta para Direita` ou `D` |
| **Ativar Áudio / Iniciar** | `Clique na Tela` ou Pressionar qualquer tecla |
| **Reiniciar Partida (Game Over / Vitória)** | `Espaço` ou `R` |

---

## 🛠️ Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Estrutura e elemento `<canvas>` para renderização de gráficos 2D.
- **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Estilização da interface, layout centralizado e tema escuro.
- **[JavaScript (ES6+)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript):** Lógica principal, detecção de colisão AABB (*Axis-Aligned Bounding Box*), vetores de física, manipulação do DOM e `requestAnimationFrame`.
- **[Web Audio API](https://developer.mozilla.org/pt-BR/docs/Web/API/Web_Audio_API):** Geração sintética de tons e efeitos sonoros via osciladores (`OscillatorNode`).

---

## 💻 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/WeslleyA/NOME-DO-SEU-REPOSITORIO.git](https://github.com/WeslleyA/NOME-DO-SEU-REPOSITORIO.git)# breakout
