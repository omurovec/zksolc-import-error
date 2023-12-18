# Issue

zksolc: `v1.3.16`
solc: `v0.8.16`

When attempting to compile, zksolc seems to have an issue resolving nested paths

```
Error:
Failed to compile smart contracts with zksolc: Compilation failed with "Source code for path `lib/prb-math/contracts/PRBMath.sol` not found\n". Using compiler: "~/.zksync/zksolc-macosx-arm64-v1.3.16", with args "~/import-error-example/src/Contract.sol" ["--standard-json", "--solc", "~/.svm/0.8.16/solc-0.8.16"]
```

## Steps to Reproduce

- Install latest foundry-zksync (nightly-74083adce839d7028e12836e51489119c5830cb8)
- `zkforge zkbuild`

# From Template:

## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

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
