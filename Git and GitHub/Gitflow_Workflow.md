# Gitflow Workflow

- **Develop Branch:** Created from main.
- **Release Branch:** Created from develop.
- **Feature Branch:** Created from develop.
- **Feature Complete:** Merged into develop.
- **Release Complete:** Merged into develop and main.
- **Hotfix:** Created from main for production issues, merged back into develop and main.

## The overall flow of Gitflow is

1. A `develop` branch is created from `main`.
2. A `release` branch is created from `develop`.
3. `Feature` branches are created from `develop`.
4. When a `feature` is complete it is merged into the `develop` branch.
5. When the `release branch` is done it is merged into `develop` and `main`.
6. If an issue in `main` is detected, a `hotfix branch` is created from `main`.
7. Once the `hotfix` is complete, it is merged into both `develop` and `main`.
