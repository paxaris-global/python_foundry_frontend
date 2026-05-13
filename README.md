# Python Foundry Frontend

Angular UI for the Python Foundry codegen API. Production image is built via CI and deployed through the Paxo GitOps repo (`k8/python-frontend-deployment.yaml`).

## Local development

```bash
npm ci
npm start
```

The dev server uses `http://localhost:4201` to avoid colliding with Paxo's main frontend on `4200`. Configure API routing via `proxy.conf.json` for local use.
