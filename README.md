# Next.js Login Page com Cypress

Este repositório contém uma simples aplicação de página de login desenvolvida com Next.js e testada utilizando Cypress. O projeto foi criado com fins educacionais para demonstrar a implementação e execução de testes end-to-end com Cypress em uma aplicação React moderna.

![Cypress Tests](https://img.shields.io/badge/cypress-tests-brightgreen.svg)
![Next.js](https://img.shields.io/badge/Next.js-v15-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## 📋 Sobre o Projeto

Esta aplicação consiste em uma simples página de login que inclui:

- Formulário de login com validação de campos
- Feedback visual para diferentes estados (carregando, erro, sucesso)

Os testes Cypress cobrem todos os fluxos principais e cenários de borda da funcionalidade de login.

## 🚀 Tecnologias Utilizadas

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Cypress](https://www.cypress.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)



## 🏁 Como Iniciar

### Pré-requisitos

- Node.js (versão 16 ou superior)
- npm, yarn ou pnpm

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/PedroAugSouza/form-cypress.git
   cd nextjs-cypress-login
   ```

2. Instale as dependências:
   ```bash
   npm install
   # ou
   yarn
   # ou
   pnpm install
   ```

3. Execute a aplicação:
   ```bash
   npm run dev
   # ou
   yarn dev
   # ou
   pnpm dev
   ```

A aplicação estará disponível em [http://localhost:3000](http://localhost:3000).

## 🧪 Executando os Testes

### Modo de Interface Gráfica

Para abrir o Cypress em modo gráfico:

```bash
npm run cypress open
# ou
yarn cypress open
# ou
pnpm cypress open
```

### Modo Headless

Para executar os testes em modo headless (CI/CD):

```bash
npm run cypress run
# ou
yarn cypress run
# ou
pnpm cypress run
```


## 📚 Recursos Adicionais

- [Documentação do Cypress](https://docs.cypress.io/)
- [Documentação do Next.js](https://nextjs.org/docs)
- [Padrões de teste recomendados](https://docs.cypress.io/guides/references/best-practices)

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir um Pull Request ou uma Issue.

1. Faça um fork do projeto
2. Crie sua branch de feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request
