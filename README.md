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

## Current code license

The identified Realsee-authored code is available under [PolyForm Noncommercial License 1.0.0](LICENSE), SPDX `PolyForm-Noncommercial-1.0.0`. The unmodified license governs permitted purposes, modification and distribution. This is source-available licensing, not an OSI-approved open source license. SDKs, third-party components and assets retain their separate terms. Earlier licensed copies retain their applicable rights, irrespective of this license change or Git history consolidation.
