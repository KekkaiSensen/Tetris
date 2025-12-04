# Tetris em Python

Este projeto é uma implementação básica do **Tetris** usando **Python 3** e a biblioteca **Pygame**.  
Além disso, possui uma suíte de testes usando **unittest** para validar a movimentação das peças.

---

## Conteúdo do Projeto

- `tetris.py` – Código principal do jogo, contendo a lógica de movimentação das peças e a interface gráfica.  
- `test_tetris.py` – Arquivo de testes que verifica se a movimentação das peças está funcionando corretamente.  
- **Dependências:** Python 3.x, Pygame.

---

## Funcionalidades

### Jogo

- Exibe uma janela de 500x500 pixels.
- Permite movimentar as peças com as teclas:
  - `SETAS ESQUERDA` – mover para a esquerda
  - `SETAS DIREITA` – mover para a direita
  - `SETAS CIMA` – mover para cima
  - `SETAS BAIXO` – mover para baixo
  - `R` – sair do jogo
- Peças desenhadas com cores aleatórias.
- Controle básico de colisão com as bordas da janela.

### Testes

O arquivo `test_tetris.py` contém testes unitários que verificam:

- Movimentação para esquerda, direita, cima e baixo.
- Se a peça não ultrapassa os limites da janela.

Para rodar os testes:

```bash
python3 test_tetris.py
