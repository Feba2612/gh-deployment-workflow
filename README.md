# GitHub Actions Deployment Workflow

Este projeto faz parte do roadmap de DevOps do [roadmap.sh](https://roadmap.sh/projects/github-actions-deployment-workflow).

Este projeto demonstra um workflow simples do GitHub Actions que implanta um site estático no GitHub Pages sempre que o arquivo `index.html` é alterado.

## Estrutura do Projeto

- `index.html`: O arquivo HTML principal com o conteúdo "Hello, GitHub Actions!"
- `.github/workflows/deploy.yml`: O arquivo de workflow do GitHub Actions que gerencia a implantação.
- `README.md`: Este arquivo, explicando o projeto.
- `styles.css`: Arquivo CSS opcional para estilos (separado para melhor organização).

## Como Funciona

1. Quando você faz push de mudanças para a branch `main` que modificam `index.html`, o workflow é acionado.
2. O workflow usa as ações integradas do GitHub Pages para fazer upload dos arquivos do site.
3. O site fica disponível em `https://<seu-usuario>.github.io/gh-deployment-workflow/`.

## Requisitos

- Repositório no GitHub chamado `gh-deployment-workflow`
- Arquivo `index.html` simples
- Workflow `deploy.yml` em `.github/workflows/`
- Implantação acionada apenas em mudanças no `index.html`

## Metas de Expansão

Você pode aprimorar isso usando um gerador de sites estáticos como Hugo, Jekyll ou Astro para criar um site mais complexo, como um portfólio pessoal.

Este projeto ajuda a aprender sobre CI/CD, GitHub Actions e GitHub Pages.

