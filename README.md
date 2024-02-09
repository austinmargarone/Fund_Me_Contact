# Fund Me Smart Contract

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

![Preview Image](devpreview.png)


## Description

Welcome to My Fund Me Smart Contract! This repository contains the codebase for my Contract built in foundry with a simple frontend. Here you can connect your metamask wallet, see your balance and add funds to the contract!

## Table of Contents

- [Fund Me Smart Contract](#fund-me-smart-contract)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Technologies Used](#technologies-used)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Documentation](#documentation)
  - [Usage](#usage-1)
    - [Build](#build)
    - [Test](#test)
    - [Format](#format)
    - [Gas Snapshots](#gas-snapshots)
    - [Anvil](#anvil)
    - [Deploy](#deploy)
    - [Cast](#cast)
    - [Help](#help)


## Technologies Used

My Fund Me Contract is built using the following technologies:

- Solidity
- Foundry
- Anvil
- HTML
- CSS
- JavaScript

## Features

- Connect MetaMask wallet
- See Balance
- Add funds to contract
- Owner can withdrwal funds

## Installation

To set up the project locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone github.com/austinmargarone/portfolio.git
   ```
2. Navigate to the project directory:

   ```bash
   cd realtor
   ```

3. Install the necessary dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

## Usage

Explore what I have to offer as a developer!

## Contributing

We welcome contributions from the community! To contribute to the project, follow these steps:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a new Pull Request.

Please review our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the [MIT License](LICENSE).


## Contact

For questions or support, please contact Austin Margarone at austin@margarone.dev.
**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
