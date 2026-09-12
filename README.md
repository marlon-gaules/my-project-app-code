# my-project-app-code
Source code, unit tests, and CI pipeline (GitHub Actions) for the end-to-end GitOps platform project.

# 📦 App Code & CI Pipeline

Este repositório contém o código-fonte da aplicação, a suíte de testes unitários e a automação de CI.

## 🔄 Fluxo de CI (GitHub Actions)
1. **Lint & Testes:** Executa a suíte de testes a cada push.
2. **Build & Push:** Gera a imagem Docker e envia para o Docker Hub.
3. **GitOps Trigger:** Atualiza a tag da imagem no repositório de infraestrutura [`my-project-gitops-manifests`](link-do-seu-outro-repo).
