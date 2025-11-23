Trying GCP Cloud Build and Artifact Registry

```
curl -sS https://webi.sh/gh | sh

gcloud builds submit --tag us-east4-docker.pkg.dev/$DEVSHELL_PROJECT_ID/devops-repo/devops-image:v0.1 .
```