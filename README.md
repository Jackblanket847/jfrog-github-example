# JFrog GitHub Actions Integration Example

This repository demonstrates how to integrate GitHub Actions with JFrog Artifactory using OpenID Connect (OIDC) for secure authentication. The workflow automates building, publishing, and scanning artifacts.

## Prerequisites

- [GitHub account](jackblanket847/jfrog-github-example/index.html)
- JFrog Artifactory account with OIDC configured
- Necessary secrets set in GitHub repository settings

## Workflow Overview

1. Checkout the repository
2. Set up JFrog CLI
3. Configure JFrog CLI with OIDC
4. Build the project
5. Publish artifacts to Artifactory
6. Scan artifacts using JFrog Xray

## Repository Structure

- `.github/workflows/build-publish.yml`: GitHub Actions workflow file
- `src/`: Source code directory
- `docs/`: Documentation files
- `config/`: Configuration files
