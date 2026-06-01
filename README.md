# Space Combat

Projeto final da disciplina de Introdução a Algoritmos/Programação, desenvolvido com Python e Pygame.

O jogo consiste em controlar uma nave espacial que deve desviar de meteoros para sobreviver o maior tempo possível.

## Integrantes do grupo

- Iury Emanuel Alves da Silva

## Estrutura do projeto

- `main.py`: ponto de entrada da aplicação.
- `src/`: código-fonte principal do jogo (loop, regras, sprites e dados).
- `assets/`: imagens, fontes e sons.
- `data/`: arquivos persistentes (recorde/ranking).
- `tests/`: testes unitários com `pytest`.
- `docs/`: documentação do projeto, incluindo proposta inicial.

## Descrição do jogo

> O jogador controla uma nave espacial que se move horizontalmente na parte inferior da tela. Meteoros caem do topo da tela em posições aleatórias. O objetivo é desviar dos meteoros e sobreviver o maior tempo possível.

> A dificuldade aumenta conforme o tempo de jogo.

## Objetivo do jogador

> O objetivo é sobreviver o maior tempo possível desviando dos meteoros e alcançando a maior pontuação possível.

## Regras do jogo

- O jogador controla uma nave com o teclado.
- Meteoros aparecem aleatoriamente no topo da tela.
- Colidir com um meteoro encerra a partida.
- A pontuação aumenta conforme o tempo de sobrevivência.
- O recorde é salvo automaticamente em arquivo.

## Controles

- Seta para esquerda: mover a nave para a esquerda
- Seta para direita: mover a nave para a direita
- ESC: sair do jogo

## Como executar o projeto

### 1. Instalar dependências

```bash
pip install -r requirements.txt
```

## Como executar os testes

```bash
python -m pytest
```

## Checklist mínimo para entrega

- Preencher este README com nome final, descrição real, regras e controles do jogo.
- Atualizar `docs/proposta.MD` com a proposta do grupo.
- Garantir que o jogo executa com `python main.py`.
- Garantir que os testes passam com `pytest`.

## Observações para os alunos

- Mantenham o código organizado em módulos pequenos e com responsabilidade clara.
- Comentem partes importantes da lógica, principalmente regras do jogo.
- Registrem decisões técnicas no README do grupo ao longo do desenvolvimento.
