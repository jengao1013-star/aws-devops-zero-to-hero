1. What is CI/CD?

Continuous Integration automatically builds and tests code on every change. Continuous Delivery/Deployment automatically releases it to environments.

2. What is the difference between continuous delivery and continuous deployment?

Delivery requires a manual approval before production. Deployment releases to production automatically after tests pass.

3. What is a pipeline?

A pipeline is an automated sequence of stages such as build, test, scan, package, and deploy.

4. What are common CI/CD tools?

Jenkins, GitHub Actions, GitLab CI, CircleCI, Azure DevOps, and Argo CD.

5. What is a Jenkinsfile?

It is a file that defines a Jenkins pipeline as code, stored in the repository.

6. What are build artifacts?

They are the outputs of a build, such as JAR files, Docker images, or packages, stored in a registry or artifact repository.

7. What is a blue-green deployment?

Two identical environments run side by side. You deploy to the idle one and switch traffic over, which allows instant rollback.

8. What is a canary deployment?

A new version is released to a small percentage of users first, then gradually increased if it is healthy.

9. What is a rolling deployment?

Instances are updated in small batches so the application stays available during the release.

10. How do you handle secrets in pipelines?

Use the CI tool’s secret store or a vault (such as HashiCorp Vault or AWS Secrets Manager) and never commit secrets to the repository.