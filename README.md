# A WORK IN PROGRESS - GitHub Actions and Husky pre-commit

This repository serves as a boilerplate for new projects.  
Features a pre-commit hook (husky) that triggers Prettier formatting.  
Additionally it also includes a GitHub workflow that runs ESLint verification after each commit.

### Requirements:
 - Install ESLint, husky, lint-staged and prettier;
 - Need a eslint configuration file which you can create by running: `npm init @eslint/config`. The one found in this repository is only intended to be used as an example.
 - Ideally you should also modify the `.prettierrc` file to match your project needs.

 