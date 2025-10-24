# Projeto CI/CD - Repositório de Manifestos

Este repositório armazena os manifestos Kubernetes (`deployment.yaml`, `service.yaml`) para a aplicação `hello-app`.

Ele serve como a **fonte da verdade (source of truth)** para o [ArgoCD](https://argo-cd.readthedocs.io/en/stable/), que monitora este repositório e aplica quaisquer mudanças ao cluster Kubernetes.

## ⚠️ Atenção: Repositório Gerenciado Automaticamente

O conteúdo deste repositório, especificamente a *tag da imagem* no arquivo `deployment.yaml`, é gerenciado automaticamente por uma pipeline de CI/CD do GitHub Actions.

A pipeline está localizada no repositório principal da aplicação.

**Qualquer alteração manual na tag da imagem será sobrescrita no próximo `push` para a aplicação.**

### Repositório Principal

Para ver o código-fonte da aplicação, o `Dockerfile` e o workflow do GitHub Actions, acesse o repositório principal:

**[Link para seu repositório `hello-app`]**
*(Substitua este link pelo URL do seu repositório `hello-app`)*
