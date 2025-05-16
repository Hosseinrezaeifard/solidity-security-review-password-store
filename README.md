## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.


## 🛡️ About This Project

This repository is part of a smart contract auditing course provided by the [Cyfrin](https://www.cyfrin.io/) team.  
It contains exercises, vulnerabilities, and audits completed during the course.

The purpose of this project is to practice identifying and mitigating common security issues in Solidity smart contracts.

📚 Course Credit: [Cyfrin Security Auditing Course](https://academy.cyfrin.io/)


- [Foundry](#foundry)
- [🛡️ About This Project](#️-about-this-project)
- [Documentation](#documentation)
- [Usage](#usage)
  - [Build](#build)
  - [Test](#test)
  - [Format](#format)
  - [Gas Snapshots](#gas-snapshots)
  - [Anvil](#anvil)
  - [Deploy](#deploy)
  - [Cast](#cast)
  - [Help](#help)
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
