# Eggs CI

GitHub Actions Workflow template for automatically publishing packages with Eggs

## Workflows

This repo has three workflows: Lint, Test and Ship

#### Lint

This workflow lists your deno code and checks if it is properly formatted.

#### Test

This workflow will run all the available tests in your repo.

#### Ship

This workflow will publish your module to nest.land on demand

this workflow needs your nest.land API key to be passed in as a secret.

follow these steps to create a new secret:

1. Go to your repository settings
2. Go to the "Secrets" menu
3. Click the "new secret" button
4. Set the name to `NESTAPIKEY`
5. Set the value to your nest.land API key
6. Click the "add secret" button

![image for step 1, 2 and 3](https://user-images.githubusercontent.com/28438021/88387051-4eab6080-cdcf-11ea-9848-4aab55825e4c.png)

![image for step 4, 5 and 6](https://user-images.githubusercontent.com/28438021/88387746-c4fc9280-cdd0-11ea-9cdf-2eb3ea05af32.png)

Now when you are ready you can follow these steps to publish your module

1. Go to the "Actions" tab of your repository
2. Select the "Ship" workflow
3. Select the "Run workflow" dropdown
4. Select the branch that has your module code.
5. Enter the version (to be published)
6. Click the "run workflow" button

![image for step 1, 2, 3, 4, 5 and 6](https://user-images.githubusercontent.com/28438021/88389691-95e82000-cdd4-11ea-92a9-b55a0d3a4cf9.png)
