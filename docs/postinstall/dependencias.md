---
sidebar_position: 1
---

# Instalar dependências

## DirectX Runtime

O DirectX é um conjunto de APIs necessárias para que os jogos corram e funcionem sem problemas.

Não é necessário instalá-las agora, pois a maioria dos clientes de jogos (Steam, Origin, Uplay, etc.) instalam o DirectX sempre que um jogo é instalado a partir desse cliente. Instalá-las agora irá garantir que não vais encontrar possíveis problemas no futuro e poderá poupar algum tempo em futuras instalações de jogos.

- Transfere e roda o [DirectX End-User Runtime Web Installer](https://www.microsoft.com/en-us/download/details.aspx?id=35)
- Carrega em `I accept the agreement` e depois em `Next`
- Se te oferecer a `Bing Bar`, certifica-te que desligas a opção de a instalar e carrega em `Next`
- Quando acabar a instalação, carrega em `Finish`

## Visual C++ Runtime

Os Runtimes do Visual C++ são necessários para uma vasta gama de programas e jogos. Os Runtimes necessários podem já estar incluídos nos programas que instalas, mas isso nem sempre acontece. Em vez de descarregar e instalar cada Runtime individualmente, vamos utilizar um instalador completo para acelerar o processo.

Tal como os Runtimes do DirectX, é recomendado instalar já o Visual C++ para evitar erros de programa no futuro.

- Vai à [página GitHub](https://github.com/abbodi1406/vcredist/releases/tag/v0.92.0) do vcredist por abbodi1406
- Na secção `Assets`, transfere a versão mais recente do ficheiro `VisualCppRedist.zip`
- Extrai o .zip e roda o instalador