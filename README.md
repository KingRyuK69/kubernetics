# Cosmocloud-Deploy Helm Chart

This Helm Chart deploys the following applications:
1. Backend (shreybatra/sample-backend)
2. Frontend (shreybatra/sample-frontend)
3. Redis Database (redis)

### Usage
Deploy the application stack using:
```bash
helm install testapp cosmocloud-deploy --atomic --timeout 30s
