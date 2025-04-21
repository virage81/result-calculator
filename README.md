# Simple Calculator Project

## Overview

This project is a simple calculator application developed to practice and demonstrate proficiency in using Git for
version control. The primary focus was to deepen understanding of Git workflows, maintain a clean commit history, and
adhere to the Conventional Commits specification. The calculator serves as a functional application to apply these
Git-related skills in a practical context.

## Project Goals

The main objective of this project was to master Git operations and best practices for collaborative development.
Specific goals included:

1. Gaining expertise in Git commands and workflows, including branches, tags, commits, merges, rebases, stashes,
   reverts, cherry-picks, and resets.
2. Mastering Git rebase to maintain a clean and linear commit history.
3. Learning to merge branches effectively using rebase for streamlined integration.
4. Understanding how to create, apply, and manage Git patches for sharing changes.
5. Configuring a public repository on GitHub or GitLab to facilitate collaboration with other developers.

## Implementation

The project was structured to incorporate the above goals through deliberate practice and application of Git techniques.
The following outlines how each goal was achieved:

### 1. Proficiency in Git Commands and Workflows

- **Branches**: Created and managed multiple branches (e.g., `feature/calculator`, `bugfix/division`, `release/v1.0`) to
  organize development tasks and isolate changes.
- **Tags**: Used tags (e.g., `v1.0.0`) to mark release points and significant milestones in the project.
- **Commits**: Followed the Conventional Commits specification (e.g., `feat: add basic arithmetic operations`,
  `fix: handle division by zero`) to ensure clear, structured, and meaningful commit messages.
- **Merges**: Performed merges to integrate feature branches into the main branch, resolving conflicts when necessary.
- **Reverts**: Practiced reverting commits to undo changes while preserving history.
- **Cherry-picks**: Selectively applied specific commits from one branch to another for targeted updates.
- **Resets**: Experimented with soft, mixed, and hard resets to manage commit history and working directory states.
- **Stashes**: Utilized stashes to temporarily save changes during context switches, ensuring a clean working directory.

### 2. Mastering Git Rebase

- Employed `git rebase` to maintain a linear and clean commit history by rewriting commit sequences.
- Rebasing was used to update feature branches with the latest changes from the main branch, avoiding unnecessary merge
  commits.
- Practiced interactive rebasing (`git rebase -i`) to squash, edit, and reorder commits for clarity and conciseness.

### 3. Merging Branches with Rebase

- Integrated branches using rebase instead of traditional merges to create a streamlined history.
- For example, feature branches were rebased onto the main branch before fast-forward merging to ensure a linear
  timeline.
- Handled rebase conflicts systematically, resolving them and continuing the rebase process.

### 4. Working with Patches

- Created patches using `git format-patch` to share specific changes with collaborators or for backup purposes.
- Applied patches using `git apply` or `git am` to incorporate changes from external sources or previous commits.
- Practiced managing patch workflows to simulate collaborative scenarios where changes are shared without direct
  repository access.

### 5. Public Repository on GitHub/GitLab

- Initialized a public repository on GitHub (or GitLab) to host the project.
- Configured repository settings, including branch protection rules to enforce code reviews and maintain quality.
- Documented the project structure and contribution guidelines in this README to facilitate collaboration.
- Practiced pushing changes to the remote repository and managing pull requests (or merge requests) to simulate team
  workflows.

## Project Structure

The calculator application was developed as a simple command-line or GUI-based tool (depending on implementation)
supporting basic arithmetic operations (addition, subtraction, multiplication, division). The codebase was organized to
reflect modular development, with separate branches for features, bug fixes, and releases.

Key aspects of the implementation:

- **Clean Commit History**: Achieved through consistent use of Conventional Commits and rebasing to eliminate redundant
  merge commits.
- **Branching Strategy**: Followed a feature-branch workflow, with descriptive branch names (e.g.,
  `feature/calculator-actions`, `feature/core`).
- **Collaboration Readiness**: The public repository was set up with clear documentation and contribution guidelines to
  support teamwork.

## Key Learnings

Through this project, the following Git-related skills were solidified:

- Effective use of Git commands to manage code versions and collaborate with others.
- Maintaining a clean and linear commit history using rebasing and Conventional Commits.
- Resolving conflicts during merges and rebases with confidence.
- Sharing and applying changes via patches for flexible collaboration.
- Setting up and managing a public repository for open-source or team-based development.

## Getting Started

To explore or contribute to this project:

1. Clone the repository: `git clone <repository-url>`
2. Check out a feature branch: `git checkout -b feat/your-feature`
3. Make changes and commit using Conventional Commits: `git commit -m "feat: add new feature"`
4. Push changes and create a pull request: `git push origin feat/your-feature`

Refer to the repository's contribution guidelines for more details on coding standards and workflows.

## Conclusion

This simple calculator project served as a practical platform to master Git version control techniques. By focusing on
clean commit practices, effective branch management, and collaborative workflows, the project demonstrates a robust
understanding of Git and its application in real-world development scenarios.
