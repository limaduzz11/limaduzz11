# Eduardo de Lima Paranhos

**Software Developer**  
Enterprise Systems • Backend & Integrations • Systems Architecture • Harness AI-Assisted Engineering

Atuo com desenvolvimento de software voltado ao ecossistema corporativo TOTVS Protheus 12, com foco em desenvolvimento ADVPL/TL++, arquitetura de integrações via APIs REST/SOAP, automação de processos de negócio e modelagem de consultas em Microsoft SQL Server.

Paralelamente, projeto e mantenho aplicações open source na **VANTA Labz** (com arquitetura limpa e abordagem local-first) e desenvolvo ferramentas para desenvolvedores explorando o **Model Context Protocol (MCP)**, orquestração de contexto e fluxos de engenharia assistida por agentes de IA.

---

### Core Stack & Technologies

* **ERP & Enterprise:**  
  ![TOTVS Protheus](https://img.shields.io/badge/TOTVS_Protheus_12-ED1C24?style=flat)
  ![ADVPL](https://img.shields.io/badge/ADVPL%2FTL%2B%2B-005696?style=flat)
  ![PO-UI](https://img.shields.io/badge/PO--UI-0070B8?style=flat&logo=angular&logoColor=white)
  ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)

* **Backend & Databases:**  
  ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
  ![SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=flat&logo=microsoftsqlserver&logoColor=white)
  ![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=flat&logo=postman&logoColor=white)
  ![SQLite](https://img.shields.io/badge/SQLite_WAL-003B57?style=flat&logo=sqlite&logoColor=white)
  ![JSON](https://img.shields.io/badge/JSON-000000?style=flat&logo=json&logoColor=white)

* **Languages & Multiplatform:**  
  ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
  ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
  ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
  ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

* **DevOps, AI & Tooling:**  
  ![Model Context Protocol](https://img.shields.io/badge/MCP-Model_Context_Protocol-8A2BE2?style=flat)
  ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
  ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
  ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
  ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

---

### Projetos & Engenharia de Software

#### [VANTA Reader](https://github.com/limaduzz11/vanta-reader) *(Open Source — VANTA Labz)*
Plataforma local-first de leitura digital para livros (EPUB, TXT) e quadrinhos/mangás (CBZ). PDF e CBR planejados no roadmap.  
- **Arquitetura & Engenharia:** Clean Architecture desacoplada, SQLite WAL (schema v5), gerenciamento reativo de estado e cache LRU anti-OOM.
- **Qualidade & Testes:** Suíte de testes automatizados com CI contínuo no GitHub Actions e foco em experiência offline-first.  
`Flutter` `Dart` `SQLite` `Clean Architecture` `Open Source`

#### [protheus-research](https://github.com/limaduzz11/protheus-research)
Servidor MCP (Model Context Protocol) para exploração técnica e apoio ao diagnóstico no ecossistema TOTVS Protheus. Fornece ferramentas para agentes de IA consultarem documentações públicas, sintaxes de linguagem e heurísticas de stack trace.  
`TypeScript` `Node.js` `MCP SDK` `TOTVS Protheus`

#### [nova-hub](https://github.com/limaduzz11/nova-hub)
Dashboard web operacional para telemetria em tempo real de infraestrutura local, gerenciamento de dispositivos via terminal SSH embutido (PTY), orquestração Kanban e rede privada Tailscale.  
`Node.js` `Express 5` `Vanilla JS` `SSH PTY` `Tailscale VPN` `WebSockets`

#### [nova-abme](https://github.com/limaduzz11/nova-abme) — [*Live*](https://nova-abme.pages.dev/)
Gateway estático de engenharia e portfólio profissional de alta performance, arquitetado com foco em resiliência, acessibilidade WCAG AAA e deploy na Cloudflare Pages.  
`Astro` `TypeScript` `Tailwind CSS` `Playwright` `Cloudflare Pages`

---

### Laboratórios Conceituais & Padrões Arquiteturais (Educacional)

> [!NOTE]
> Os repositórios abaixo são **laboratórios conceituais e guias de estudo de arquitetura**. Não se destinam a compilação autônoma nem contêm código proprietário de clientes, focando em demonstrar padrões canônicos da TOTVS (TDN), boas práticas e contratos de integração.

* [`protheus-advpl-lab`](https://github.com/limaduzz11/protheus-advpl-lab): Padrões avançados ADVPL (rotinas de `MSExecAuto MATA410` de Pedidos de Venda, transações ACID com `TCQuery`/`TCSQLExec`, auto-cadastro e relatórios).
* [`protheus-rest-lab`](https://github.com/limaduzz11/protheus-rest-lab): Padrões de consumo e exposição de APIs REST no ERP Protheus (`WSRESTFUL` nativo com `restful.ch`, cliente `FWRest`, `TCQuery` e serialização `JsonObject`).
* [`protheus-mvc-lab`](https://github.com/limaduzz11/protheus-mvc-lab): Padrões canônicos MVC Protheus com `FWMBrowse`, `ModelDef` (`MPFormModel`), `ViewDef` (`FWFormView`) e pontos de entrada de modelo.
* [`protheus-integration-lab`](https://github.com/limaduzz11/protheus-integration-lab): Padrões de integração via `FWRest`, webhooks transacionados e conciliação de pagamentos com gateways externos.
* [`protheus-po-ui-template`](https://github.com/limaduzz11/protheus-po-ui-template): Template de referência de integração entre frontend Angular + PO-UI e backend REST ADVPL.
* [`advpl-utils`](https://github.com/limaduzz11/advpl-utils): Utilitários para formatação de strings, cálculos de datas com clamp, dias úteis com calendário fiscal Protheus e exportação `TCQuery` para CSV.
* [`protheus-schedule-lab`](https://github.com/limaduzz11/protheus-schedule-lab): Padrões de processamento assíncrono via Schedule TOTVS com `SchedDef()` e execução autônoma via `RpcSetEnv`.

---

### Contato & Redes

* **LinkedIn:** [Eduardo de Lima Paranhos](https://www.linkedin.com/in/eduardo-de-lima-paranhos-910930263/)
* **Website Técnico:** [elptecnologia.com.br](https://elptecnologia.com.br/)
