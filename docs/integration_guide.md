# Integration Guide

This document provides a step-by-step guide to integrating GitHub Actions with JFrog Artifactory using OIDC.

## Steps

1. **Configure OIDC in JFrog Artifactory**: Set up OIDC integration in your JFrog Artifactory instance.

2. **Set GitHub Secrets**: In your GitHub repository, set the following secrets:
   - `JF_URL`: Your JFrog Artifactory URL
   - `JF_REPO`: Target repository in Artifactory

3. **Customize Workflow**: Modify `.github/workflows/build-publish.yml` as needed for your project.

4. **Run Workflow**: Push changes to trigger the GitHub Actions workflow.
