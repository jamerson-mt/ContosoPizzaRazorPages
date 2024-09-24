# ContosoPizza Razor Pages

Esta é uma aplicação de exemplo criada com **ASP.NET Core** usando **Razor Pages**, permitindo gerenciar uma pizzaria com operações de CRUD para pizzas e gerenciamento de pedidos de clientes.

## Índice
- [Introdução](#introdução)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Começar](#como-começar)
- [Estrutura das Páginas](#estrutura-das-páginas)
- [Contribuição](#contribuição)

## Introdução
A aplicação **ContosoPizza** foi criada como parte do aprendizado da plataforma **ASP.NET Core** pela docuemntação fornecida pelo **Microsoft Learn** e demonstra funcionalidades básicas de uma aplicação web, permitindo criação, leitura, atualização e exclusão (CRUD) de pizzas.

## Funcionalidades
- Criar, visualizar, atualizar e deletar pizzas.
- Listar pizzas disponíveis.

## Tecnologias Utilizadas
- **ASP.NET Core** - Framework para o desenvolvimento da aplicação.
- **Razor Pages** - Para a construção da interface do usuário.

## Como Começar

### Pré-requisitos
- [.NET SDK 7.0.0](https://dotnet.microsoft.com/download) instalado.
- Um editor de código, como o [Visual Studio Code](https://code.visualstudio.microsoft.com/) ou o [Visual Studio](https://visualstudio.microsoft.com/).

### Instalação
1. Clone o repositório:
    ```bash
    git clone https://github.com/jamerson-mt/ContosoPizzaRazorPages.git
    cd ContosoPizzaRazorPages
    ```
2. Instale as dependências e compile o projeto:
    ```bash
    dotnet restore
    dotnet build
    ```
3. Rode a aplicação localmente:
    ```bash
    dotnet run
    ```
   A aplicação estará disponível em: `https://localhost:5001`.

### Armazenamento de Dados
Este projeto utiliza um arquivo SQLite para armazenar dados durante a execução. As alterações nos dados serão reiniciadas sempre que a aplicação for parada ou reiniciada.

## Estrutura das Páginas
- **/Pages/Pizzas/Index.cshtml** - Lista todas as pizzaz, permite criar e remover as existentes.


## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

---
