# GCP Cloud Build Exercises

This repository contains configurations for deploying a Google Cloud Compute Engine instance using Google Cloud Build.

## Overview

This project sets up a Compute Engine instance with the following specifications:

- **Operating System**: Windows Server 2022
- **Machine Type**: n1-standard-2 (2 vCPUs and 7.5 GB of memory)
- **Disk Type**: Standard HDD (50 GB)
- **Admin Username**: `testgcpnow`
- **Admin Password**: `&JRSNRnm,yq8jM5`

## Cloud Build Configuration

The project uses a `cloudbuild.yaml` file to automate the deployment of the Compute Engine instance. The configuration performs the following steps:

1. **Create Compute Engine Instance**: Deploys a Windows Server instance with the specified machine type and disk.
2. **Set Admin Username and Password**: Configures the admin user and password for accessing the Windows instance.

## Requirements

- Google Cloud Platform account
- Google Cloud SDK installed
- Access to Cloud Build and Compute Engine APIs

## Instructions to Deploy

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/GCP_CloudBuild_Exercises.git
   cd GCP_CloudBuild_Exercises
