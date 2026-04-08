# Oi, muito prazer, sou o Pedro :)

- Enhgenheiro de Software Fullstack
- Especialista em integrações com Qlik Sense
- Pós Graduação em Engenaria de Software em andamento na PUC-MG

## Frontend

- Core: React | TypeScript | Next.js | TailwindCSS | HTML | CSS
- Dataviz: echarts
- State Management: Context API, Tanstack Query | Zustand
- Testing: Vitest | React Testing Library
- Tooling/Bundling: Vite | Webpack
- Misc: Microfrontends | SPAs | PWAs | REST APIs | Storybook | Figma

## Backend

- Core: Node.js | Express.js | NestJS
- Databases: PostgreSQL, MongoDB, MySQL
- Misc: Docker | GitHub Actions | REST APIs

## Projetos pessoais em destaque

### [QS App Analyzer Toolkit](https://github.com/pperdigo/qlik-app-analyzer)

Tenho muito orgulho dessa aplicação, pois desenvolvi ela para resolver um problema real meu em um trabalho antigo: eu precisava analisar minunciosamente o script de carga de dados e expressões de medidas e dimensões de mais de 20 aplicativos QVF críticos do meu cliente para identificar padrões que precisavam ser atualizados

O problema: A única forma que a equipe conhecia de fazer isso era manualmente investigar o aplicativo, o que levaria muito tempo e estaria sujeito a erro humano. Essa aplicação resovle esse problema da seguinte forma:

- Uso das APIs expostas no browser para extrair as informações relevantes de forma simples, no formato JSON
- Uso de software workers para executar código JavaScript no console do navegador do usuário

Stack: React, JavaScript, Qlik APIs, Chrome Extension APIs

Próximos passsos:

- Implementar TypeScript
- Implementar testes com Vitest/RTL
- Exibir dados extraídos em um dashboard, em vez de apenas extrair para JSON
