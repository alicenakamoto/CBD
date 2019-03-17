NAME: Introducing curved bonded derivatives


Abstract 
In this article, we are proposing a cryptoeconomic primitive that makes it possible to invest in any entity represented by a unique identifier (e.g. an URL) with an automated market maker in a trustless way.

Background 
As Hayek has argued, markets are an efficient way to aggregate information that is distributed among individuals within a society (Hayek, 1945). By using prices as signals the limited knowledge of individuals can be gathered and used to allocate resources efficiently.

Currently, access to markets where individual knowledge is applied for profit generation, such as the stock market, is very limited and restricted to a global elite. This leaves crucial information blindspots, inter alia of individuals in high potential growth areas like developing countries.

The cryptoeconomic revolution introduced more inclusive investment mechanisms like initial coin offerings. The creation of tradable digital assets was extremely simplified but is still restricted to knowledgeable technicians or people who can afford them. Another problem is illiquidity, while the creation of a cryptoeconomic asset is fairly simple, creating a liquid market for less known assets is hard.

An old idea currently revisited with the use of decentralised blockchain technology is prediction markets. They present an accessible opportunity for individuals to gain value through their knowledge. Prediction markets make it easy to place bets on the outcome of events, but the entry barrier is relatively high. Agents must specify a certain date and a precise outcome of a performance indicator form a credible source while relying on a decentralised jurisdictional system for disputes. An even bigger problem might be market making. It is often hard to find a counterparty that takes a bet, especially for unpopular events. These challenges make prediction markets also imperfect investment vehicles.

While we are living in a knowledge economy, the economic instruments to make use of individual knowledge are very limited to certain areas and restricted to a few people.
The potential to coordinate global information and allocate resources in a more efficient way is desperately needed, especially in high growth areas like developing countries, where access to financial instruments is particularly scarce.
We believe that new cryptoeconomic investment instruments can be used for information coordination. They will be the “killer application” for blockchain technology in the short term future.

Introducing Curve Bonded Derivatives
In response to the above-stated challenges of inclusive financial instruments for information coordination, we are proposing a new cryptoeconomic primitive, the Curve Bonded Derivative (CBD). CBDs address two particular issues:

CBDs make it possible to invest in any entity by using a unique identifier as a representation for that entity. 
CBDs provide instant liquidity through an automated market maker and reduce prediction signals to a binary input.


Bonding curves
A bonding curve is a cryptoeconomic instrument, first introduced to enable curation markets that “..allows groups to more effectively coordinate & earn from value they co-create around shared goals.” (Simon de la Rouviere, 2017).

The important attributes of curved bonding are:

Agents can buy or sell a token through a smart contract at any time.
The price is determined by the supply of the token and predefined in the contract. 

This function, the relationship between price and supply, can be represented by a rising graph. 



The price increases with the supply of the token. That's why we speak of curved bonding.

The advantage of bonding curves is instant liquidity. The smart contract functions as an automatic market maker and allows agents to buy and sell their shares at any time. 

While curved bonding is mostly used for the issuance of tokenised assets we propose to use curved bonding for the issuance of derivatives representing digital or real-world entities.

The derivative obtains its value from the performance of an underlying entity. We suggest using URLs as unique identifiers to represent these entities.
The derivative will not be directly connected to any performance indicator. The price will only change accordingly to the demand of the derivative that represents the real world entity.

To illustrate the relationship between the derivative and the real-world entity we can look at a distant relative, the trading (collectible) card. A trading card usually contains an image of a person or thing along with a short description. Baseball cards are especially well-known. The value of a trading card mainly depends on the subject's popularity and the scarcity of the card.

Similar to trading cards the price of the CBD will also depend on the popularity and scarcity of the entity it represents while having no direct connection to performance indicators.

In order to bet that an entity will increase in relevance in the future, agents can buy stakes in URLs representing this entity on CBD registry contracts. They can also sell the stake at any time when they believe relevance will decrease.
Use cases 
Example use case:
Alice learns about a new project, she is really excited about and believes that this project has a bright future. She visits her favourite CBD registry and enters the URL of the project. If the project wasn’t yet registered she can register it herself, as such she is investing in the project. She invests 100$ and gets 200 tokens.
A year later the internet is really buzzing about this project and many more people buy tokens after Alice while fewer people sell. Alice checks her investment again and she is pleased to see that the price for one token increased to a 1000$. She sells 20 token and already made a significant profit through her knowledge, while still holding a small stake.
Real world use cases:
Crowdfunding:
Current crowdfunding models like Kickstarter or ICOs have lengthy setup times and their illiquidity makes them very inconvenient for investors. Curve bonded derivatives have the potential to make it easier to crowdfund projects. 
Alice has an idea for a new app so she writes a prototype on GitHub, explains it in an article and registers the repository URL through a CBD registry. She can now invest in the URL and send it out to friends and like-minded peers. If they like the idea they will also invest in it. After more people invested in the project, Alice can sell some of her initial investment to a higher price and use the money to start working on the project.
Articles:
Currently, there is no easy way to invest in ideas, but CBDs could make this possible. Online articles could be registered through their URLs and people would now have the possibility to signal how strong they believe in the future value of the expressed ideas. Writers could register and invest in their articles after publishing them and earn money with their ideas too. 
Music:
Music could be an enabler for mainstream adoption of CDBs. Currently, there is no way to invest in an artist or song, while the internet is full of passionate fans that predict the future success of their favourite artists. CBDs could enable a market where fans can bet on the future success of their favourite artist or song. This could prove to be a more efficient way to enable discovery of lesser-known artists than current models. Like in the above-mentioned cases CBDs could also be a way for musicians to finance their projects.


Challenges

While CBDs make it very easy to invest in any entity, this makes them also very susceptible to attacks like pump and dump schemes. Attackers could buy a big stake in a CBD, promote it heavily and then sell it to a premium. This can obviously be very dangerous for inexperienced investors. Instruments to make these attacks less likely will need to be developed. 

Short selling for Bonding Curves could help to prevent assets from rising to irrational highs (Fang Gong 2019). Decentralised reputation systems for investors could also be a way to mitigate the risk.

We believe in open information markets. Patronising people by censoring their ability to invest through central entities might prevent them from losses in the short term but hurts our society in the long term. Everybody has unique knowledge and only by creating instruments to access this knowledge we can advance in a globally efficient way.

Conclusion
Current financial instruments exclude important parts of the global population and are restricted to a limited selection of assets, they thereby only enable very incomplete information markets. 

Curve Bonded Derivatives could create universal and liquid markets for information: 

By making all entities that can be represented by a unique identifier, feasible for investment.
By creating liquidity through curved bonding and enabling instant market making for these entities.

The internet is a base layer communications network, through which we can exchange information almost instantly. But we are missing a global language to evaluate information: ideas, projects and real-world entities, to allocate capital accordingly.


Additional Notes

Technical Primer to build bonding curves in solidity (Slava Balasanov, 2018).

This article will be continuously improved, feedback is much appreciated.

If you are interested in helping us to build a CBD Registry or giving us feedback join our telegram channel or write us on Twitter: https://twitter.com/AliceNakamoto, https://twitter.com/moritzfelipe
