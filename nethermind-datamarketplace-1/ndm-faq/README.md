---
description: Frequently asked questions about the Nethermind Data Marketplace
---

# FAQ

## What is NDM? 

Nethermind Data Marketplace is a protocol that creates a subnetwork within Ethereum to handle data delivery directly between parties running NDM-supporting nodes. NDM allows data consumers to discover data providers and uses a smart contract to facilitate on-chain, secure payments in exchange for data. Its unique built-in reputation and data delivery protocol minimises the amount of on-chain transactions.

## Where to download NDM?

You can download up to date packages on [Nethermind downloads page](https://downloads.nethermind.io/)

## Is NDM a finished project? 

No, right now we are at beta phase of NDM. It is not a finished product so you should expect some bugs. 

## Where can I find technical assistance? 

We have a sepparate channel for NDM on our Discord server, feel free to ask any questions there. You can find it at [Nethermind Discord](https://discord.gg/732jyuNjph).

## Can data providers also join NDM ?

Yes, NDM was built for consumers as well as for providers.

## Do I need to wait for sync before using NDM? 

Yes, we recommend to run NDM with Beam Sync to make sync process as fast as possible.

## How does the Proccess of buying data looks like ?

First of all you will neeed to connect to a provider, after that you will be able to make a deposit for data asset of your choice. Payment for the data will be charged from deposit you made and not from your wallet.

For example - you connected to a provider which provides data asset with units 1 gwei per each. You make a deposit for 100 units, so 100 gwei is transfered from wallet to NDM smart contract, each time you use a single unit, 1 gwei (plus fee) will be transfered from the deposit on contract to the provider account. 

## What cryptocurrency can I use to pay with NDM? 

It depends on the package you are using - right now we are supporting ETH and xDai.

## Do I need a wallet to start using NDM?

No, NDM is able to create a wallet for the sake of using NDM first time you run a client.

## Can I use my own account?

Yes, you can. Copy your keystore file info 'keystore' folder and that's it. After running application the window to unlock the account appear.

## How do I import my wallet into MetaMask?

NDM wallets can be imported into MetaMask as a Keystore file.  To do so, follow the instructions at [https://metamask.zendesk.com/hc/en-us/articles/360015489331-Importing-an-Account](https://metamask.zendesk.com/hc/en-us/articles/360015489331-Importing-an-Account), choose JSON File as the type, and then when prompted to select your Keystore file:

1. locate your NDM installation folder
2. navigate to the `keystore` folder
3. select the file that has your Ethereum address in the name

## How do I import my wallet into MyEtherWallet?

NDM wallets can be imported into MyEtherWallet as a Keystore file.  To do so, follow the instructions at [https://kb.myetherwallet.com/en/getting-started/how-to-access-your-wallet/\#Keystore-JSON-Password](https://kb.myetherwallet.com/en/getting-started/how-to-access-your-wallet/#Keystore-JSON-Password) and when prompted to select your Keystore file:

1. locate your NDM installation folder
2. navigate to the `keystore` folder
3. select the file that has your Ethereum address in the name

## How do I import my wallet into MyCrypto?

Consumer and provider wallets in NDM can be imported into MyCrypto as a Keystore file.  To do so, follow the instructions at [https://support.mycrypto.com/how-to/accessing-wallet/how-to-access-your-wallet-with-keystore-file](https://support.mycrypto.com/how-to/accessing-wallet/how-to-access-your-wallet-with-keystore-file) and when prompted to select your Keystore file:

1. locate your NDM installation folder
2. navigate to the `keystore` folder
3. select the file that has your Ethereum address in the name

## Where can I change account? 

In the account tab you have an option to change current account. 