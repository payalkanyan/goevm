# GoEVM from scratch

This is a Mock Isolated EVM modal written in GoLang for learning purposes.
This is an implementation of https://evm-from-scratch.xyz/content/01_intro.html as an example.
The EVM have Memory, Storage, Stack, Event Logging, Opcode Instructions implemented.
The EVM is written with Dynamic Gas specification. It has no state of accounts as memory, storage, event logs everything gets reset after every EVM execution.
Some of the Opcodes are not implemented as those require state management.
