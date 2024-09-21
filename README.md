# Windows Compute Engine Deployment

This repository contains a Cloud Build pipeline (`cloudbuild.yaml`) that automates the deployment of a Windows Compute Engine instance with the following specifications:

- **Operating System**: Windows Server 2019
- **Machine Type**: n1-standard-2 (2 vCPUs, 7.5 GB memory)
- **Boot Disk**: 50GB Standard HDD
- **Admin User**: `admin_user`
- **Admin Password**: `AdminPassword123!`

## Steps to Deploy

1. **Create a Google Cloud Project** and ensure you have the required permissions to create Compute Engine instances.
2. **Enable the Compute Engine API** in your project:
   ```bash
   gcloud services enable compute.googleapis.com

