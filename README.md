# QCoin

QCoin (QCN) is a limited supply cryptocurrency based on the Ethereum blockchain and the ERC-20 standard.

QCoin has three practical functions: 
1. It is a membership token that grants access to the global luxury lifestyle club - QCoinClub. 
1. It stores the QCoinClub membership tier information: 1 QCN = Tier 1 Member, 2 QCN = Tier 2 Member, 3 QCN = Tier 3 Member and so on.
1. QCoin is also tradeable like any other cryptocurrency, with a potential to appreciate in value and become an investment in itself.

# QCoinClub

QCoinClub is a global, members-only luxury lifestyle club backed by QCoin, a tradable ERC-20 token. Club members get access to the most exclusive venues, events, products and experiences that are not available to anyone else. We ensure this, by asking selected top lifestyle brands to design unique experiences exclusively for us.

With the help of our blockchain backed portal we ensure that the services and products offered can be booked and enjoyed only by the QCoin owners. Members are expected to pay the full price for the services in fiat currency. QCoinClub is charging a standard booking fee (also in fiat) for each transaction.

QCoin itself is not considered to be a form of payment for the service provision. It's only a token proving one's membership in the club. But, given the tradable nature of the token, Luxury lifestyle businesses receive a certain amount of QCoin for participation in the project, giving them a stake in the total market value of the QCoin itself and an incentive to join the project.

## QCoinClub Portal

QCoinClub's benefits are facilitated by the electronic booking portal that utilises both Ethereum blockchain as well as traditional web software stack in the backend.

The portal is a main channel of interaction between members, club's staff and service providers. It's also a tool to browse and reserve the luxury services and products available to members.

>> Other functions?

## The membership

The portal uses Ethereum blockchain to authenticate the members (authentication) and also to provide the information about the tier of their membership (authorisation).

In practical terms, to access the system an individual must purchase and transfer QCoin to their non-custodial wallet and then connect the wallet to the portal. The more QCoin an individual holds, the higher the membership tier he/she gets. Individuals with 0 QCN in their wallets are considered non-members and denied access to the portal.

QCoin can be purchased via popular cryptocurrency exchanges on the current market prices, or obtained by other type of exchange, donation, inheritance, etc.

There is no other way of becoming a club member than obtaining at least one QCoin, which is an equivalent of Tier 1 Membership.

## Products, services and third party providers

The services and products (benefits) offered by the platfrom are also tiered, with some available only to the higher tier individuals, while others also enjoyable by the lower tiers.

The physical provision of the member's benefits is carried out by third party companies that are in contract with the club to provide such services. To provide the incentive for third parties to join the network (and design unique experiences for the club), we reserve a pool of QCoin to be used as a reward. The vesting system will be put in place to

## Fees

Providers charge standard fees in fiat currency for the services and products they offer via our portal, while the club charges standard transaction fees (also in fiat currency). The portal uses an on-line payments solution to charge either full value of the product or initial transaction fee, with the remaining value of the product to be settled directly with a provider at the time of provision.

Altough cryptocurrency payments are not currently considered, they are not being ruled-out.

Apart from third party fees and transaction fees, no extra membership payments are charged.

# Team

QCoinClub has been founded by the duo of luxury travel and leisure veterans.

## Bo Dziewierz, CEO

https://www.linkedin.com/in/bdziewierz/

Long term software architect and engineer with a specialisation in web, mobile and application security. 15+ years experience architecting, building and securing multi-tiered, distributed web and mobile applications; 10 years experience with complex, service-oriented architectures; 5 years with microservice based solutions in the cloud; long term DevSecOps, engineering automation and Scrum practitioner.

Hotel Treats, Stayplanner, Eurostar, Travel Intelligence.

DAZN, PwC, Nationwide Building Society, Capgemini,

## Kat Pankowska, COO

https://www.linkedin.com/in/katarzynapankowska/

I work with hoteliers at St. Regis, Nobu, Fairmont, and more to increase their ancillary revenues by enabling them to sell more services (spa treatments, F&B experiences, events, etc.) to local residents, businesses and guests.

I make hotels' unique experiences accessible with a swipe, turn visitors into ambassadors with a tap, and increase TRevPAR with each click.

## ...

# Roadmap

## Development of the platform

## Provider onboarding

## Public airdrop

## Public sale

# Architecture

List Architectural principles
* Simplicity
* Security by design
* Open nature

## Ethereum

## ETH-20

## OpenZeppelin

OpenZeppelin is a de facto standard for implementing many Ethereum standards, including ERC-20. QCoin has been build on-top of OpenZeppelin ERC-20 library to inherit all the industry good-pratices:

* List those good practices.

## Smart Contract

### Contract account

Security of contract account is

### Contract address

### Source Code

## DApp

# Coin governance

By design QCoin has been built as a simple smart contract that only implements the most essential ERC-20 functions. This decision has been made because of the number of design goals:
1. The two practical functions of QCoin token are to authenticate the QCoinClub members and control their membership tiers.
2. The token is tradable on popular exchanges.
3. The token is decentralised, so that it "governs itself" using all the mechanisms that are natively built-in to the blockchain.

Goal no. 1 is ensured by the nature of Ethereum blockchain itself. <Write about which features exactly, link to sources>

Goal no. 2 has been supported by utilising ERC-20 standard. <Write about which features exactly, link to sources>

Goal no. 3 has been achieved by keeping the smart contract as simple and standard as possible. There are no functions in the smart contract, apart from what ERC-20 requires, that would leave the supply, tradability or value of the coin in the hands of a single entity or individual.

## No Minting

QCoin has been preminted to the exact number of 21000000 QCN with 18 decimals. QCoin smart contract doesn't allow minting of more tokens. This decision has been made to quarantee the exclusivity of the QCoinClub and also to ensure a decentralisation of the coin itself. Minting will never be a factor that affects the supply and the market price of the token.

## No Mining

No new QCoins will ever be mined. The supply is exactly 21000000 QCN and that supply has been preminted on the blockchain.

## No Burning

QCoin contract doesn't have any built-in token burning functions. Although "burning" via transferring them to the inactive accounts is still possible due to the very nature of the blockchain itself, the smart contract doesn't support any explicit burn functions.

## Free-Trading

The QCoin is tradabale like other ERC-20 assets. Although initially number of coins will be kept by QCoinClub in a reserved pool to be used as an incentive for service providers to join the club, no restrictions will be introduced to the tradability of the QCoin.

To ensure liquidity, the decision has been made to introduce 18 decimals, so that fractions of QCoin can also be traded.