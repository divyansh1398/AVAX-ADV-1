# Avax-Eth Assignment 1

Using deposit(),withdraw(),totalSupply,balanceOftoken functions using avalanche subnet.

## Description

Contract for creating a seperate wallet/vault for every user and user will do certain operations.

## Getting Started

## Initialize

1. Enter your subnet name with this command.

``avalanche subnet create mySubnet``

Then select these properties as is

Select ``SubnetEVM``
Select ``Use latest version``
Select ``Low disk use / Low Throughput 1.5 mil gas/s (C-Chain's setting)``
Select ``Airdrop 1 million tokens to the default address (do not use in production)``
select ``No``

 Then it will output ``Successfully created subnet configuration``

To deploy your Subnet, run

``avalanche subnet deploy mySubnet``
 
 Next, select ``Local Network``
 
Now you will need to create a network and your private key account in the metamask with the displayed configurations.

and then execute below things


### Executing program

1. Deploy ERC20.sol first.
2. Then, Deploy the Vault.sol contract with the address of already deployed ERC20 contract.
3. Now mint some tokens and approve them to be transfered to the valut contract by giving it both the addresses and the amount.
4. Now, you can call the deposit and wothdraw functions of the main Vault contract and check them as stated in the contract.
