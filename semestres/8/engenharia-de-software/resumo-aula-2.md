# Histórico da Engenharia de Software e Ciclo de Vida do Software — Resumo

## Histórico da Engenharia de Software
- **Definição:** aplicação de princípios de engenharia ao desenvolvimento, operação e manutenção de software.
- **Origem (1960s):** aumento da complexidade e a chamada **“crise do software”** impulsionaram métodos estruturados, processos formais e práticas de qualidade.
- **Motivação:** reduzir falhas, atrasos e estouros de orçamento; aumentar previsibilidade, qualidade e manutenção.

## Fases da Evolução da Engenharia de Software
- **1960s:** crise do software; projetos grandes e sistemas de tempo real expõem limitações.
- **1970s:** métodos estruturados; documentação forte; modelo cascata populariza-se.
- **1980s:** qualidade de software, métricas e normas; design orientado a abstrações.
- **1990s:** processos **iterativos** e incrementais; prototipação; gestão de risco.
- **2000s+:** **metodologias ágeis**; entregas frequentes; foco em valor; integração/entrega contínuas.

## Problemas enfrentados
- **Escopo e requisitos:** ambíguos, mutantes ou pouco priorizados; *scope creep*.
- **Prazo e custo:** estimativas ruins; dependências subestimadas; retrabalho.
- **Qualidade:** testes tardios/insuficientes; falta de automação; débitos técnicos.
- **Processo e comunicação:** silos; feedback lento; documentação desatualizada.

## Ciclo de Vida de Software — Definição
- **Conjunto de fases** que regem o desenvolvimento, implantação, operação e manutenção.
- **Objetivos:** organizar o trabalho, reduzir riscos, dar rastreabilidade, facilitar governança e melhoria contínua.

## Modelo Cascata — Definição e Etapas
- **Definição:** sequência linear de fases com pouca sobreposição.
- **Etapas típicas:** levantamento de requisitos → análise e design → implementação → testes/validação → implantação → manutenção.
- **Vantagens:** simplicidade, forte documentação, adequação a ambientes regulados e requisitos estáveis.
- **Desvantagens:** pouca flexibilidade a mudanças; feedback e testes chegam tarde; risco de descobrir problemas ao final.
- **Quando usar:** projetos com escopo claro e estável; alta conformidade/regulação; contratos fixos.

## Modelo Iterativo — Definição e Características
- **Definição:** desenvolvimento em ciclos curtos com **entregas parciais**, incorporando feedback e **refinando requisitos** ao longo do tempo.
- **Características:** aprendizado progressivo; gerenciamento de risco por iteração; validação contínua com stakeholders.
- **Vantagens:** adaptação a incerteza; redução de risco; aumento de envolvimento do usuário.
- **Desvantagens:** coordenação mais complexa; pode exigir maturidade de gestão e integração.
- **Quando usar:** requisitos em evolução; necessidade de validar hipóteses ou usabilidade com usuários.

## Modelo Ágil — Definição e Princípios
- **Definição:** abordagem incremental/adaptativa orientada a entregar **valor de negócio** frequentemente.
- **Princípios (síntese do Manifesto Ágil):**
  - Pessoas e interações mais que processos e ferramentas.
  - Software em funcionamento mais que documentação abrangente.
  - Colaboração com o cliente mais que negociação de contratos.
  - Responder a mudanças mais que seguir um plano.
- **Práticas comuns:** backlog priorizado, time-boxing (sprints), planejamento adaptativo, *daily meetings*, retrospectivas, integração/entrega contínuas.
- **Quando usar:** ambientes dinâmicos; necessidade de rapidez e aprendizado contínuo; foco em valor e redução de desperdício.

## Comparação entre os modelos
| Modelo    | Vantagens                           | Desvantagens                             | Uso típico                           |
|-----------|-------------------------------------|------------------------------------------|--------------------------------------|
| Cascata   | Simplicidade, documentação forte    | Rigidez; teste/feedback tardios          | Escopo estável e regulado            |
| Iterativo | Feedback e aprendizado contínuos    | Gestão/coordenação mais complexas        | Requisitos incertos/em evolução      |
| Ágil      | Flexibilidade; time-to-market       | Exige disciplina/maturidade do time      | Mudanças frequentes; valor contínuo  |

## Quando utilizar cada modelo?
- **Cascata:** requisitos **claros e estáveis**; compliance; contratos rígidos.
- **Iterativo:** **incerteza moderada/alta**; descoberta de requisitos por protótipos.
- **Ágil:** **mudanças frequentes**; necessidade de priorizar valor e reduzir *lead time*.

## Análise de sucesso e fracasso — Fatores críticos
- **Sucesso:** visão e escopo claros; patrocínio executivo; comunicação efetiva; gestão ativa de riscos e mudanças; testes e automação; boas práticas de engenharia (CI/CD, revisão de código).
- **Fracasso:** requisitos vagos; falta de priorização; atrasos sem gestão; integração tardia; baixa qualidade; ausência de métricas e feedback.

## Exemplos de sucesso e fracasso
- **Sucesso:**
  - **Spotify:** organização em *squads/tribes*; autonomia; foco em valor e experimentação.
  - **Amazon (práticas internas):** ciclos pequenos; métricas; entrega contínua e foco no cliente.
- **Fracasso:**
  - **Healthcare.gov (2013):** requisitos e coordenação deficientes; testes/integração inadequados.
  - **Windows Vista (2007):** complexidade e compatibilidade; mudanças tardias; percepção de baixo valor.
*(Exemplos usados para fins didáticos.)*

## Lições aprendidas
- **Envolvimento do usuário** desde o início; ciclos curtos com **inspeção e adaptação**.
- **Automatizar** integração, testes e deploy; reduzir retrabalho e tempos de *handoff*.
- **Métricas de fluxo e qualidade** (lead time, *cycle time*, taxa de defeitos, *deployment frequency*, *change failure rate*).
- **Arquitetura evolutiva** e boa observabilidade; dívida técnica sob controle.

## Importância da escolha do modelo correto
- Afeta **qualidade**, **custo**, **prazo** e **risco**.
- O **contexto** (regulação, estabilidade do escopo, urgência, maturidade do time) deve guiar a escolha — e ela **pode mudar** à medida que se aprende.

## Ferramentas de gestão 
- **Jira:** gestão de backlog, sprints, quadros Kanban/Scrum, *dashboards* e métricas.
- **Trello:** quadros visuais simples; listas e cartões; bom para equipes pequenas ou fluxos leves.
- **Azure DevOps:** suíte integrada (Boards, Repos, Pipelines, Test Plans) — do planejamento ao CI/CD.

## Boas práticas na implementação
- **Gerenciar escopo e priorização** com critérios de valor (ex.: WSJF, MoSCoW).
- **Definições claras** (DoR/DoD), *branching* e *code review*.
- **Integração contínua** e **testes automatizados** (pirâmide de testes).
- **Entregas frequentes** e *feature flags* para reduzir risco.
- **Retrospectivas** e melhoria contínua orientadas por métricas e evidências.

## Papel do Product Owner
- **Maximiza valor**: traduz objetivos de negócio em um **backlog priorizado**.
- **Tria e refina requisitos**; aceita/valida incrementos.
- **Conecta stakeholders e time**; decide trade-offs de escopo, prazo e valor.

## Conclusão — Ciclo de vida e sucesso do projeto
- **Combinação certa de modelo + práticas de engenharia + gestão por métricas** eleva previsibilidade e valor entregue.
- **Ciclos curtos com feedback real** e **automação** reduzem risco e aumentam qualidade.
- **Adaptação ao contexto** é central: não há “modelo único” — há **escolhas informadas** ao longo do ciclo de vida.

---

## Referências
- **Manifesto for Agile Software Development** — [Valores](https://agilemanifesto.org/) · [Princípios](https://agilemanifesto.org/principles.html)
- **ISO/IEC/IEEE 12207:2017 — Software Life Cycle Processes** — [Página oficial ISO](https://www.iso.org/standard/63712.html) · [Página IEEE](https://standards.ieee.org/ieee/12207/5672/)
- **Royce, W. W. (1970).** *Managing the Development of Large Software Systems* — [PDF](https://www.praxisframework.org/files/royce1970.pdf)
- **Boehm, B. (1988).** *A Spiral Model of Software Development and Enhancement* — [PDF](https://www.cse.msu.edu/~cse435/Homework/HW3/boehm.pdf)
- **The Scrum Guide (2020).** Ken Schwaber & Jeff Sutherland — [Site oficial](https://scrumguides.org/) · [PDF](https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-US.pdf)
- **Jira Software — Guia de início** — [Atlassian (guia introdutório)](https://www.atlassian.com/software/jira/guides/getting-started/introduction)
- **Trello 101 — Boards, Lists & Cards** — [Guia oficial](https://trello.com/guide/trello-101)
- **Azure DevOps — Visão geral** — [Documentação Microsoft Learn](https://learn.microsoft.com/en-us/azure/devops/user-guide/what-is-azure-devops?view=azure-devops)