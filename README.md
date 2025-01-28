# Docs-DiscussPlanner
[![Docusaurus](https://img.shields.io/badge/Docusaurus-2E8555?style=for-the-badge&logo=docusaurus&logoColor=white)](https://discussplanner.netlify.app/)  
[![Netlify Status](https://api.netlify.com/api/v1/badges/57eb4dea-9994-45f4-9e97-6a9026413134/deploy-status)](https://app.netlify.com/sites/discussplanner/deploys)  


https://github.com/BPS-sys/DiscussPlanner の 開発者用ドキュメント

# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

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
