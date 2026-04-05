# Branching Strategy: Feature Branch Workflow

In this project, I follow a simple **Feature Branch Workflow** to maintain a clean and organized code history.

## Principles
1.  **Main Branch:** The `main` (or `master`) branch always contains stable, deployable code.
2.  **Feature Branches:** For every new task or feature, I create a dedicated branch (e.g., `feature/add-evidence`).
3.  **Pull Requests:** Changes are merged into `main` only after verification.

## Merging Strategy
-   **Merge Commits:** I use merge commits to preserve the historical context of when a feature was integrated.
-   **Conflict Resolution:** Conflicts are resolved locally before merging to ensure the main branch remains clean.
