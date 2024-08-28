# Sistema de Cadastro de Livros

Este projeto foi desenvolvido em C# com o objetivo de criar um sistema de gerenciamento de cadastro de livros, funcionários e clientes de uma biblioteca, utilizando conceitos de Programação Orientada a Objetos (POO).

## Funcionalidades Implementadas

- **Configuração da Estrutura Básica do Projeto**: Foi configurada a estrutura inicial do projeto no Visual Studio, criando pastas e arquivos principais necessários para a organização do código.

- **Implementação da Interface `IPessoa`**: Criada a interface `IPessoa`, que define os métodos necessários para operações básicas envolvendo uma pessoa, como cadastro e busca.

- **Implementação da Classe Abstrata `Pessoa`**: Desenvolvida a classe abstrata `Pessoa`, que implementa a interface `IPessoa` e serve como base para as classes `Funcionario` e `Cliente`.

- **Criação das Classes `Funcionario` e `Cliente`**: Implementadas as classes `Funcionario` e `Cliente`, que herdam da classe `Pessoa`. Estas classes são responsáveis por gerenciar os dados específicos de funcionários e clientes no sistema.

- **Implementação da Classe `Livro`**: Desenvolvida a classe `Livro`, que contém os atributos e métodos necessários para gerenciar as informações de um livro na biblioteca.

- **Implementação da Classe `Emprestimo`**: Criada a classe `Emprestimo`, que lida com a lógica de empréstimo de livros, registrando informações sobre qual cliente emprestou qual livro e em que data.

- **Implementação da Classe `Biblioteca`**: Implementada a classe `Biblioteca`, que centraliza as operações do sistema, utilizando as classes e interfaces anteriormente criadas para gerenciar a biblioteca como um todo.

- **Persistência de Dados em JSON**: Foi desenvolvida a classe `GerenciadorDeArquivo`, responsável por salvar e carregar dados em arquivos JSON, garantindo a persistência das informações dos livros, funcionários e clientes.

- **Persistência de Dados em Banco de Dados (Opcional)**: Implementada uma classe adicional para gerenciar a persistência dos dados em um banco de dados, embora essa funcionalidade seja opcional.

## Contribuidores

- **Jefferson Nogueira de Oliveira** - GitHub: [prof-Jefferson](https://github.com/prof-Jefferson)
- **Outro Contribuidor** - GitHub: [jeffjno](https://github.com/jeffjno)
- **joao Pedro Golenia** -  GitHub: [joaolenia](https://github.com/joaolenia)

## Licença

Este projeto está licenciado sob a licença MIT.
