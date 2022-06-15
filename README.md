# Stackup documentation

## Description

This issue outlines a simple documentation structure and a sample document for building
[Stackup's](https://stackup.sh/) developer documentation. Stackup is EIP 4337 compatible smart contract Wallet.

## Documentation Structure

```
docs/     # Root directory.
|- intro.md                   # Introduction about stackup
|- getting-started/      # Lists down prerequisites tools, dependencies & link to architecture
|- architecture/           # Explains how multiple apps play their roles
|- Explorer/                 # Service for fetching blockchain data for an address
|- bundler/                  # Service for forwarding UserOperations to the EntryPoint
|- backup/                  # Service for providing encrypted and non-custodial backup of wallets.

```

## How to create a doc

Refer Docusaurus documentation - [here](https://docusaurus.io/docs/create-doc)

## Each doc structure

```
TODO: Set structure for each doc item.
```

# Usage

This documentation is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

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

# License

Distributed under the GPL-3.0 License. See [LICENSE](./LICENSE) for more information.

# Contact

Feel free to direct any technical related questions to the `dev-hub` channel in the [Stackup Discord](https://discord.gg/FpXmvKrNed).
