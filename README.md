# myfinance-web-donet
MyFinance - Projeto do Curso de Pos-Graduação em Engenharia de Software da PUC-MG

## Descrição
Plataforma web que possibilita que os usuarios registrem suas receitas e despesas, para que possam ter uma analise de seus gastos e consequentemente desenvolver um melhor planejamento financeiro.
A aplicação permite o usuário criar categorias personalizadas para suas transações de despesas e receitas.

## Arquitetura

A arquitetura utilizada no projeto foi MVC (Model-View-Controller) que organiza o software em três componentes principais: Model (Modelo) gerencia os dados, View (Visão) responsável por exibeir informações ao usuário e passando as interações para a Controller (Controladora) que processa essas informações e realiza a comunicação com o model e atualizando a view quando necessário.

<img src="/myfinance-web-netcore/Image/DiagramaArquitetura.png">

## Requisitos

- ASP.NET Core: Versão 7.0

- Microsoft SQL Server

## Configurando o ambiente local

1. Clone o repositório do projeto:

   ```
   https://github.com/ArthurCoelhob/myfinance-web-donet.git
   ```

2. Acesse o diretório do projeto:

   ```
   cd myfinance-web-netcore
   ```

3. Instale os pacotes do projeto:

   ```
   dotnet add package Microsoft.EntityFrameworkCore --version 7.0.13
   dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 7.0.13
   dotnet add package AutoMapper --version 12.0.1
   dotnet add package AutoMapper.Extensions.Microsoft.DependencyInjection  --version 12.0.1
   ```

4. Crie o banco de dados utilizando o script "myfinanceweb.sql"

## Executando o projeto

1. Para executar, utilize os seguintes comandos dentro da pasta "myfinance-web-netcore" do projeto:

   ```
   dotnet build
   dotnet run
   ```

2. O servidor será iniciado e estará acessível em um dos seguinte endereços:

  ```
   https://localhost:7217
   http://localhost:5019
   ```
