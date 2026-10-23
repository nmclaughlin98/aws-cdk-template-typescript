# AWS CDK TypeScript Template Repository

This repository is a GitHub template for creating AWS CDK applications in TypeScript with a Node.js Lambda example.

## Create a project

1. Select **Use this template** and create a new repository.
2. Keep the new repository's default branch named `main`.
3. Push to `main` to run the initialization workflow.

The workflow replaces `TEMPLATE_REPO_NAME` and `TEMPLATE_OWNER` in the staged project, promotes all files—including hidden files—from `template/` to the repository root, and removes the staging directory and this meta README. It commits the initialized project to `main`, then removes itself in a second commit.

The workflow intentionally skips this source repository: `nmclaughlin98/aws-cdk-template-typescript`.

## Staged project

The complete CDK project boilerplate is in [`template/`](./template/). It includes the CDK stack, Node.js 24 Lambda handler, tests, package configuration, project documentation, and build/deploy workflows. After initialization, its own README and setup instructions are at the repository root.

If the generated repository protects `main`, allow GitHub Actions to push to that branch before the first push, or the initializer will be unable to promote the project files.
