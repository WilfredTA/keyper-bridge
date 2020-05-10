# Introduction

Keyper Bridge enables easy Wallet <-> Dapp communication. It encapsulates message passing, event handling, serialization and deserialization in a simple asynchronous interface so that dapps can treat the wallet like another included module.

It also dynamically generates bindings to wallet functions so that message handling on the wallet side is also unnecessary if all you want to do is enable the dapp to call wallet functions from a different process. However, it is also extensible and customizable, allowing the ability to create and listen for custom messages, change the serialization, change the communication channels (e.g., from window message API to web sockets), and add additional bindings between the dapp and wallet for new wallet methods.

For an example of keyper bridge in use alongside a wallet, see the [Token Mint Demo](https://github.com/WilfredTA/token_mint) application.

# Install

`git clone https://github.com/WilfredTA/keyper-bridge`

`cd keyper-bridge`

`npm i`

`npm run build`
