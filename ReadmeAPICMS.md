<!-- Título -->
<h1 align="center"><strong>API CMS</strong></h1>


<!-- Status -->
<h3 align="center">🚧 Em Desenvolvimento... 🚧</h3>


<!-- Tópicos -->
<h1>🏁 Tópicos</h1>
<ul>
    <li><a href="#sobre">Sobre o Projeto</a></li>
    <li><a href="#funcionalidades">Funcionalidades</a></li>
    <li><a href="#demoApl">Demonstração da Aplicação</a></li>
    <li><a href="#preRequisitos">Pré-requisitos</a></li>
    <li><a href="#tecUtilizadas">Tecnologias Utilizadas</a></li>
    <li><a href="#canaisDigitais">Canais Digitais</a></li>
    <li><a href="#licenca">Licença</a></li>
</ul>


<hr/>
<!-- Sobre o projeto -->
<h2 id="sobre">💻 Sobre o Projeto</h2>
<p align="justify">A <strong>API CMS</strong> é ...<p>


<hr/>
<!-- Funcionalidades -->
<h2 id="funcionalidades">⚙️ Funcionalidades</h2>

### Features:
- [x] Controllers
  - [x] CarrosselMultimidia
  - [x] Documento
  - [x] LojaAplicativo
  - [x] Produto
  - [x] Promocao
  - [x] RedeSocial
  - [x] ServicoAtendimento
- [x] DTOs
  - [x] CarrosselMultimidia
  - [x] Documento
  - [x] LojaAplicativo
  - [x] Produto
  - [x] Promocao
  - [x] RedeSocial
  - [x] ServicoAtendimento
- [x] Mappings
  - [x] AutoMapperProvider
  - [x] CarrosselMultimidiaProfile
  - [x] DocumentoProfile
  - [x] LojaAplicativoProfile
  - [x] ProdutoProfile
  - [x] PromocaoProfile
  - [x] RedeSocialProfile
  - [x] ServicoAtendimentoProfile




<hr/>
<!-- Demonstração da Aplicação -->
<h2 id="demoApl">🎨 Demonstração da Aplicação</h2>

Para acessar a aplicação, clique [aqui](https://www.banesecard.com.br/CMS/api).
<!-- [ADICIONAR LINK QUANDO A API ESTIVER DISPONÍVEL] -->

<!-- ![alt](./Home.png) -->
**Tabela Rede Social:**
Tem o objetivo de armazenar as redes sociais que estarão disponíveis na nova Landing Page.

**Tabela Conteúdo Multimídia:**
Tem o objetivo de salvar os arquivos referentes ao produto (salvar documentos).

**Tabela Produto:**
Tem como objetivo salvar os cartões e seus respectivos atributos.

**Serviço Atendimento:**
É referente a área de contatos no final do site.

**Sessões:**
É referente aos tópicos da Landing Page.




<hr/>
<!-- Pré-requisitos -->
<h2 id="preRequisitos">👉 Pré-requisitos</h2>

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
* [Git](https://git-scm.com)
* [Visual Studio 2019](https://visualstudio.microsoft.com/pt-br/vs/) <!-- [TALVEZ SEJA NECESSÁRIO INFORMAR OS COMPONENTES] -->

Baixe o Repositório.

```bash
# Crie uma pasta onde deverá ficar o projeto (recomenda-se cria na unidade C: com o nome Git)

# Abra o Terminal (Windows+R > digite cmd > OK)

# Entre na pasta Git
$ cd ../..
$ cd Git

# Clone este repositório
$ git clone https://repositorios.banese.com.br/Seac/ssc-api-gerenciamento-conteudo.git
```

Além disto, será necessário a instalação de alguns pacotes no Visual Studio: <!-- [VERIFICAR QUAIS REALMENTE SÃO NECESSÁRIOS] -->

1. NLog
2. AutoMapper
3. NLog.Web.AspNetCore
4. Swashbuckle.AspNetCore
5. Seac.Corporativo.Logging

    Para a instalação desse pacote, será necessário configurar o Nexus (Tools > NuGet Package Manager > Package Manager Settings > NuGet Package Manager > Package Sources > Adicione um pacote, com Name "Nexus" e Source "https://bibliotecas.banese.com.br/repository/nuget-all/").
6. NLog.Targets.ElasticSearch
7. Microsoft.AspNetCore.Server.IISIntegration
8. Microsoft.AspNetCore.Mvc.NewtonsoftJson

Obs: Opte sempre pela versão mais atual.






<hr/>
<!-- Tecnologias Utilizadas -->
<h2 id="tecUtilizadas">🛠 Tecnologias Utilizadas</h2>

As seguintes ferramentas foram usadas na construção do projeto: <!-- [ADICIONAR/REMOVER CASO SEJA NECESSÁRIO] -->

- [C#](https://docs.microsoft.com/en-us/dotnet/csharp/)
- [IIS](https://www.iis.net/)
- [.NET](https://dotnet.microsoft.com/)
- [JSON](https://www.json.org/json-en.html)
- [Swagger](https://swagger.io/)
- [ASP.NET](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-3.1)
- [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)
- [Entity Framework](https://docs.microsoft.com/en-us/ef/)
- [Dependency Injection](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-3.1)


<hr/>
<!-- Canais Digitais -->
<h2 id="canaisDigitais">Canais Digitais</h2>

<h3><i>WEB</i></h3>

| NOME | URL |
| ------ | ------ |
| Landing Page | https://www.banesecard.com.br/ |
| Portal Cliente | https://www.banesecard.com.br/PortalCliente/ |
| Portal TKS | https://www.usetks.com.br/PortalLojista/Login/ |
| Portal Terceiros | https://www.banesecard.com.br/PortalTerceiros/ |

<h3><i>APPs Nativos</i></h3>

| NOME | URL |
| ------ | ------ |
| App BaneseCard | API: [Portal Cliente][api_pc] |
| APP Lojista | API: [Portal Lojista][api_pl] |

<h3><i>APPs Híbridos (React-Native)</i></h3>

| NOME | URL |
| ------ | ------ |
| App Voucher | API: [Portal Benefícios][api_pb] |
| App Metas | API: [Portal Assistente][api_pa] |
| App TKS Pay | (Ainda está em desenvolvimento) |

[api_pc]:https://www.banesecard.com.br/PortalCliente/api ""
[api_pl]:https://www.usetks.com.br/PortalLojista/api ""
[api_pb]:https://www.banesecard.com.br/portalbeneficios/api ""
[api_pa]:https://www.banesecard.com.br/PortalAssistente/api ""


<hr/>
<!-- Licença -->
<h2 id="licenca">📝 Licença</h2>
<small><i>© Copyright 2020. Sergipe Administradora de Cartões e Serviços Ltda - SEAC | Todos os direitos reservados.</i>
</small>