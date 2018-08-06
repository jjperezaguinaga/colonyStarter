# Colony Starter

_Learn to build with Colony! Get a head start on your next project!_

Colony Starter (formerly known as "Hackathon Starter") includes a variety of starter packages that demonstrate how to use and integrate different tools with Colony. We want to make it as easy as possible for you to start building with Colony so we upgraded to a monorepo that includes a variety of starter packages that you can install with a just few simple commands.

## Get Started

### Step 1

Globally install the [@colony/colony-starter](https://www.npmjs.com/package/@colony/colony-starter) package with yarn:

```
yarn global add @colony/colony-starter
```

### Step 2

Move to your working directory and unpack the [colony-starter-basic](/packages/colony-starter-basic) package:

```
colony-starter colony-starter-basic
```

### Step 3

Move to your new starter directory and checkout the [colony-starter-basic](/packages/colony-starter-basic) readme:

```
cd colony-starter-basic
```

## Starter Packages

Now that you have a basic understanding of how Colony works, check out some of the other starter packages by repeating steps 2 and 3 and substituting `colony-starter-basic` with the package of your choice!

### General

- [colony-starter-basic](/packages/colony-starter-basic)
- [colony-starter-react](/packages/colony-starter-react)

### Specific

- [colony-starter-dao](/packages/colony-starter-dao)
- [colony-starter-daico](/packages/colony-starter-daico)

## Development

### Prerequisites

- Yarn 1.7
- Node 9.5

_You may find it helpful to use Node Version Manager (`nvm`) to manage node versions._

### Install Dependencies

Install development dependencies:

```
yarn
```

### Start Network

Start a local test network with [Ganache](https://github.com/trufflesuite/ganache-cli):

```
yarn start-ganache
```

### Deploy Contracts

Open a new terminal window and deploy contracts with [Truffle](https://github.com/trufflesuite/truffle):

```
yarn deploy-contracts
```

### Start TrufflePig

Open a new terminal window and connect to the deployed contracts with [TrufflePig](https://github.com/JoinColony/trufflepig):

```
yarn start-trufflepig
```

### Run Tests

Open a new terminal window and run tests:

```
yarn test
```

### Test Install Package

Open a new terminal window and test install a package:

```
yarn colony-starter [colony-starter-package]
```
