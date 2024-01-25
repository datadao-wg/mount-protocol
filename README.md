# Mount protocol

Mission:**Building Finance first Data DAO Asset Creation and Issuance Protocol**

Vision:**Open Finance First, Open Data Second, Open AI Third**

## Contribute

We’re developing Mount, an Filecoin protocol that establishes DataDAO with algorithmically set interest rates; users and dApps will be able to earn interest on FIL and tokens, and borrow Ether and tokens to invest, use, or short-sell.

The mount contract is mainly divided into 3 parts: **deployer**, **factory**, **agency**

**deployer**: mount the passport of the protocol, only the deployer can provide the protocol to deploy NFTs

**agency**: A pool of funds, where the ERC20 tokens minted by users will be stored in the agency

**factory**: It is convenient for users who hold deployer NFTs to quickly deploy agencies and apps

## Related contracts

**Voting contract:**

1.Datadao can control data to perform a series of operations, such as: receiving data, renewing data storage, and controlling user access to data.

2.Datadao can control the fund pool on the chain and manage the allocation of funds on the chain.

**reference**:

1.https://github.com/GeekyAnts/sample-e-voting-system-ethereum

2.https://github.com/madrona-labs/voting	  

3.https://github.com/VirginiaBlockchain/QuadraticVotingDapp

**Mount contract:**

1.Users can store data in filecoin and wait for datadao voting review.

2.Datadao provides users with data funding, and the ownership of the data belongs to datadao,after the data is stored in filecoin.

3.Datadao generates the corresponding DealID and gives it to the user as an NFT certificate,after datadao votes and uploads the data.

**reference**:

smart contracts in wrap protocol

[ERCs/ERCS/erc-7527.md at lanyinzly-patch-1 · lanyinzly/ERCs (github.com)](https://github.com/lanyinzly/ERCs/blob/lanyinzly-patch-1/ERCS/erc-7527.md)

**Permanent storage contract:**

1.Datadao can manage Renewal operation of DealID of data.

2.Datadao controls the data uploaded by users to be stored on filecoin.

**reference**:

1.https://github.com/FILCAT/client-contract

2.https://github.com/FILCAT/deal-bounty-contract

3.https://github.com/FILCAT/dotStorage-deal-renewal

**Market contract:**

1.Datadao can auction data and define a starting price. investors can participate in the bidding for the required data.

2.Datadao can trade data with investors, and datadao defines the price of data.

**reference**:

1.https://github.com/oceanprotocol/contracts/tree/main

## Official Website

https://mountprotocol.xyz/
