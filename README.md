# tenho que pensar em um.

Projeto final da disciplina de Introdução a Algoritmos/Programação, desenvolvido com Python e Pygame.

Este repositório é um template para os grupos da disciplina. A proposta é começar com uma base funcional e evoluir o jogo ao longo do semestre.

## Integrantes do grupo

- Carlos F. Vieira Da ruz
- Gabriel

## Estrutura do projeto

- `main.py`: ponto de entrada da aplicação.
- `src/`: código-fonte principal do jogo (loop, regras, sprites e dados).
- `assets/`: imagens, fontes e sons.
- `data/`: arquivos persistentes (recorde/ranking).
- `tests/`: testes unitários com `pytest`.
- `docs/`: documentação do projeto, incluindo proposta inicial.

## Descrição do jogo

  A ideia principal é criar um souls like tipo hollow knight, o quanto eu preciso simplificar, eis a questão, mas, pelo menos um boss cabuloso tem que ter. Atualizar no final do projeto.

Exemplo:

> O jogo consiste em controlar um personagem que deve lutar contra inimigos (minions e boss) para [objettivo a ser cnstruido]. O jogador ganha upgrades ao passar de fase e perde vidas ao tomar hits do inimigo. A partida termina quando o jogador morre ou zera o game, (teremos save).

## Objetivo do jogador

Derrotar todos os inimigos da possivel sala, ou fase.

Exemplo:

> O objetivo é coletar a maior quantidade possível de itens antes que o tempo acabe, evitando colisões com os obstáculos.

## Regras do jogo

Liste as principais regras do jogo.

Exemplo:
------------------mudar-------------------------

- O jogador se movimenta usando as setas do teclado.
- Cada item coletado aumenta a pontuação.
- Colidir com um obstáculo reduz a quantidade de vidas.
- A partida termina quando o jogador perde todas as vidas ou quando o tempo acaba.

## Controles
-----------------mudar-------------------------

Informe as teclas ou comandos utilizados no jogo.

Exemplo:

- Seta para cima: mover para cima
- Seta para baixo: mover para baixo
- Seta para esquerda: mover para esquerda
- Seta para direita: mover para direita
- Espaço: realizar ação
- ESC: sair do jogo

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone LINK_DO_REPOSITORIO
cd NOME_DA_PASTA
pip install -r requirements.txt
python main.py
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
