# Tezos Tweet

NFT DApp for posting tweets anonymously and also getting public support in the form of anonymous donations which will be secured on Tezos Blockchain.

This dapp is heavily inspired from:
+ Tutorial [Build your first DApp on Tezos in 2-4 hours](https://styts.com/your-first-tezos-dapp) 
+  [medium post building your first dapp on tezos](https://medium.com/coinmonks/building-your-first-dapp-on-tezos-part-1-writing-smart-contract-on-smartpy-d7cdf27476f9)

## Quick Demos

### [Demo on Mainnet](https://tztweet.xyz)
### [Demo on Florencenet Testnet](https://test.tztweet.xyz)
### [Demo on YouTube](https://www.youtube.com/watch?v=xxxxxxx)


## The problem

Media is the fourth pillar of democracy. In many countries media is controlled by the government which is suppressing their Freedom of speech( eg: [Censorship_in_China](https://en.wikipedia.org/wiki/Censorship_in_China) ).

Blockchain can solve this problem since it is decentralized. This is an example project, a tweet site where anyone can share their views anonymously and the writers can also get support in the form of anonymous donations(work in progress). This will ensure no central authority controls the content of the articles since it is distributed.

## Developers Tutorial

first you need to create a smart contract using https://smartpy.io/ide , please follow the [medium post building your first dapp on tezos](https://medium.com/coinmonks/building-your-first-dapp-on-tezos-part-1-writing-smart-contract-on-smartpy-d7cdf27476f9)

Here is my smart contract (testnet): [KT1CnJWdLMEcUsRvuXLxLC6LNysHHZAZx8to](https://better-call.dev/florencenet/KT1CnJWdLMEcUsRvuXLxLC6LNysHHZAZx8to/operations)

Now clone this repo, update the contract address with yours in `pages/index.vue` and install dependencies and build it.

for [Florencenet Testnet](https://test.tztweet.xyz) use branch: `florencenet`

for [mainnet](https://tztweet.xyz) use branch: `main`


```bash
$ git clone https://github.com/gamifications/tztweet
$ cd tztweet
# install dependencies
$ npm install

# build for production and launch server
$ npm run generate
$ npm start
```

