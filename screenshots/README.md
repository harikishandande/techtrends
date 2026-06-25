# Required Screenshots Checklist

Place the following screenshots in THIS folder. Use the EXACT file names below
(any common image extension is fine, e.g. .png). These are graded by the rubric.

| # | File name                              | Step | What it must show                                                                 |
|---|----------------------------------------|------|-----------------------------------------------------------------------------------|
| 1 | docker-run-local                       |  2   | App in the browser at http://127.0.0.1:7111, INCLUDING the navigation bar          |
| 2 | ci-github-actions                      |  3   | GitHub Actions tab with a SUCCESSFUL "TechTrends - Package with Docker" run        |
| 3 | ci-dockerhub                           |  3   | DockerHub repository page showing the techtrends image with the `latest` tag       |
| 4 | k8s-nodes                              |  4   | Output of `kubectl get no` (node Ready)                                            |
| 5 | kubernetes-declarative-manifests       |  4   | Output of `kubectl get all -n sandbox` (deployment, pod, service all running)      |
| 6 | argocd-ui                              |  6   | ArgoCD UI after login, INCLUDING the navigation bar                                |
| 7 | argocd-techtrends-staging              |  6   | techtrends-staging Application in ArgoCD, fully Synced & Healthy                   |
| 8 | argocd-techtrends-prod                 |  6   | techtrends-prod Application in ArgoCD, fully Synced & Healthy                      |

Total: 8 screenshots required by the rubric.
