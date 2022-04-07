# An overview of DeFi, 0x Protocol, 0x API



## Environment setup

This demo will only work on the Kovan testnet.

This tutorial will be using 2 dummy ERC20 token contracts that I deployed on the Kovan testnet. These are not the real DAI and USDC, but they are drop-in replacements. Each contract also exposes a `mint(uint256)` function that can be used to create tokens for the user.

- DAI (18 decimals) is hosted at: `0x48178164eB4769BB919414Adc980b659a634703E`
- USDC (6 decimals) is hosted at: `0x5a719Cf3E02c17c876F6d294aDb5CB7C6eB47e2F`

## Environment setup

This webapp has been tested with Node v10.15.3. Use `npm install` to install all the various dependencies and, after installation finishes successfully, run `npm run serve` to run a live webserver on `http://localhost:9000`. Any change to the TypeScript code will trigger the webpage to refresh with newly compiled code.





Create Your Own Exchange

Prerequisites

Please do the following:

* Install [Metamask](https://metamask.io/) (on Chrome) and create a new account (optionally, re-use an existing account)
* Install [VSCode](https://code.visualstudio.com/) (Will make programming in TypeScript much easier)
* **Important!** Mint some KETH by using the [faucet](https://faucet.kovan.network/), or by pasting your address in the [Kovan Gitter](https://gitter.im/kovan-testnet/faucet), please ensure that you have at least 1-2 ETH.
* Install NodeJS, preferably v10.15.3 or higher. If you use Linux as an OS, please ensure that your NodeJS has all the shared libraries, compilers, in order to install packages with native C code.
* Revise [ERC20 token allowances](https://tokenallowance.io/)
* Register for an [Infura account](https://infura.io/) (free)
* Make sure you are comfortable working with JavaScript. You should be familiar with concepts such as promises, `async`/`await` syntax, anonymous functions (or callbacks).



Detail

In the task, you will build your own DeFi application, which is an exchange that uses [0x API](https://0x.org/api) to easily swap between [DAI](https://makerdao.com/en/) and [USDC](https://www.centre.io/usdc).

**clone** it to get started.

Check Off - Email us a screenshot of your exchange web app after successfully swapping DAI and USDC. It should look something like this.



In addition, please send us a screenshot of your MetaMask. It should look like something like this. 


