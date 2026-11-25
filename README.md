# CRUD de Livros em Java

Sistema de cadastro de livros feito em Java, rodando pelo console. Dá pra listar, adicionar, atualizar e deletar livros, e os dados ficam salvos em um arquivo de texto, então não somem quando o programa fecha.

## O que ele faz
- Lista todos os livros cadastrados
- Adiciona um livro novo (título, autor e ano de publicação)
- Atualiza os dados de um livro pelo ID
- Deleta um livro pelo ID
- Salva e carrega tudo automaticamente do arquivo `livros.txt`

## Tecnologias e conceitos
- Java
- Programação orientada a objetos (classe `Livro` com atributos, getters e setters)
- Coleções (`List` / `ArrayList`)
- Leitura e escrita de arquivos (`BufferedReader` e `BufferedWriter`)
- Entrada de dados com `Scanner`

## Como rodar
1. Clone o repositório
2. Na pasta que contém `projetosjava`, compile:
   ```
   javac projetosjava/*.java
   ```
3. Execute:
   ```
   java projetosjava.MenuConsole
   ```

## Estrutura
- `Livro.java`: modelo do livro (id, título, autor, ano)
- `MenuConsole.java`: menu e lógica do CRUD

## Ideias de melhoria
- Permitir vírgula no título (hoje ela é o separador do arquivo)
- Validar entradas inválidas, como letras onde se espera número
- Usar um banco de dados (SQL) no lugar do arquivo de texto
