# Eggs CI

GitHub Actions Workflow template for automatically publishing packages with Eggs

## Workflows

This repo has three workflows: Lint, Test and Ship

- **Lint** - runs `deno lint` and `deno fmt` on your repository

- **Test** - run all the available tests in your repository

- **Ship** - publish your module to nest.land whenever you create a release or push a tag to your GitHub repository

> **NOTE:** You need to set your nest.land api key as a secret for the "Ship" workflow to run. See [GitHub Secrets docs](https://docs.github.com/actions/reference/encrypted-secrets) for more details.
