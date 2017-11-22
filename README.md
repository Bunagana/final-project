# BlockChain Developer Decal Final Project: LoQuorum

## What is LoQuorum

LoQuorum is an application that will tackle a fundamental problem when it comes to crowdfund local development project around the world. The idea behind LoQuorum is to empower local communities to get united to solve issues that they are facing.

## Why LoQuorum

In many parts of the world, central governments tend to not be efficient in the way the handle problems that are far away from where the government resides (i.e. capital cities). Thus, when a bridge collapse in a small locality of Ivory Coast local communities can fund a project that will repair the bridge. Moreover, LoQuorum can also be used to fund projects done by non-profit around the World. For instance, a US resident may want to help with the funding of the construction of a school in Uganda or helping organization that are fighting against “modern slavery” in India.

Right now, www.purecharity.com is one of the leading crowdfunding platform when it comes to the funding of humanitarian non-profit organizations. LoQuorum will make it easy for people who may not want to share their financial information with organization such as purecharity.org to participate. Moreover, because all the transaction will be configured in contracts on the Ethereum block-chain, the system will be almost self-regulated and thus will function with low cost. The decentralization brings two things: the first one is the security of donors and the second one the frictionless nature of transactions. Non-profit and communities can instantly receive the funds provided by donors.

### Accountability

Project managers who are asking for fund will have to provide a roadmap of the steps of their projects. If the project is not fully executed donators should be able to recover their fund. Thus, LoQuorum has at least two contracts beside the token contract.

1.    The first contract has the funding logic.
2.    The second contract is a voting contract where donators grades the evolution of the project they donated to. If 55% of donators are unsatisfied, the voting contract will change the state of the funding contract by allowing withdrawals. The voting power is calculated by how much each address donated.

Moreover, non-profit organizations are only allowed to have access to the funding required for each step. In order to access the next level funding, donators have to vote.


## Project Design

LoQuorum has three main contracts that interact with each other.

1.    The crowdfunding Contract.
This contract behaves like a crowd-sale contract.

2.    The Token Contract
ERC-20 contract that stores information regarding stakeholders.

3.    The Accountability Contract
This contract sets in place the logic of a voting contract. Donors have the vote in order to allow the funding of each step.










