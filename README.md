# Gerenciador de Tarefas (React + Vite)

Este repositório contém uma aplicação simples de gerenciamento de tarefas construída com React + Vite e estilizada com Tailwind CSS.

## Tecnologias

- React
- Vite
- Tailwind CSS
- lucide-react (ícones)

## Pré-requisitos

- Node.js (v16+ recomendado)
- npm ou yarn

## Instalação

1. Instale dependências:

```bash
npm install
# ou
# yarn install
```

## Executar em desenvolvimento

```bash
npm run dev
# ou
# yarn dev
```

Abra o endereço mostrado no terminal (por padrão http://localhost:5173).

## Build para produção

```bash
npm run build
# ou
# yarn build
```

## Estrutura principal do projeto

- `src/` - código fonte
  - `components/` - componentes reutilizáveis (AddTask, Tasks, Button, Input, Title)
  - `pages/` - páginas (ex: TaskPage)
  - `App.jsx` - componente raiz

## Como usar a aplicação

- Adicionar tarefa: use o formulário para informar título e descrição.
- Marcar como concluída: clique no botão principal da tarefa (o texto ficará com linha-through).
- Excluir tarefa: clique no ícone de lixeira ao lado da tarefa.

As tarefas são salvas no `localStorage` do navegador, então persistem entre atualizações locais.

## Observações

- O projeto é uma boa base para estudar React com Vite e Tailwind. Sinta-se à vontade para adicionar testes, autenticação ou persistência remota.

## Contribuição

Pull requests são bem-vindos. Para mudanças maiores abra uma issue primeiro para discutirmos a proposta.

## Licença

Licença padrão — ajuste conforme necessário.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
