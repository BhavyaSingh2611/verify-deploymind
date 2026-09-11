# Verify Hello

DeployMind verification fixture. It verifies injected identity, secrets, and the per-app Postgres connection.

Publish this directory to a public GitHub repository, then run the platform dogfood test with:

```sh
REPO_URL=https://github.com/<owner>/<repo> make e2e-public-repo
```
