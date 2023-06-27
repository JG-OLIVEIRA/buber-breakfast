# COMANDOS USADOS


- Para criar o arquivo de solução: 

```bash
- dotnet new sln -o BuberBreakfast
```

- Para criar o arquivo contendo os contratos das classes do projeto:

```bash
- dotnet new classlib -o BuberBreakfast.Contracts
```

- Para criar o arquivo contendo a api
```bash
- dotnet new webapi -o BuberBreakfast
```

- Para adicionar ambas as pastas no arquivo de solução do projeto:

```bash
- dotnet sln add (ls -r **/*.csproj)
```