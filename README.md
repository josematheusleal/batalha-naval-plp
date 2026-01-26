# Projeto Batalha Naval – PLP

Este é um **projeto acadêmico da disciplina PLP**, desenvolvido em **JavaScript**

---

## Equipe

* Leticia
* Luana Vitoria
* Matheus
* Melissa
* Vinicius Mendes
* Yasmin Muniz
---

## Regras básicas do projeto

* ❌ Ninguém pode alterar a branch `main` diretamente
* ✅ Toda mudança deve ser feita em uma **branch própria**
* ✅ Toda branch deve virar um **Pull Request**
* ✅ Todo Pull Request precisa de **aprovação**

Essas regras ajudam a evitar erros e bagunça no código.

---

## O que é uma branch?

Uma **branch** é uma cópia do projeto para você trabalhar sem atrapalhar os outros.

* `main` → versão principal e estável do projeto
* `feature/*` → onde você desenvolve sua tarefa

Exemplo de branch:

```
feature/tabuleiro-backend
```

---

## 🔄 Como trabalhar no projeto (passo a passo)

### 1️⃣ Atualizar o projeto antes de começar

Sempre faça isso primeiro:

```bash
git pull origin main
```

---

### 2️⃣ Criar uma branch para sua tarefa

```bash
git checkout -b feature/nome-da-tarefa
```

Exemplo:

```bash
git checkout -b feature/interface-inicial
```

---

### 3️⃣ Fazer alterações no código

* Edite os arquivos
* Salve normalmente no VS Code

---

### 4️⃣ Ver o que foi alterado

```bash
git status
```

---

### 5️⃣ Criar um commit

```bash
git add .
git commit -m "tipo: descrição do que foi feito"
```

Exemplo:

```bash
git commit -m "feat: cria tabuleiro do jogo"
```

---

### 6️⃣ Enviar sua branch para o GitHub

```bash
git push origin feature/nome-da-tarefa
```

---

### 7️⃣ Abrir um Pull Request (PR)

No GitHub:

* Clique em **Compare & Pull Request**
* Explique rapidamente o que você fez
* Aguarde alguém aprovar

⚠️ **Somente depois da aprovação o código entra na `main`.**

---

## Guia de Commits

Use sempre este formato:

```
tipo: o que você fez
```

### Tipos que vamos usar

#### `feat` → quando criar algo novo

```
feat: cria tabuleiro do jogo
feat: adiciona tela inicial
```

#### `fix` → quando corrigir algo errado

```
fix: corrige erro ao atacar posição repetida
```

#### `chore` → organização ou criação de arquivos

```
chore: cria estrutura de pastas
```

#### `docs` → documentação

```
docs: adiciona cronograma do projeto
```

---

### O que NÃO fazer

* Não usar commits como:

  * `update`
  * `ajustes`
  * `mudanças`
* Não subir tudo de uma vez sem explicar
* Não mexer direto na branch `main`

---

## Organização do Projeto (visão geral)

```
backend/    → regras do jogo e lógica
frontend/   → telas, botões e interface
docs/       → documentação do projeto
data/       → dados salvos (ex: ranking)
```
