# Document Store

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)

<table>
<tr>
<td>
Microservice for persisting documents to AWS S3 with role based access controls.
</td>
</tr>
</table>

## Contents

- [Conventional Commits](#maven-git-commit)

## Conventional Commits

This project uses the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification for commit
messages. The specification provides a simple rule set for creating commit messages, documenting features, fixes, and
breaking changes in commit messages.

A [pre-commit](https://pre-commit.com) [configuration file](.pre-commit-config.yaml) has been provided to automate
commit
linting. Ensure that *pre-commit* has been [installed](https://www.conventionalcommits.org/en/v1.0.0/) and execute...

```shell
pre-commit install
````

...to add a commit [Git hook](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks) to your local machine.

An automated pipeline job has been [configured](.github/workflows/git.yml) to lint commit messages on a push. 
