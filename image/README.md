# Coder DDEV Base Image

This Docker image is the base image for Coder Drupal DDEV workspaces. It contains:
- Ubuntu 24.04 LTS
- curl and wget (required for Coder agent download)
- coder user (UID 1000) with passwordless sudo for package installation
