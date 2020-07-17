# git-semver GitHub Actions
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

This repository contains GitHub Actions, which make it possible to use [git-semver](https://github.com/PSanetra/git-semver) commands in GitHub Action jobs. 

* latest: Return the latest version in the current repository.
* next: Return the next version, calculated by examining the Git history according to the conventional-commits spec.
* markdown-log: Return a changelog for a specific or the next version, formatted as markdown, calculated by examining the Git history according to the conventional-commits spec.
