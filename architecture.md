# Architecture Overview

User → GitHub → GitHub Actions → Docker Build → Application

## Flow:
1. Developer pushes code
2. GitHub Actions triggers pipeline
3. Docker image builds
4. Application runs in container
