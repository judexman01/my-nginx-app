argocd app create nginx-app `
  --repo https://github.com/judexman01/my-nginx-app.git `
  --path . `
  --dest-server https://kubernetes.default.svc `
  --dest-namespace default `
  --sync-policy automated
