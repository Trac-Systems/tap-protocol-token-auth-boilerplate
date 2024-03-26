# Token Authority Boilerplate for TAP Protocol

This boilerplate generates inscription texts to create token authorities as well as redeem inscriptions (see https://github.com/BennyTheDev/tap-protocol-specs).

A token authority enables sub-indexers to hook into the TAP Protocol and allows for off-Bitcoin computation to distribute tokens from the authority.

Projects may find this boilerplate useful to connect to their own applications, games, services, and L2s with the TAP Protocol.

What it does:

- Demonstrates how to create a token authority.
- Demonstrates how a token authority generates and signs redeem inscription.
- Allows to perform single or multiple token transfers in one transaction instead of 2.

## Requirements

NodeJS 20+

## Installation & Execution

Clone this repository in order to run:

```
git clone https://github.com/Trac-Systems/tap-protocol-token-auth-boilerplate.git
cd tap-protocol-airdrop-boilerplate
npm i
node token-auth.mjs
```
