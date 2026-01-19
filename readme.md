Git Flow Web Project

This repository contains a simple static web application used to demonstrate professional Git version control workflows. The focus of the project is not the application itself, but the disciplined use of Git for feature development, release management, and production fixes.

The project follows the Git Flow branching model and reflects workflows commonly used in team-based software development environments.

Project Overview

The application consists of a basic HTML, CSS, and JavaScript setup. Changes to the codebase are intentionally small and incremental to highlight best practices in source control, including meaningful commit messages, isolated feature branches, and controlled merges.

Git Workflow Model

This repository follows the Git Flow branching strategy:
main – Production-ready, stable code only
develop – Integration branch for completed features
feature/* – Feature-specific development
hotfix/* – Urgent fixes applied directly to production
release/* – Release stabilization and version preparation

Version tags are used to mark stable releases.
Key Practices Demonstrated
Feature-based branching and pull request workflows
Merge conflict identification and resolution
Hotfix handling with back-merging into development
Stashing for context switching between tasks
Safe undo strategies using revert and controlled reset
Clean, readable commit history

Release preparation and semantic version tagging

Technologies Used
HTML5
CSS3
JavaScript
Git (CLI)
GitHub
No frameworks are used intentionally to keep the focus on version control practices.

Release Management
Releases are prepared using dedicated release branches and tagged using annotated Git tags. Hotfixes are applied directly to the main branch and merged back into development to prevent regression.


