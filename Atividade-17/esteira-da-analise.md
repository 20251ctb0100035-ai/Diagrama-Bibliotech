# Esteira da Análise — BiblioTech

**Estudante:** Anthony Pagani

## Funcionalidade 1: Registrar empréstimo do livro

- **1. Fala do cliente:** "Eu queria poder pegar um livro emprestado sem ficar anotando em caderno."
- **2. História de usuário:** Como leitor, quero registrar o empréstimo de um livro, para levá-lo sem papelada..
- **3. Requisito:** RF01 — O sistema deve permitir registrar o empréstimo de um livro a um leitor.
- **4. Caso de uso (RF01):** Ator Bibliotecário → "Registrar empréstimo" (verbo + objeto)

## Funcionalidade 2: renovar empréstimo do livro

- **1. Fala do cliente:** "Eu queria poder renovar empréstimo do meu livro atual"
- **2. História de usuário:** Como leitor, renovar o empréstimo do meu livro atual por um outro pois não to gostando desse e outro parece ser melhor.
- **3. Requisito:** RF02 — O sistema deve permitir registrar a renovação de um livro emprestado do leitor
- **4. Caso de uso (RF02):** Ator Bibliotecário → "Registrar renovação" (verbo + objeto)

## Rastreabilidade

| Elipse no diagrama | Veio do requisito | Que veio da fala |
|---|---|---|
| | RF01 | "..." |
| | RF02 | "..." |

<!-- Nível A: conte o caminho completo de cada funcionalidade,
     da fala do cliente até o que está desenhado no diagrama. -->

## Relacionamento entre casos de uso (nível A)

- Tipo: «include» ou («extend»)
- Entre: "pesquisar livro" e "Reservar livro"
- Por que é esse e não o outro: Algumas vezes a pessoa ta olhando o livro e não fica interessado nele e pesquisa outro

- Tipo: («include») ou «extend»
- Entre: "reservar livro" e "identificar leitor"
- Por que é esse e não o outro: Depois que o livro for registrado o sistema vai ter que identificar quem o registrou sem confundir com outra pessoa ou errada

## Autoavaliação

**Conceito pretendido:** ___ (A / B / C)

- Conversei sobre esta atividade com: ______ (ou "ninguém")
- Esteira da análise: ______ (diga onde)
- Diagrama e notação: ______
- Rastreabilidade: ______
- Organização da entrega: ______