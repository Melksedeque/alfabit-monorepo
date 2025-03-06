# Projeto Alfabit Monorepo - React - Design System

![Tela Principal](./screenshot/tela-principal.png)

## Menu

- [Layout](#layout)
- [Descrição](#descrição)
  - [Principais recursos incluem](#principais-recursos-incluem)
  - [Proximos passos de desenvolvimento](#proximos-passos-de-desenvolvimento)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura de Pastas](#estrutura-de-pastas)
  - [Arquivos Principais](#arquivos-principais)
- [Como Instalar e Rodar o Projeto](#como-instalar-e-rodar-o-projeto)
  - [Configuração](#configuração)
  - [Casos de Uso Comuns](#casos-de-uso-comuns)
  - [Solução de Problemas](#solução-de-problemas)
- [Projeto ao Vivo](#projeto-ao-vivo)
- [Fluxo de Dados](#fluxo-de-dados)
- [Licença](#licença)
- [Autor](#autor)

## Layout

[Layout no Figma](<https://www.figma.com/design/77vXUhArXMYOiuuRUbYqVf/React%3A-Turborepo%2C-componentes-e-storybook-%7C-Alfabit-(Community)?node-id=0-1&p=f&t=oSFvHSNnn9XKni4z-0>)

## Descrição

### Principais recursos incluem:

- Componentes do Design System (Button, Input, TextBlock)
- Suporte a temas personalizáveis (light, dark e custom)
- Documentação interativa com Storybook
- Estrutura de monorepo usando Turborepo
- Pacotes independentes e reutilizáveis
- Demo app usando Remix.js

## Tecnologias Utilizadas

- React
- TypeScript
- Styled Components
- Turborepo
- pnpm (Package Manager)
- Storybook
- Remix.js
- Tailwind CSS

## Estrutura de Pastas

```
.
├── apps/
│   ├── alfabit-demo/    # Aplicação demo em Remix.js
│   └── docs/            # Documentação Storybook
├── packages/
│   ├── alfabit-button/      # Componente Button
│   ├── alfabit-input/       # Componente Input
│   ├── alfabit-textblock/   # Componente TextBlock
│   ├── alfabit-tokens/      # Design tokens
│   └── component-template/  # Template para novos componentes
└── scripts/
    └── create-component.js  # Script para criar novos componentes
```

### Arquivos Principais:

## Como Instalar e Rodar o Projeto

1. Clone o repositório
2. Instale as dependências:

```bash
pnpm install
```

3. Para desenvolvimento:

```bash
pnpm dev
```

4. Para build:

```bash
pnpm build
```

### Configuração

### Casos de Uso Comuns

### Solução de Problemas

## Projeto ao Vivo

## Fluxo de Dados

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](https://github.com/Melksedeque/alfabit-monorepo?tab=MIT-1-ov-file) para mais detalhes.

## Autor

- GitHub - [Melksedeque Silva](https://github.com/Melksedeque/)
- FrontEndMentor - [@Melksedeque](https://www.frontendmentor.io/profile/Melksedeque)
- Twitter / X - [@SouzaMelk](https://x.com/SouzaMelk)
- LinkedIn - [Melksedeque Silva](https://www.linkedin.com/in/melksedeque-silva/)
