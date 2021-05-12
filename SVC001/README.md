# SVC001: Stacker Ventures VC Fund 1

**SVC001 Token Contract Address**: [0xa8b3b1392b17f64d5a50b4b4bd3800324d07800b](https://etherscan.io/address/0xa8b3b1392b17f64d5a50b4b4bd3800324d07800b)

Deposits to Fund 1 were collected through this Gauge Smart Contract: [0xcd8dd2891df222dddebbeb77748a3c59c843c4e0](https://etherscan.io/address/0xcd8dd2891df222dddebbeb77748a3c59c843c4e0) 

At Block Number **12346260**, any Soft Commitments that were not yet withdrawn were fully committed to the Fund alongside all of the preexisting Hard Commitments.

By querying the `balances` property of the Gauge Smart Contract and providing the investor's address, a final snapshot of their Soft Commitments and Hard Commitments will be returned.

These final balances were used to mint the distributions for SVC001 Fund token.

Here is a [Full Breakdown](https://github.com/stacker-ventures/funds-info/blob/main/SVC001/SVC001-distributions.json) of the tokens minted for all of the final deposits to the fund.

The Full Breakdown above corresponds to the tokens minted across the following 4 transactions:
[0x73d1970035961693787ad5224f773c81d4206d24fd63cd84c7b8f5101f191672](https://etherscan.io/tx/0x73d1970035961693787ad5224f773c81d4206d24fd63cd84c7b8f5101f191672)
[0x4be84917b1a23038fa605c9e33a24b88e0130c152b32f7cae50fe14685180c57](https://etherscan.io/tx/0x4be84917b1a23038fa605c9e33a24b88e0130c152b32f7cae50fe14685180c57)
[0x4356b1ce16cb143a26852bb8afb25a9086430a1097fc78886526ba171222c021](https://etherscan.io/tx/0x4356b1ce16cb143a26852bb8afb25a9086430a1097fc78886526ba171222c021)
[0xadf5fdabd2efb30bf31127c77a6acebac704c818f36b3b768b3bbf940bfb3220](https://etherscan.io/tx/0xadf5fdabd2efb30bf31127c77a6acebac704c818f36b3b768b3bbf940bfb3220)

By examining the Event Logs of the Minting transactions above, they will correspond to the amounts in the Full Breakdown file.

The Full Breakdown file contains all of the investors who deposited through the Gauge Contract and they also received STACK rewards for their deposits into Fund 1.

In addition to Gauge Contract participants, there were some early investors to the Fund who did not receive STACK rewards. Their contributions are accounted for in the DAO Treasury. The tokens for the early participants were minted in the final minting transaction: 
[0xaf31a5844df48a5bca883af4e886c7edcee098c3c1f71dc33117574eef5104f7](https://etherscan.io/tx/0xaf31a5844df48a5bca883af4e886c7edcee098c3c1f71dc33117574eef5104f7)

The [Source Code](https://etherscan.io/address/0xa8b3b1392b17f64d5a50b4b4bd3800324d07800b#code) of the SVC001 Token contract is published and verified on EtherScan. These tokens represent your share of the Assets managed by the fund. 

After verifying that all distributions were correct, the `governance` property of the Smart Contract is now set to the `0x0` address, which means no further tokens can be minted.
