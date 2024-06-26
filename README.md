# Add step view to your workflow
<img width="266" alt="Screenshot 2024-05-13 at 4 53 45 PM" src="https://github.com/32teeth/GitHubWorkflows/assets/75797/10c8916b-2b7c-4cda-93da-c45c0e215f94">



## Caller Workflow [![Caller](https://github.com/32teeth/GitHubWorkflows/actions/workflows/caller.yml/badge.svg?branch=main)](https://github.com/32teeth/GitHubWorkflows/actions/workflows/caller.yml)

1. Create a new GitHub Actions workflow file in your repository, for example, `caller.yml`.
2. Copy the provided workflow YAML into `caller_workflow.yml`.
3. Optionally, replace the placeholder credentials (`${{ secrets.CREDENTIAL1 }}` and `${{ secrets.CREDENTIAL2 }}`) with your actual secrets.
4. Adjust any other configuration settings as needed.
5. Commit and push the changes to your repository.

## Check Workflow [![Check](https://github.com/32teeth/GitHubWorkflows/actions/workflows/check.yml/badge.svg?branch=main)](https://github.com/32teeth/GitHubWorkflows/actions/workflows/check.yml)

1. Create a new GitHub Actions workflow file in your repository, for example, `check.yml`.
2. Copy the provided workflow YAML into `check.yml`.
3. Adjust any configuration settings as needed.
4. Commit and push the changes to your repository.

## Pre Flight Workflow [![Pre Flight](https://github.com/32teeth/GitHubWorkflows/actions/workflows/pre-flight.yml/badge.svg?branch=main)](https://github.com/32teeth/GitHubWorkflows/actions/workflows/pre-flight.yml)

1. Create a new GitHub Actions workflow file in your repository, for example, `pre-flight.yml`.
2. Copy the provided workflow YAML into `pre-flight.yml`.
3. Adjust any configuration settings as needed.
4. Commit and push the changes to your repository.

## Reusable Workflow [![Reusable](https://github.com/32teeth/GitHubWorkflows/actions/workflows/reusable.yml/badge.svg?branch=main)](https://github.com/32teeth/GitHubWorkflows/actions/workflows/reusable.yml)

1. Create a reusable workflow file named `reusable.yml`.
2. Copy the provided workflow YAML into `reusable.yml`.
3. Add the necessary steps and logic for your reusable workflow.
4. Commit and push the changes to your repository.
5. Ensure that the main workflow (`caller.yml`) properly triggers the `reusable` job with the required inputs.
6. Test the workflow to ensure it behaves as expected.

Make sure that your repository has appropriate secrets set up in GitHub Settings, and ensure that the workflows are properly configured to use these secrets. Also, ensure that the triggers and conditions for each workflow suit your project requirements.
