<div> 
<p><a href="https://github.com/JosiTubaroski/Novo_Sircoi/blob/main/README.md">Home</a></p>
</div> 

# WEB API com .NET 8 e SQL-Server

### Como funciona a estrutura de projetos Web-API .Net8?

A estrutura de um projeto Web API em .NET 8 é organizada de forma modular e segue boas práticas para garantir a escabilidade, manutenção e clareza de código. Vamos explorar como essa estrutura funciona, os principais componentes e como eles se integram:

### Estrutura Básica de um Projeto Web API .NET 8

Quando você cria um projeto Web API no .NET 8 (usando o Visual Studio, Visual Studio Code ou CLI do .NET), a estrutura inicial é gerada automaticamente. Aqui está uma visão geral dos principais componentes:

### 1. Pasta Controllers:

- Contém os controladores da API, que são classes que lidam com requisições HTTP.
- Cada controlador geralmente corresponde a um recurso da API (ex.: ProdutosController, UsuariosController).

<img src="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server/blob/main/img/Estrutura/01_Controler_Exemplo.png"/>

### 2. Pasta Models:

- Contém as classes que representam os dados da aplicação (entidades).
- Essas classes são usadas para mapear objetos para o banco de dados (Entity Framework) ou para serializar/deserializar dados JSON.

<img src="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server/blob/main/img/Estrutura/02_Models_Exemplo.png"/>

### 3. Pasta Data:

- Contém classes relacionadas ao acesso a dados, como o DbContext do Entity Framework.

<img src="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server/blob/main/img/Estrutura/03_Data_Exemplo.png"/>

### 4. Pasta Service:



Aula: https://www.youtube.com/watch?v=bnAuqSgmTyc

<div> 
<p><a href="https://github.com/JosiTubaroski/Web_API_CriarProjeto/blob/main/README.md">01. Criando Projeto .NET8 </a></p>
</div> 

<div> 
<p><a href="https://github.com/JosiTubaroski/Web_API_CriarProjeto/blob/main/README.md">02. Começando o Projeto .NET8, criando AppDbContex </a></p>
</div> 


