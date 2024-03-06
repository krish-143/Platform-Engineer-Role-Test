This repository contains a Python script that creates a new GitHub repository for both Platform and data enginerrs when triggered based on engineer-type variable, using the GitHub API.

## Prerequisites

You need to have a GitHub Personal Access Token (PAT) with the necessary permissions to create repositories. This token should be stored in a secret in your GitHub repository named `GH_TOKEN`.

## Running the Python script

This Python script (main.py) is set up to run manually through the GitHub Actions tab in your repository. When you run the action, you will be prompted to enter the following information:

- Repository Name
- Organisation Name (or User Name)
- Repository Description (optional)
- Default Branch (optional)
- engineer-type (platform or data)

## Example

To run the action, navigate to the Actions tab in your repository, select the "Create Repository" workflow, and click "Run workflow". Enter the required information and click "Run workflow" again.


## Important Note

This repo contains two word files with name **approach to task** and **ideal changes**

**approach to task**  This word file clearly explains my approach about the task.

**ideal changes**  This word file clearly explains what the actual changes I made to the default template
# Platform-Engineer-Role-Test
