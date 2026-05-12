# Python Foundry Frontend

Angular UI for the Python Foundry codegen API. Production image is built via CI and deployed through the Paxo GitOps repo (`k8/python-frontend-deployment.yaml`).

## Local development

```bash
npm ci
npm start
```

Configure API routing via `proxy.conf.json` for local use.
