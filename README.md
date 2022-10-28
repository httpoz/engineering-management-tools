# Awesome Engineering Leadership [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of resources, guidance and support for engineering leaders. 
This resource aims to be a playbook for everyone from early career engineering managers all the way to the most seasoned VPs of Engineering building teams and cultures from the ground up.

If you transitioning into Engineering Management or you are stuck figuring things out, here is [a curated list for software developers to transition to an engineering management role.](https://github.com/kdeldycke/awesome-engineering-team-management)

## Contents

- [Platform](#platform)
  - [Incident Management and Response](playbooks/platform/incident-management/readme.md)
- [Contribute](#contribute)

## Contribute

Contributions welcome! Read the [contribution guidelines](.github/contributing.md) first.

# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
