# AWS CDK TypeScript Template Repository

This repository is a GitHub template for creating AWS CDK applications in TypeScript with a Node.js Lambda example.

## Create a project

1. Select **Use this template** and create a new repository.
2. Create a fine-grained personal access token limited to the new repository, with **Contents: Read and write** and **Workflows: Read and write** permissions. Add it to the new repository as the Actions secret `TEMPLATE_INIT_TOKEN`.
3. Add **Pull requests: Read and write** permission to the token. The initializer needs it to open the setup PR.
4. Rerun the failed **Initialise Repository from Template** workflow from the Actions tab. The initial push starts the workflow, and the initializer opens a pull request against `main`.
5. Review and merge the initialization PR. The staged project and initializer removal are both included in that PR.
6. Keep the new repository's default branch named `main`.

The workflow replaces `{--TEMPLATE_REPO_NAME--}` and `TEMPLATE_OWNER` in the staged project, promotes all files—including hidden files—from `template/` to the repository root, and removes the staging directory and this meta README. It also removes itself in the proposed changes; merging the PR completes initialization.

The workflow intentionally skips this source repository: `nmclaughlin98/aws-cdk-template-typescript`.

## Staged project

The complete CDK project boilerplate is in [`template/`](./template/). It includes the CDK stack, Node.js 24 Lambda handler, tests, package configuration, project documentation, and build/deploy workflows. After initialization, its own README and setup instructions are at the repository root.
