# ToDo

Início de uma aplicação de lista de tarefas em Angular.

> 📦 **Projeto de estudo** — não recebe mais atualizações.

## Contexto

Criado em outubro de 2023. A ideia original era um app Angular (com Angular Material e SCSS) integrado a um backend Spring Boot com banco SQL Server, mas o repositório contém **apenas o frontend recém-gerado** pelo Angular CLI: a tela ainda é o modelo padrão e não há backend nem banco de dados aqui.

## Tecnologias

- **Angular 16** (Angular CLI 16.2) — framework do frontend.
- **Angular Material / CDK** — biblioteca de componentes visuais (instalada, ainda não usada).
- **SCSS** — estilos.
- **Karma + Jasmine** — testes padrão do Angular CLI.

## Como rodar

Pré-requisito: Node.js (versão LTS) e npm.

```bash
cd to-do
npm install
npm start
```

O app abre em <http://localhost:4200>. Outros scripts: `npm run build` e `npm test`.

## Estrutura

- `to-do/` — projeto Angular (o `README.md` interno é o gerado pelo Angular CLI).
- `to-do/src/app/` — módulo e componente principal.
