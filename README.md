Hi! I'm currently deep-diving into Cyfrin Updraft's Foundry Fundamentals course 🚀. This project is all about mastering the art of smart contract development with Foundry — from setting up the playground to writing, testing, and deploying Solidity magic ✨.

Honestly, this course sometimes makes me feel like my brain took a coffee break without telling me ☕️🧠💨. Like, Foundry's flexin' hard, and I'm just trying to keep up without face-planting into code 🤯. But hey, that’s the sweet struggle of leveling up in blockchain dev — gotta respect the hustle while it politely roasts my coding ego 😅🔥.

It’s like Foundry is that strict but fair gym coach for Solidity, making me do reps of testing, deploying, and debugging — sweat and all 💪💻. But once you get the hang of it, you feel like a smart contract ninja 🥷 ready to conquer the decentralized world 🌐.

So yeah, riding this Updraft wave like a pro surfer, catching bugs and bugs 🐛🐛 with style, and slowly turning my 'stupid moments' into 'aha!' moments. Foundry, you cheeky beast, I’m coming for ya! 🎯🤓

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
