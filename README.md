Sistema de Biblioteca — Modelagem UML

Turma: Informática 204
Curso: Técnico em Informática
Professor: Fábio

Integrantes

Marilayne Batista Ferreira

Graziela Ribeiro dos Santos

Eduarda Silva Lima

Alessandra Ramos


Descrição do projeto

Este projeto consiste na modelagem UML de um Sistema de Biblioteca, desenvolvido como atividade da disciplina de Informática.

O sistema é composto por 6 classes que possuem atributos, métodos e relacionamentos entre si, representando o funcionamento básico de uma biblioteca.

Classes

1. Biblioteca

Atributos:

nome

endereço


Métodos:

cadastrarLivro()

cadastrarUsuario()


2. Livro

Atributos:

título

ISBN

anoPublicacao


Métodos:

emprestar()

devolver()


3. Autor

Atributos:

nome

nacionalidade


Métodos:

escreverLivro()


4. Usuario

Atributos:

nome

matrícula


Métodos:

realizarEmprestimo()

devolverLivro()


5. Emprestimo

Atributos:

dataEmprestimo

dataDevolucao


Métodos:

realizar()

finalizar()


6. Funcionario

Atributos:

nome

matrícula


Métodos:

registrarEmprestimo()

cadastrarLivro()


Relacionamentos

Biblioteca → Livro: cadastra livros.

Biblioteca → Usuario: cadastra usuários.

Autor → Livro: escreve livros.

Usuario → Emprestimo: realiza empréstimos.

Emprestimo → Livro: envolve um livro.

Funcionario → Emprestimo: registra empréstimos.

Funcionario → Livro: cadastra livros.


Objetivo

Aplicar conceitos de UML, classes, atributos, métodos e relacionamentos, desenvolvendo uma representação organizada de um sistema de biblioteca e disponibilizando o projeto no GitHub.
