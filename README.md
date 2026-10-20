# Gerenciador de Tarefas

Uma aplicação console simples em .NET para gerenciamento de tarefas, utilizando C# e testes unitários com xUnit.

## Pré-requisitos

Certifique-se de ter o [SDK do .NET](https://dotnet.microsoft.com/download) instalado na sua máquina (versão compatível com o projeto, ex: .NET 8, .NET 9 ou superior).

---

## Como compilar (Build)

Para compilar o código fonte e verificar se há algum erro de sintaxe ou dependência, navegue até o diretório raiz do projeto (onde está o arquivo `.sln` ou na pasta do projeto) e execute:

```bash
dotnet build
```

---

##  Como rodar a aplicação console (Run)

Para iniciar a aplicação console, você pode navegar até a pasta do projeto principal (ex: `GerenciadorTarefas`) e executar o comando de execução. Alternativamente, a partir da raiz, aponte para o projeto:

```bash
dotnet run --project src/GerenciadorTarefas/GerenciadorTarefas.csproj
```
*(Nota: Ajuste o caminho `--project` conforme a estrutura real das pastas do seu repositório).*

---

## Como executar os testes unitários (Test)

Os testes foram escritos utilizando o framework **xUnit**. Para rodar a suíte de testes e validar o comportamento do `TaskManager` e `TaskItem`, execute o seguinte comando na raiz do projeto:

```bash
dotnet test
```

Este comando irá compilar os projetos necessários e apresentar o resultado detalhado dos testes (Passou/Falhou) diretamente no seu console.
