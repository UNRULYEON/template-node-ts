# template-node-ts

This is a template for a Node application written with TypeScript. This template has been set up with:

- [Prettier](https://prettier.io/)
- [Conventional commits](https://conventionalcommits.org) ([cz-cli (commitizen)](https://github.com/commitizen/cz-cli) and [commitlint](https://github.com/conventional-changelog/commitlint))
- [Release please](https://github.com/googleapis/release-please) as a Github Action
- Docker for development and production
- License (MIT)
- Contributing guide

After creating a repository from this template, go through this checklist and search for all the keywords and change them to whatever you like:

- [ ] Changed `APPLICATION_NAME` to the application name
- [ ] Changed `APPLICATION_DESC` to a description of the application
- [ ] Changed `REPO_NAME` to the name of the repo
- [ ] Changed `REPO_SSH_URL` to the SSH URL of the repo (`git@github.com:USERNAME/template-node-ts.git`)
- [ ] Changed `AUTHOR` to the author of the application (`AUTHOR <EMAIL>`)

After going through this checklist, remove the section above the divider.

---

# APPLICATION_NAME

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org) [![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

APPLICATION_DESC

## Gettings started

Developing and running APPLICATION_NAME is recommended with Docker. Running APPLICATION_NAME without is also possible.

### Running APPLICATION_NAME in Docker

APPLICATION_NAME has Docker support for both development and production.

| Script                   | Description                                                     |
| ------------------------ | --------------------------------------------------------------- |
| `yarn start:docker`      | Starts APPLICATION_NAME in development mode in Docker           |
| `yarn start:docker:prod` | Builds and starts APPLICATION_NAME in production mode in Docker |

APPLICATION_NAME will be available on the default port `3000` or the one specified in `.env`

### Running APPLICATION_NAME

Make sure you have the following installed:

- Node, you can find the current version in [`.nvmrc`](https://github.com/UNRULYEON/REPO_NAME/blob/main/.nvmrc)
- Yarn

Next, following these steps

1. Run `yarn` to install all dependencies
2. Run `yarn start` to run APPLICATION_NAME
3. APPLICATION_NAME will be available on the default port `3000` or the one specified in `.env`

## How to contribute

APPLICATION_NAME follows [conventional commits](https://conventionalcommits.org) and has been set up with [cz-cli (commitizen)](https://github.com/commitizen/cz-cli). Make sure to read the contributing documentation.

[Read more &rarr;](CONTRIBUTING.md)
