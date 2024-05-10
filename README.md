![MetaMask logo](logo.png?raw=true)

# MetaMask



Sample Web3-Wallet is a mobile wallet that provides easy access to websites that use the [EVM-Compatible](https://icb.network/) blockchain.


## Documentation

- [Architecture](./docs/readme/architecture.md)
- [Development Environment Setup](./docs/readme/environment.md)
- [Build Troubleshooting](./docs/readme/troubleshooting.md)
- [Testing](./docs/readme/testing.md)
- [Debugging](./docs/readme/debugging.md)
- [Storybook](./docs/readme/storybook.md)
- [Miscellaneous](./docs/readme/miscellaneous.md)

## Getting started

### Environment setup

Before running the app, make sure your development environment has all the required tools. Several of these tools (ie Node and Ruby) may require specific versions in order to successfully build the app.

[Setup your development environment](./docs/readme/environment.md)

### Building the app

**Clone the project**

```bash
git clone git@github.com:ICBNetwork/web3-Wallet.git
cd web3-Walet
```

**Install dependencies**

```bash
yarn setup
```

_Not the usual install command, this will run scripts and a lengthy postinstall flow_

### Running the app

**Run Metro bundler**

```bash
yarn watch
```

_Like a local server for the app_

**Run on a iOS device**

```bash
yarn start:ios
```

**Run on an Android device**

```bash
yarn start:android
```
