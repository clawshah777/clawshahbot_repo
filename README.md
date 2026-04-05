# clawshahbot_repo

Starter scaffold for ClawShahBot apps and deployments. This repo includes a simple static site and a GitHub Actions workflow that can deploy to your VPS via SSH.

How to use:
1. Add repository to GitHub (you already created it).
2. Add the deploy private key as a repository secret named `DEPLOY_PRIVATE_KEY`.
3. Update the workflow `deploy.yml` with your VPS user and host.
4. Push to the repo; Actions will deploy to your VPS.
