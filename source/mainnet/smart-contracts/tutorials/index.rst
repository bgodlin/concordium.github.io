.. include:: ../../variables.rst
.. _sc-tutorials:

==========
Tutorials
==========

You can go through a number of different tutorials to sharpen your skills as
a dApp (decentralized application) developer on the Concordium blockchain.

In :ref:`Setup the developer enviroment <setup-env>` you learn how to set up the development enviroment for working with smart contracts.

In the :ref:`Counter <counter-sc>` tutorial, you are going to build a simple smart contract with a counter that can be increased or decreased and where only the owner can perform the operations.

In the :ref:`piggy bank <piggy-bank>` tutorial, you are going to build a simple smart contract modelling a piggy bank.
It should allow any account to insert CCD and only the owner to smash it, taking all of the CCD inside.

In the :ref:`wCCD <wCCD>` tutorial, you are going to get familiar with the deployed wCCD token on testnet.
You are going to write a basic web frontend example that can read from and write to the deployed wCCD smart contract on testnet.

In the :ref:`Voting<voting-dapp>` tutorial, you learn how to create a smart contract and dApp to conduct a vote.

In the :ref:`NFT Minting <nft-index>` tutorial you will mint and transfer non-fungible tokens. The :ref:`Semi-fungible tokens<sft-index>` tutorial describes how to mint and transfer semi-fungible tokens. And the :ref:`Fungible tokens<ft-index>` tutorial explains how to mint, transfer, and burn fungible tokens.

In the :ref:`NFT marketplace <nft-marketplace-index>` tutorials you will setup an NFT marketplace.

In the :ref:`eSealing <eSealing>` tutorial, you are going to learn how to seal a document, so you can prove that it was in your possession at the time of sealing.
You will use a front end and the |bw| to register the file hash of a selected document in a smart contract and then
display the timestamp and the sealer from an already time-stamped document at the front end.

In the :ref:`sponsored Transactions <sponsoredTransactions>` tutorial, you will explore how to sign a
message in the |bw| (or |mw-gen2| that uses WalletConnect) and how to send the signature to a backend.
You will then instruct the backend to submit the transaction on behalf of the user on-chain.

In the :ref:`Smart Contract Upgrade <intro-smart-contract-upgrade>` tutorial you will deploy a smart contract and upgrade its logic. During the upgrade, you will call a migration function to change the shape of the state.

Once you are familiar with smart contracts, it is a good idea to read the :ref:`Smart contracts best practices<sc-best-practices>`.

.. toctree::
   :maxdepth: 1
   :hidden:

   setup-env
   Counter <./counter/counter-contract>
   PiggyBank <./piggy-bank/index>
   wCCD <./wCCD/index>
   voting/index
   nft-minting/index
   sft-minting/index
   fungible-tokens/index
   nft-marketplace/index
   eSealing <./eSealing/index>
   Sponsored Transactions <./sponsoredTransactions/index>
   Smart Contract Upgrade <./smartContractUpgrade/index>
