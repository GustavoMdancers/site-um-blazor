# SiteUmBlazor

Aplicação web desenvolvida com Blazor em .NET, criada para demonstrar o uso de componentes interativos, navegação entre páginas e layouts de uma interface moderna.

## Visão geral

O projeto é um pequeno site em Blazor Web App que inclui páginas de exemplo para:

- Página inicial
- Sobre
- Contador
- Mensagem
- Placar
- Weather
- Página de erro e not found

A estrutura foi montada como base para desenvolvimento de páginas, testes de componentes e aprendizado de Blazor Server.

## Tecnologias utilizadas

- .NET 10
- ASP.NET Core
- Blazor Web App
- C#
- Bootstrap
- Razor Components

## Estrutura do projeto

```text
site-um-blazor/
├── SiteUmBlazor/
│   ├── Components/
│   │   ├── Layout/
│   │   ├── Pages/
│   │   ├── App.razor
│   │   └── Routes.razor
│   ├── Properties/
│   ├── wwwroot/
│   ├── Program.cs
│   ├── appsettings.json
│   ├── appsettings.Development.json
│   └── SiteUmBlazor.csproj
├── README.md
└── LICENSE
```

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- .NET SDK 10.0 ou superior
- Um editor como VS Code ou Visual Studio

## Como executar

No terminal, na raiz do projeto, execute:

```bash
dotnet restore
dotnet run --project SiteUmBlazor
```

Depois disso, a aplicação será iniciada e o endereço local normalmente será exibido no terminal, como:

```text
https://localhost:XXXX
```

Acesse a URL informada no navegador para visualizar o site.

## Páginas principais

- `/` — Home
- `/sobre` — Página sobre o projeto
- `/contador` — Demonstra contador interativo
- `/mensagem` — Exemplo de mensagem e interação
- `/placar` — Página com placar/score
- `/weather` — Exemplo de página com dados simulados

## Observações

Este projeto funciona como uma base inicial para aplicações Blazor, com navegação e componentes reativos prontos para extensão. É uma ótima estrutura para evoluir com novas telas, serviços e lógica de negócio.

## Licença

Este projeto está licenciado sob a licença contida no arquivo [LICENSE](LICENSE).
