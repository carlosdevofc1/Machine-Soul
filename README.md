# Machine soul.

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

  A ideia principal é criar um souls like inspirado em hollow knight e skull: the hero slayer, onde faremos o player lutar contra inimigos e avançar na história.

Exemplo:

> O jogo consiste em controlar um personagem que deve lutar contra inimigos (minions e boss) para tentar reviver a humanidade e compreender como foi seu fim. O jogador ganha upgrades ao passar de fase e perde vidas ao tomar hits do inimigo. A partida termina quando o jogador morre ou zera o game, (teremos save).

## Objetivo do jogador

Derrotar todos os inimigos da sala, ou fase.

Exemplo:

> Nas salas normais o objetivo vai variar entre matar todos os minions e sobreviver por certo tempo.
> Em uma sala de Boss, o único objetivo é vencer o inimigo.

## Regras do jogo

Liste as principais regras


- O jogador se movimenta usando as setas do teclado.
- Caso perca todas as vidas o player morre.
- Existem 3 dificuldades, normal, hard e alma-pura.
- só é possível jogar a dificuldade alma-pura após zerar o game em qualquer outra dificuldade.

## Controles


Informe as teclas ou comandos utilizados no jogo.

Exemplo:

- AD para movimentação geral.
- Barra de espaço ou B para saltar.
- Q ou C para dar dash.
- E para ataque simples.
- F para ataque especial.
- ESC para pausar o jogo.

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
