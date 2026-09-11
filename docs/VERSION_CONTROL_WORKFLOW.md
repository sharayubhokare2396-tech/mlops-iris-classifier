# Git Version Control Workflow for MLOps Project

## Project
mlops-iris-classifier

## Branching Strategy
- main: Stable project branch
- develop: Development and integration branch
- feature/*: Used for implementing new features

## Workflow
1. Create a feature branch from develop.
2. Make the required changes in the project.
3. Stage and commit the changes with a meaningful commit message.
4. Push the feature branch to GitHub.
5. Create a Pull Request from the feature branch to develop.
6. Review and merge the Pull Request.
7. Pull the updated develop branch locally.

## Commit Convention
- feat: New feature
- fix: Bug fix
- docs: Documentation changes
- chore: Maintenance or configuration changes

## Useful Git Commands

```bash
git status
git switch develop
git switch -c feature/<feature-name>
git add .
git commit -m "feat: description"
git push -u origin <branch-name>
git pull origin develop