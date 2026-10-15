# Passos para a Questão 7

1. Copie a pasta `.github` deste projeto para a raiz do seu repositório GitHub.
2. No GitHub, abra o repositório.
3. Vá em **Settings → Secrets and variables → Actions**.
4. Crie:
   - `DOCKERHUB_USERNAME` com valor `gabriel1751`
   - `DOCKERHUB_TOKEN` com o valor do seu token Docker Hub
5. Não coloque o token em nenhum arquivo.
6. Garanta que existe um `Dockerfile` válido na raiz do repositório.
7. Faça:

```powershell
git add .
git commit -m "Adiciona workflow Docker Build and Push"
git push
```

8. Abra a aba **Actions** no GitHub e verifique se o workflow `Docker Build and Push` ficou verde.
9. Depois envie o resultado para completar o arquivo `07-primeiro-workflow.md`.

Badge:

```markdown
![Docker Build and Push](https://github.com/SEU_GITHUB_USERNAME/SEU_REPOSITORIO/actions/workflows/docker-build-push.yml/badge.svg)
```
