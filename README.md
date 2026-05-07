# ♟️ Chess System

Projeto de um jogo de xadrez desenvolvido em Java utilizando Programação Orientada a Objetos.

A aplicação roda diretamente no terminal/console, utilizando uma interface textual para exibir o tabuleiro, peças, movimentos e status da partida.

O projeto foi desenvolvido durante os estudos do curso de Java da Udemy, com foco na prática de lógica de programação, modelagem orientada a objetos e implementação das regras oficiais do xadrez.

---

# 🚀 Tecnologias utilizadas

* Java
* Programação Orientada a Objetos (POO)
* Git
* GitHub

---

# 🧠 Conceitos praticados

Durante o desenvolvimento deste projeto foram aplicados conceitos importantes de desenvolvimento backend e orientação a objetos:

* Herança
* Polimorfismo
* Encapsulamento
* Abstração
* Tratamento de exceções
* Enumerações
* Composição
* Manipulação de matrizes
* Regras de negócio

---

# ♟️ Funcionalidades implementadas

* Movimentação de peças
* Validação de jogadas
* Controle de turnos
* Captura de peças
* Verificação de xeque
* Verificação de xeque-mate
* Roque (Castling)
* En Passant
* Promoção de peão
* Interface textual via console

---

# 📂 Estrutura do projeto

```bash
src
 ├── Application
 ├── Boardgame
 └── chess
```

## 📁 Application

Responsável pela execução da aplicação e interação com o usuário.

### Classes:

* `Programan.java`
* `UI.java`

---

## 📁 Boardgame

Contém a estrutura genérica do tabuleiro.

### Classes:

* `Board.java`
* `BoardException.java`
* `Piece.java`
* `Position.java`

---

## 📁 chess

Contém toda a lógica específica do jogo de xadrez.

### Classes principais:

* `ChessMatch.java`
* `ChessPiece.java`
* `ChessPosition.java`
* `ChessException.java`
* `Color.java`

### Peças implementadas:

* `King.java`
* `Queen.java`
* `Rook.java`
* `Bishop.java`
* `Knight.java`
* `Pawn.java`

---

# ▶️ Como executar o projeto

## Pré-requisitos

* Java JDK 17+ (ou versão compatível)

---

## Clone o repositório

```bash
git clone https://github.com/lucascrippa7/Chess.git
```

---

## Acesse a pasta do projeto

```bash
cd Chess
```

---

## Execute a aplicação

Execute a classe principal localizada em:

```bash
src/Application/Programan.java
```

---

# 💻 Interface da aplicação

O sistema utiliza uma interface textual executada diretamente no terminal.

Através dela é possível:

* Visualizar o tabuleiro
* Selecionar posições
* Movimentar peças
* Acompanhar peças capturadas
* Verificar estados de xeque e xeque-mate

---

# 📚 Objetivo do projeto

Este projeto foi desenvolvido principalmente para fins de estudo e prática de:

* lógica de programação;
* orientação a objetos;
* modelagem de domínio;
* implementação de regras complexas;
* organização de código Java.

Projetos de xadrez são excelentes exercícios para consolidar raciocínio lógico e arquitetura de software.

---

# 👨‍💻 Autor

Desenvolvido por Lucas Crippa.

GitHub:

[https://github.com/lucascrippa7](https://github.com/lucascrippa7)
