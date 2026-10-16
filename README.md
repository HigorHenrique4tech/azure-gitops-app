# azure-gitops-app

Aplicação de exemplo (`api` e `web`) com Dockerfiles e o pipeline de CI que builda, escaneia, assina e publica as imagens no ACR.

Parte do projeto [projeto-gitops](https://github.com/HigorHenrique4tech/projeto-gitops), junto com `azure-gitops-infra` e `azure-gitops-config`.

> Projeto de laboratório e portfólio. Em construção.

## Desenvolvimento

```bash
pre-commit install   # instala os hooks de pre-commit e commit-msg
pre-commit run --all-files
```

Commits seguem [Conventional Commits](https://www.conventionalcommits.org/) e são assinados com chave SSH.
