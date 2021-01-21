---
layout: post
author: Felix Mago
title: Let’s build bridges - Exploring the potential of a wrapped Dash
excerpt: Creating a wrapped Dash is not done overnight, but it seems possible from a technical perspective and promises great potential from a business standpoint. It allows Dash to enter new markets and offers unique opportunities for user.
---
The rise of DeFi, decentralized exchanges, wrapped assets, and increasing interoperability between different protocols brought the Blockchain space closer together in 2020. With Dash Platform coming up, the Masternode network, and a fantastic user base, Dash can profit from these new trends and, vice versa; the Blockchain space can benefit from Dash. An essential first step in this direction is creating a wrapped version of Dash, practically a copy of Dash that can be used on another Blockchain such as Ethereum. This wrap opens a whole new world of use cases, potential users, and partnerships. Dash Incubator is currently exploring the technical feasibility of creating a wrapped version of Dash and the business potential it creates.

!["1960s Advertising - Magazine Ad - Handi Wrap (USA)" by ChowKaiDeng](/assets/image/1960s_Advertising_Magazine_Ad_Handi_Wrap_USA.jpg)

## A shift towards a decentralized world of finance

Decentralized finance (DeFi) has been taking the Blockchain space by storm, promising a new form of financial infrastructure based on free-to-use or plug and play "money legos" that serve as an alternative to the middle-men based legacy banking and financial system.
It is no surprise that DeFi applications and services have attracted massive investments as new decentralized business models are booming, and usage is increasing rapidly. One indicator here is the total value locked ([TVL](https://defipulse.com/)) in DeFi smart contracts. It has risen from less than 700 million USD in January 2020 to over 23 billion USD in January 2021.

In terms of the highest TVL, MakerDAO, the decentralized credit platform, with its DAI stablecoin, has been leading this new market, but others are growing fast. For example, the lending platform Aave offers decentralized loans to users that collateralize their crypto assets or derivatives platform Synthetics, enabling everyone to create synthetic assets easily. Many of these platforms have gained massive attention from media and users. They provide great value propositions - e.g., decentralized DAI vs. centralized USDT, complicated bank loans vs. instant decentralized loans, financial institutions releasing their synthetics vs. everyone creating synthetic public assets.

With all these developments, it is fair to say that the crypto space has made a big step forward as the number of products, services, users, and investments have increased significantly in the last year.

But as most of these applications are built on Ethereum, Dash has not been part of it. While other assets can easily be swapped in a decentralized manner, going from Dash to ETH still requires a third party such as a centralized exchange. An essential requirement to change this is finding a way to list Dash at a decentralized exchange. To do this, Dash would require a wrapped asset, essentially a copy of Dash that has the same value as the original and is usable on another Blockchain, such as Ethereum.

## The age of decentralized exchanges and crypto yields

Among all those many decentralized projects and business models, decentralized exchanges are a crucial enabler. They have been around for many years, but since last year have seen a massive increase in users and transactions. A DEX allows users to switch assets without using any centralized third parties easily. A User simply connects and transfers assets via a Web 3 wallet such as Metamask.

The biggest DEX, Uniswap, [exceeded](https://www.theblockcrypto.com/linked/79775/uniswap-coinbase-monthly-volume-september) Coinbase in trading volume In September 2020. Open access and ease of use are a critical part of Uniswap’s success. Another key reason is its incentive model. Uniswap distributes trading fees to their users, where before, those fees only went in the pockets of centralized exchanges.

To receive those fees, users have to provide liquidity to different pairs in a liquidity pool, e.g., WBTC-ETH, usually in a 50:50 ratio.

The fees generated in those pools are significant. You can find current stats on [Uniswap](https://info.uniswap.org/pairs). For example, on January 12, 2021, the pair WBTC-ETH generated over 170.000 USD in fees within 24 hours, the pair USDC-ETH generated almost 589.000 USD in the same period. Based on the number of funds provided, users share these fees. This example is based on a total pool size of 228 million for WBTC-ETH and 223 million USD for USDC-ETH.

![Screenshot of Uniswap Info, 12.1.2021](/assets/image/Uniswap_fees_Jan_12_2021.jpg)

The promise of high fees on DEX is undoubtedly one factor why many funds are moving on Ethereum-based DEX, but the financial incentives for users go even beyond that. Why? Because in return for providing assets into a liquidity pool, users receive a specific pool token. In the case of Uniswap, this usually is a token with a cryptic name, ending with UNI-V2.

In addition to just holding pool tokens for fees, users are free to do with them as they please. For example, they can participate in various incentive programs that reward users with additional tokens as an incentive. This has become known as yield farming or liquidity mining and has often become a way to launch new projects.

Until November last year, users could, for example, provide ETH-USDT in Uniswap’s own [liquidity mining program](https://www.theblockcrypto.com/linked/84762/dex-uniswap-liquidity-mining-over) and receive extra UNI tokens as a reward. This brought users to Uniswap and affected the tokens in the pool, as both ETH and USDT were essentially locked away in those pools. For ETH and USFT, this increased scarcity and liquidity.

So far, we have seen many similar incentive programs with new ideas coming up regularly. [Yearn.Finance](https://yearn.finance/) vaults are a great example, and they follow a beautifully simple idea. The vaults are pooling user assets and permanently moving them around to where they receive the highest yields.

As seen in those examples, the DeFi movement has created many new ideas that drive projects, users, and adoption. Most of these projects happen on Ethereum, but other assets, such as Bitcoin, are already and massively used on Ethereum in the form of a wrapped copy, e.g., WBTC. So, what are those wrapped assets precisely, and what options exist to create them?

## Different ways to wrap crypto assets

"A wrapped token is an ERC-20 token with a value identical to another asset that it represents, either through a smart contract or by being backed one-to-one with the underlying asset", according to a definition from [Cointelegraph](https://coinmarketcap.com/alexandria/article/what-is-wrapped-bitcoin).

Wrapped tokens solve the issue of trading assets on another Blockchain, e.g., by creating an ERC-20 token from a non ERC-20 asset. The ERC-20 can then be traded on Ethereum and used within Ethereum based applications.

Of course, wrapped tokens cannot create tokens out of nowhere. Instead, every wrapped token minted requires a token taken out on the original chain. Therefore, a key question is how to make sure that the original token really exists and is locked away. The answer is through a custodial solution, and until now, we see a few different options to achieve this.
The first option is by using a centralized custodial service. [WBTC](https://wbtc.network/) is the most prominent example. It uses Swiss custody provider [BitGo](https://www.bitgo.com/). An alternative is a decentralized option that works in a trustless custodial setup. The most famous example here is renBTC, where the original BTC is stored in the [RenVM](https://medium.com/renproject/how-renvm-actually-works-c2f76a2630c4) by decentralized nodes.

Both options have their pros and cons. The way over a regulated, centralized custodial service such as BitGo requires a user to complete AML/KYC with the merchant selling the WBTC. That might scare off some users, but it is a requirement for institutions. Running through such a custodial service also makes it more expensive and time-consuming to switch from one asset to another. It is important to note that once WBTC is minted, a user can transact it freely, e.g., trading on decentralized exchanges. On the other hand, the Ren model works faster and enables dApps to automatically initiate a swap from an asset to its wrapped version.

So far, WBTC has a much larger market capitalization with almost 111,000 BTC wrapped or over 3.8 billion USD, ranking number 13 of all crypto assets. RenBTC ranks on 62 with a market capitalization of over 445 million, which equals almost 12800 BTC.

For Dash, both ways are possible and worth exploring. The consortia based custodial solution requires partnerships, whereas a non-custodial solution involves development.
Moreover, the custodial option requires most likely larger investments. The latter seems to have more flexibility and control. It can be built on Ren and similar models such as [tBTC](https://defipulse.com/blog/what-is-tbtc/) based on a randomly selected group of signers. Dash Incubator is currently exploring the technical feasibility of different options.

## Potential for Dash and the way forward

Creating a wrapped Dash is not done overnight, but it seems possible from a technical perspective and promises great potential from a business standpoint. It allows Dash to enter new markets and offers unique opportunities for users:

- Listings on decentralized exchanges can attract a new group of traders and investors that drive demand and liquidity.
- It gives new arbitrage opportunities that occur from inefficiencies between decentralized exchanges and centralized exchanges.
- Liquidity pools provide users new ways to earn yields on Dash.
- Users can generate their trading pairs vs. Dash.
- Dash can be part of the many DeFi products and services such as yield farms or yield aggregators.
- Lots of new partnerships can be created, especially in the decentralized borrowing and lending space.
- New DeFi products are launching almost every day. For example, we see lots of DeFi banks built on Ethereum, offering a variety of banking and investment services. Only a wrapped version allows Dash to become part of this new movement.
- Dash can be part of decentralized payment networks, leveraging on Dash’s established ecosystem.
- Users or projects can create decentralized Masternode services that transfer rewards back to Ethereum, effectively increasing yield opportunities from DeFi applications.
- Dash in DeFi and every single partnership gives opportunities to create great stories and news value, increasing media attention for Dash.

As Dash Incubator is pushing for adoption and use of Dash Platform cases, we see many possibilities of how a wrapped asset can contribute to our goals. A wrapped asset is just a first but required step to position Dash within the broader Blockchain and Ethereum ecosystem.

Additionally, promoting Dash Platform features across different Blockchain communities can attract new developers, especially since the DAO can fund ideas. Ethereum has apparent shortcomings such as low transaction speed, high transaction and storage costs for decentralized applications.

At the end of the day, we want Dash to be in as many verticals as possible that drive usage, adoption, and creates value propositions for people.

We love to hear your feedback. Please let us know here or on the public [Trello board](https://trello.com/c/rSjuWCp3).

Pictures:
- ["1960s Advertising - Magazine Ad - Handi Wrap (USA)"](https://www.flickr.com/photos/62205794@N00/517261750) by [ChowKaiDeng](https://www.flickr.com/photos/62205794@N00)
- Screenshot of Uniswap Info, 12.1.2021
