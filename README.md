
QCoinClub Whitepaper <!-- omit in toc -->
====================

v0.86 (Draft - This is not the final version!)

Author: Bo Dziewierz <bo@qcoinclub.com>

- [1. Abstract](#1-abstract)
- [2. Disclaimer](#2-disclaimer)
- [3. Vision](#3-vision)
- [4. Objectives](#4-objectives)
- [5. QCoinClub](#5-qcoinclub)
  - [5.1. QCoin](#51-qcoin)
  - [5.2. QCoinClubPortal](#52-qcoinclubportal)
  - [5.3. Membership & tiers](#53-membership--tiers)
  - [5.4. Unique products & services](#54-unique-products--services)
  - [5.5. Third-party providers](#55-third-party-providers)
  - [5.6. Fees](#56-fees)
- [6. QCoin token economy](#6-qcoin-token-economy)
  - [6.1. Supply](#61-supply)
  - [6.2. Initial distribution](#62-initial-distribution)
  - [6.3. Liquidity & tradability](#63-liquidity--tradability)
  - [6.4. Governance](#64-governance)
    - [6.4.1. No minting](#641-no-minting)
    - [6.4.2. No mining](#642-no-mining)
    - [6.4.3. No burning](#643-no-burning)
    - [6.4.4. QCoin as a governance token](#644-qcoin-as-a-governance-token)
- [7. Team](#7-team)
  - [7.1. 7.1 Engineering](#71-71-engineering)
  - [7.2. Business entity](#72-business-entity)
- [8. Roadmap](#8-roadmap)
  - [8.1. Release of the QCoin Smart Contract - Aug 2021](#81-release-of-the-qcoin-smart-contract---aug-2021)
  - [8.2. Initial liquidity provision - Sep 2021](#82-initial-liquidity-provision---sep-2021)
  - [8.3. Start of provider onboarding - Sept 2021](#83-start-of-provider-onboarding---sept-2021)
  - [8.4. Release of the QCoinClubPortal v1.0 - Nov 2021](#84-release-of-the-qcoinclubportal-v10---nov-2021)
  - [8.5. Token air-drop - Nov 2021](#85-token-air-drop---nov-2021)
  - [8.6. QCoinClubPortal v2.0 - Jun 2022](#86-qcoinclubportal-v20---jun-2022)
- [9. Architecture](#9-architecture)
  - [9.1. Hybrid Dapp](#91-hybrid-dapp)
  - [9.2. Microservices layer](#92-microservices-layer)
  - [9.3. Smart contract](#93-smart-contract)
  - [9.4. Back-office applications](#94-back-office-applications)

# 1. Abstract

QCoinClub is a members-only luxury lifestyle club and concierge service backed by QCoin (QCN), a tradable Ethereum token.  

Members get access to the most exclusive venues, events, products, and experiences that are not available via other channels. We ensure the uniqueness of the services and products by asking selected top lifestyle brands to design unique experiences exclusively for us.

The service is provided via mobile web application, QCoinClubPortal. Access to the portal is granted only to the club members, and club member privileges are awarded only to holders of at least 100 QCN (Tier 1 membership).

The QCoin token has been preminted to the amount of exactly 21000000 with 18 decimals. It will be initially distributed via air-drop and via Uniswap trading. Separate pools will be reserved for distributions among club service and product providers and as QCoinClub reserve to cover future initiatives.

# 2. Disclaimer

The information shared in this whitepaper is not all-encompassing or comprehensive and does not in any way intend to form a contractual relationship. The primary purpose of this whitepaper is to provide potential club members, club service providers, and other QCoin holders with information that helps in the analysis of the project and making an informed decision before obtaining QCoin.

We strongly advocate a careful study of this whitepaper and all the documents referenced by it. There are risks and uncertainties associated with the QCN token sale and acquisition that should be taken into account. You may want to engage the services of appropriate experts to help you with the decision regarding QCoin.

The QCoin tokens are functional utility tokens designed for use only on the QCoinClubPortal and other QCoinClub software products that are yet to be developed. 

The tokens are not securities. In the event that you purchase QCoin, your purchase cannot be refunded or exchanged. Tokens do not entitle you to any equity, governance, voting, or similar right or entitlement in the QCoinClub, Flisacka Sp. z o. o. or in any of its affiliated companies.
# 3. Vision
 
Our vision is to establish the one and only, truly global, borderless, luxury lifestyle club and concierge service for the World's top percentile.

# 4. Objectives

We have set out to achieve the following set of objectives that support our vision:

1. Global
2. Borderless
3. Decentralized
4. Private and anonymous
5. Luxury
# 5. QCoinClub

QCoinClub is the embodiment of our vision: a global, members-only luxury lifestyle club and concierge service backed by the Ethereum blockchain. Through the club, members get access to the unique concierge service and exclusive venues, events, products and experiences that are not available via other channels.
## 5.1. QCoin

QCoin (QCN) is a utility cryptocurrency implemented on the Ethereum blockchain using the ERC-20 standard. It's a backbone of the QCoinClub that enables us to meet our key objectives. To do so it leverages the key capabilties of ERC-20 and Ethereum: 
* cross-border membership transferability, 
* decentralised exchange that doesn't require any third party to act as an intermediary
* pseudonymity of parties in the network.

In practice, QCoin has three main functions for club members and stakeholders:

1. It is a membership token that authenticates members and authorizes access to QCoinClub's benefits.
2. It stores the QCoinClub membership tier information.
3. It is also tradeable in a trustless and pseudonymous manner, with the potential to appreciate in value and become an investment in itself.

Aditionally, given the tradable nature of the token (and the fact it can appreciate in value), Luxury lifestyle businesses receive a certain amount of QCoin for participation in the project, giving them a stake in the total market value of the QCoin itself and an incentive to join the project. Businesses can also participate in the QCN/ETH Liquidity Pools, further benefiting from the exchange fees.

Please note, that altough intially the QCoin will not be used as a payment instrument, we do not rule out that in the future such option will be available.
## 5.2. QCoinClubPortal

QCoinClub's benefits and services are facilitated by the electronic portal utilizing both Ethereum blockchain as well as traditional web software stack in the backend. The portal is the main channel of interaction between members, club staff, and service providers. It's also a tool to browse and reserve the luxury services and products available to members.

The development of the portal is ongoing, with each subsequent iteration providing a certain number of new features, improvements, and bug fixes. The long-term aim is to open the development roadmap as much as possible to the club members, whereby it's the members who decide on the priority of work. The governance of this model is to be further discussed and developed.

## 5.3. Membership & tiers

The QCoinClubPortal uses Ethereum wallets to authenticate the members and also to provide information about the tier of their membership. In practical terms, to access the system an individual must acquire and transfer QCoin to their non-custodial wallet and then connect the wallet to the portal. The more QCoin an individual holds, the higher the membership tier he/she gets. Individuals with 0 QCN in their wallets are considered non-members and denied access to the portal.

QCoin can be purchased via popular cryptocurrency exchanges on the current market prices or obtained via the air-drop, or by another type of exchange, donation, etc.

The following membership tiering system has been put in place:
| Min. QCN | Tier |
| --- | --- |
| 1000 | 1 |
| 2000 | 2 |
| 5000 | 3 |
| 10000 | 4 |
| 20000 | 5 |
| 50000 | 6 |
| 100000 | 7 |
| 200000 | 8 | 
| 500000 | 9 | 
| 1000000 | 10 | 

There is no other way of becoming a club member than obtaining at least one thousand QCoin, which is equivalent to Tier 1 Membership.

## 5.4. Unique products & services 

The services, products and other benefits offered by the club via the portal are also tiered, with some available only to the higher tier individuals, while others also enjoyable by the lower tiers. 

To ensure the membership in the club has a certain exclusive value, we take extra care to make products and services unique to the QCoinClub and not available via other channels.

The product types offered by the club include, but are not limited to:
* skip-the-line entry to exclusive golf clubs, night clubs, social clubs, etc,
* VIP places at cultural and sports events,
* private concerts,
* private celebrity events,
* pre-launch access to luxury fashion products,
* Michelin-star and gourmet dining,
* 5-star superior accommodation,
* personal health and wellbeing,
* personal coaching and training,
* personal shopping,
* luxury interior design services for homes, yachts, jets, etc,
* privately commissioned art and music,
* private travel advisory,
* general concierge services.

## 5.5. Third-party providers

The physical provision of the products and services is carried out by third-party companies that are in contract with the club to provide such services. During the onboarding process, we ask selected top lifestyle brands to design unique experiences exclusively for us.

To incentivize third parties to join the network (and design unique experiences for the club), we reserve a pool of QCoin to be used as a reward. Third parties are rewarded one-off amount of QCoin from this pool, giving them a stake in the total market value of the QCoin itself. This also enables them to particpate in the Liquidity Pools for QCN/ETH pair that contributes extra income from owning the coin.

The vesting mechanism is in place to ensure coins are released in stages after a certain amount of value is delivered by the third-party provider.

Ongoing development of the benefits offered is ensured. The long-term aim is to open this process as much as possible to the club members, whereby it's the members who decide on the type of services and products that are offered. The governance of this model is to be further discussed and developed.

## 5.6. Fees

Providers charge their standard fees in fiat currency for the services and products they offer via the club, while the club charges standard transaction fees (also in fiat currency). The portal uses an on-line payments solution to charge either the full value of the product or the initial transaction fee, with the remaining value of the product to be settled directly with a provider at the time of provision.

Apart from third-party fees and transaction fees, no extra membership payments are charged.

Please note, that although cryptocurrency payments are not being considered for initial launch, they are not being ruled out and are indeed an option for the future.

# 6. QCoin token economy

## 6.1. Supply

The total supply of the QCoin is set to be exactly 21000000 (21 mln) with 18 decimals.

## 6.2. Initial distribution

The initial supply of QCoin has been divided into number of pools, each with a specific purpose:

| Pool | Purpose |
| --- | --- |
| 1000000 | Initial liqudity pool to facilitate public trading on Uniswap with an initial 3 years developer lock. |
| 20000000 | Pool used for third party supplier onboarding, air-drops, expanding liquidity pools, etc. |
## 6.3. Liquidity & tradability

The QCoin is tradabale like other ERC-20 assets. Although initially a number of coins will be kept by the club in a reserved pool to be used as an incentive for service providers, no restrictions will be introduced to the tradability of the QCoin.

The coin is traded on Uniswap. Initial pool of 1000000 is to be reserved as the Liquidity Pool to start trading. The inital price of the QCoin has been set to 0.000001 ETH per token. LP token will be time locked for 3 years initially.
## 6.4. Governance

QCoin's Smart Contract implements only the most essential ERC-20 functions. This has been decided to meet the key design goals for the QCoin token: 
1. QCoin is a membership token of a utility nature used only to authorize access to the QCoinClubPortal
2. QCoin is freely tradable
3. QCoin is decentralized

As a result, there are no functions in the smart contract, apart from what ERC-20 requires, that would leave the supply, tradability or value of the coin in the hands of a single entity or individual.

### 6.4.1. No minting

QCoin has been preminted to the exact amount of 21000000 QCN with 18 decimals. QCoin smart contract doesn't allow minting of any more tokens. This decision has been made to guarantee the exclusivity of the QCoinClub and also to ensure the decentralization of the coin itself. Minting will never be a factor that affects the supply and the market price of the token.

### 6.4.2. No mining

No new QCoins will ever be mined. The supply is exactly 21000000 QCN and that supply is preminted on the blockchain.

### 6.4.3. No burning

QCoin contract doesn't have any built-in token burning functions. Although "burning" via transferring them to inactive accounts is still possible due to the very nature of the blockchain itself, the smart contract doesn't support any explicit burn functions.

### 6.4.4. QCoin as a governance token

QCoin is not a security. As such, it does not guarantee equity, co-ownership, vote, nor any governing power over QCoinClub, Flisacka Sp. z o. o., nor any other company or stakeholder in the QCoinClub project. Instead, it's a membership token of a utility nature that is used to authenticate and authorize club members to access club services and products.

# 7. Team

QCoinClub has been founded by a team of luxury travel and leisure veterans with current luxury travel and lifestyle business experience.

## 7.1. 7.1 Engineering
Bo Dziewierz - https://www.linkedin.com/in/bdziewierz/

The team is growing and this whitepaper will be updated in the next versions to reflect that.

## 7.2. Business entity

The business entity managing QCoinClub is Flisacka Sp.z o. o., a limited company registered in Poland under KRS number 0000883803

# 8. Roadmap

## 8.1. Release of the QCoin Smart Contract - Aug 2021
ERC-20 Smart Contract released on Ethereum MainNet.

## 8.2. Initial liquidity provision - Sep 2021

Initial Liquidity Pool will be established on Uniswap with 3 years LP lock
## 8.3. Start of provider onboarding - Sept 2021

Provider onboarding starts in August 2021 and continue indefinitely. The roadmap for provider onboarding is as follows:  

* We onboard 10 luxury lifestyle businesses by the end of December 2021, offering three unique products each in US and UK target markets.
* 25 providers onboarded by Feb 2022
* 75 - Jun 2022
* 200 - Dec 2022
## 8.4. Release of the QCoinClubPortal v1.0 - Nov 2021

The development of the QCoinClubPortal starts in August 2021. The first production release of the software (v1.0) is to become available to all QCoin holders by the end of Nov 2021.

## 8.5. Token air-drop - Nov 2021

The first QCoin air-drop is to start in November 2021.

The aim of the air-drop is to build an initial community of QCoinClubPortal users and also boost the social media presence of the product. To maximize the impact and effectiveness of the air-drop, it is to be targeted so that only selected parties will be entitled to participate.
## 8.6. QCoinClubPortal v2.0 - Jun 2022

The next major version QCoinclubPortal is released starting an ongoing release cycle. New releases to include features and improvements developed to answer the future needs of QCoinClub members.
# 9. Architecture

QCoinClub's architecture consists of a number of high-level architectural components:
## 9.1. Hybrid Dapp

QCoinClubPortal is a member front-end, architected in a "hybrid DApp" model. It means that although it is built as a traditional centralized web application, it does have elements that interact directly (via web3) and rely on decentralized Smart Contracts running on Ethereum blockchain.

## 9.2. Microservices layer

The microservices layer provides a set of centralized services for the QCoinClubPortal front-end. The web application communicates with the microservices via the RESTful API interface using GraphQL. 

The microservices layer provides the following functionality (among others):
* Content provision & categorisation
* Content personalisation
* Search
* Session management
* Payments
* Bookings
* Order fulfillment
  
Microservices are deployed in the AWS cloud leveraging serverless technology and other cloud-native services.
## 9.3. Smart contract

QCoin is a standard ERC-20 smart contract deployed on Ethereum blockchain. It has been built using OpenZeppelin Contracts library, a de facto standard for implementing many Ethereum contract types, including ERC-20. OpenZeppelin helps to reduce the risk of vulnerabilities by providing battle-tested, community reviews code.

QCoinClubPortal front-end communicates with the smart contract via web3 libraries and a set of helper technologies, including WalletConnect and Infura.

Working in conjunction with standard capabilities of Ethereum blockchain QCoin smart contract implements two key uses cases for QCoinClub members. It provides authentication by means of Etherum wallet connectivity (WalletConnect) and authorization by providing the membership tier bound to the amount of QCoin held in the wallet.
## 9.4. Back-office applications

QCoinClub will also include a number of back-office business applications, including a Content Management System (CMS), Order Management System (OMS), Business Information System (BI/MI), etc.
