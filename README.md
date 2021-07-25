# Summer 2021 Smart Contract Developer Bootcamp

Exercises done during the chainlink bootcamp

Chainlink is an Oracle network, allowing smart contracts to execute operations outside the blockchain, such as retrieving API feed.

#### Speakers:

Day1 - Harry Papacharissiou @Pappas9999

Day2 - Patrick Collins @PatrickAlphaC

## Notes
### Day 1
Blockchain demo

https://andersbrownworth.com/blockchain

SHA256Hash always same length

Block + Nonce + Data => Hash
Use nonce to change the hash without changing data
the mining is making the calculation to find the nonce that makes the hash have x number of leading zeros

Blockchain - reference previous block

Peers majority vote for blockchain

Chainlink
​@Mihir Jain Chainlink is a decentralized oracle network. LINK is a utility token used to pay node operators for executing jobs and tasks on the Chainink Network

Gas Auction - Bus analogy who pays more
@Jake Kunkel you can run your transactions in a virtual environment to estimate the gas, like on a local chain like ganache
​@Jacob Birmingham yep! anytime you make a change to state, you have to pay gas

#### Links
- [Upgrading your Smart Contracts | A Tutorial & Introduction](https://www.youtube.com/watch?v=bdXJmWajZRY&ab_channel=PatrickCollins)
- [Cryptozombies](https://cryptozombies.io/)
- [Chainlink](https://www.youtube.com/channel/UCnjkrlqaWEBSnKZQ71gdyFA)
- [Developer Bootcamp Weekend: Day 1 Exercises](https://docs.google.com/document/d/1-2j17bRPusTBSeUOH9_1VbL2YgKqUyLvM600AnEtQAc/preview?pru=AAABev1H5WU*bq8_9jYPLjQ4DrNXPXEWow)
Dd


_____

Oracle - blockchains are deterministic, need a way to reach external api cant all nodes call and consensus
Chainlink isn't a deterministic network, hence it can achieve non-deterministic consensus
https://blog.chain.link/levels-of-data-aggregation-in-chainlink-price-feeds/
Oracle market coverage help reduce risk of attacks


But oracles cant be centralized, otherwise risk.

So you have descentralized oracle network

https://ethresear.ch/t/counter-proposal-to-enshrined-price-feeds-dual-token-oracles/7437/3

https://docs.chain.link/ price feeds
https://blog.chain.link/build-defi-yield-farming-application-with-chainlink/

https://eth-converter.com/

Chainlink adapters

Chainlink market ethereum kovan
Most projects use the out of the box solutions like price feeds though. Like syntheitx, aave, compound, etc
​@Stênio Ferreira yes, you can increase the gas with the "speed up" button

Ideas

Eletric grid smart grid


Chainlink VRF - verified random number

______
### Day 2

[Chainlink blog](https://blog.chain.link/)

DefiPulse to see which stack most popular projects using
- yearn.finance github uses brownie
Curve finance


Remix is a devel environment/ framework
IDE
Ganache - local deployment blockchain
Brownie Mixes

For support:
Discord
Ethereum stack exchange, tag with brownie


Brownie accounts new
get_account(id=dog)

Set max gas price
https://docs.ethers.io/v5/api/contract/contract/#Contract-functionsCall

Ganache - local ethereum network - fake blockchain - spins a process
Brownie - suite for automating and testing
Oracle network - processing outside blockchain
Brownie network lists

Creator o infura and metamask https://consensys.net/about/


Smart contract attack -
Reentrancy
Oracle manipulation
Audit by 3rd party, peer review. Auditors

Smart contract is immutable, so testing is crucial
