# erc20-challenge Demo


## Setup

Clone this repo:
git clone https://github.com/tonysun83/erc20-challenge

### Local Node Setup 
1) cd erc20-node-template
2) WASM_BUILD_TOOLCHAIN=nightly-2020-10-05 cargo build --release


### Install and Build The Contract
1) cd erc20
2) cargo +nightly contract build
3) cargo +nightly contract generate-metadata
Follow instructions here to upload binary and deploy contract:
https://substrate.dev/substrate-contracts-workshop/#/0/deploying-your-contract

### Front End Setup

1) cd erc20-front-end-template
2) yarn install
3) yarn run

Send Tokens From Alice Account in the ERC20 Token Transfer section

![alt text](https://github.com/tonysun83/erc20-challenge/blob/main/upload-start.png?raw=true)

![alt text](https://github.com/tonysun83/erc20-challenge/blob/main/upload-complete.png?raw=true)

![alt text](https://github.com/tonysun83/erc20-challenge/blob/main/deploy-contract.png?raw=true)

![alt text](https://github.com/tonysun83/erc20-challenge/blob/main/transferproof.png?raw=true)

