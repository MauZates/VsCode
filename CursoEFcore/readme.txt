Comando Criação de Banco
> - (localdb)mssql\

Comandos Cli
-n = Nome
-o = Diretório
-f = Framework

> Criar Solução 
	> dotnet new sln -n Curso
> Criar Projeto 
	> dotnet new console -n CursoEFcore -f netcoreapp3.1
> Adicionar projeto a solução 
	> dotnet sln Curso.sln add CursoEFCore\CursoEFcore.csproj
> Carregar Projeto
	Entrar no diretório e execultar comando > code .
> Extensão do SqlServer
	> dotnet add CursoEFCore\CursoEFCore.csproj package Microsoft.EntityFrameworkCore.SqlServer -- version 3.1.5

Segundo o Key Bindings, no windows você usa Shift + Alt + F

--Comando Git
Pegar todas as branchs > git fetch
Listar as Branch > git branch -a
Deletar uma branch local > git branch -d nome-da-branch
Deletar uma branch remota > git push origin --delete CursoEfCore

