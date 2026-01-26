# Arquitetura do Projeto – Batalha Naval

## Visão Geral

O projeto Batalha Naval está dividido em duas partes principais:

- Backend: responsável pelas regras do jogo
- Frontend: responsável pela interface com o usuário

## Backend

Localizado na pasta `backend/`.

Responsabilidades:
- Controle do tabuleiro
- Regras do jogo
- Lógica principal

Principais arquivos:
- `Board.js`: representa o tabuleiro do jogo
- `GameService.js`: controla o fluxo do jogo

## Frontend

Localizado na pasta `frontend/`.

Responsabilidades:
- Interface do usuário
- Interação com o jogador
- Exibição do tabuleiro

Principais arquivos:
- `index.html`: estrutura da página
- `main.css`: estilos
- `app.js`: lógica da interface

## Organização

A separação entre frontend e backend facilita:
- Manutenção do código
- Trabalho em equipe
- Evolução do projeto
