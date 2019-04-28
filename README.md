# PHBS_BlockChain_2018
As if to further testify humans’ infinite affection for cats, in late 2017, CryptoKitties, an Ethereum-based kitty-breeding game enchanted so many people in just a few days after its launch that it once clogged the Ethereum network and delayed the processing of transactions. The hype about CryptoKitties introduced many into the realm of Blockchain and presented another possibility of Blockchain application: digital assets as non-fungible tokens (NFTs), used for people’s collecting proclivity. However, all the hype over this brand-new game waned gradually, posing question on whether this application of Ethereum can sustain any longer. 

Therefore, in this business review, I would investigate this business in detail, and also look at non-fungible tokens at large. 

## CrypoKitties: An Overview
On the official website, the project of CryptoKitties is defined in such sentences: “In CryptoKitties, users collect and breed oh-so-adorable creatures that we call CryptoKitties! Each kitty has a unique genome that defines its appearance and traits. Players can breed their kitties to create new furry friends and unlock rare [cattributes] (https://www.cryptokitties.co/about)”. The users do not actually have any CrypoKitties in physical form but only “own” the token in the blockchain. And unlike cryptocurrencies that have identical units, each CryptoKitty is unique to the owner and its uniqueness is where it got its value from. Besides, CryptoKitties is an active community in which users can create new collectibles and trade them with each other on Ethereum.

At launch, 50,000 “Gen 0” cats (also known as “Clock Cats”) are stored in a smart contract on the Ethereum blockchain. Every fifteen minutes, a cat would be distributed through smart contract, and each of those cats are sold by auction.

## Genes
Each CryptoKitty is one of a kind, with a distinct look (phenotype) determined by its immutable genes (genotype) stored in the smart contract. The “cattributes” include base color, highlight color, accent color, mouth, fur, pattern, eye shape, eye color, wild, environment, secret and purrstige, which together would make any cat distinct from one another. As the below graph shows, the “cattributes” are determined by a cat’s genome, which contains a series of blocks each with four genes. Among them, three are hidden genes (H1, H2, H3) and one is primary (P). When two cats breed, the primary gene has a 75% chance of being passed on and the hidden genes 25%. Within the three hidden genes, they also have a different probability of being passed down, depending on the rank of the gene. Therefore, that is one of the most exciting parts about breeding: the owners could find two cats they favor and deliberately breed an offspring with desired traits. It is said that the smart contracts have over 4-billion variations of phenotypes and genotypes.

![Cattributes](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/1.png)
![Cattributes](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/2.png)

## Mutation
However, a new-born kitty might have traits that are not inherited from either of the parents. That is when genetic mutation happens. Two genes that partner together would have the chance to cause a specific mutation, and having two purebred kitties would have a higher likelihood of such mutation, which explains the high price of purebred species. The concept of mutation sure adds a lot of fun to CrytpoKitties.
![Mutation](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/3.png)
![Mutation](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/4.png)

## Family Jewels
In addition, there’s the concept called “Family Jewels”, [which are rewarded to the first Kitties to discover Mewtations (new Cattributes), and those jewels may be inherited by their descendants](https://guide.cryptokitties.co/guide/cat-features/family-jewels). Depending on how early a kitty discovers such Mewtation, different types jewels are rewarded (Diamond, Gilded, Amethyst, Lapis). Also, the kitty’s descendants would have the opportunity to claim the jewels as well if they share the identical cattribute. 

![Family Jewels](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/5.png)

To further enhance the sense of peculiarity and exclusivity, CryptoKitties creates several types of special digital cats apart from normal cats: Fancy Cats, Exclusive Cats and Special Edition Cats. [Fancy Cats are a series of special cats identified by their unique artwork and badge](https://guide.cryptokitties.co/guide/types-of-cats/fancy-cats).
* Fancy Cats have a unique recipe of breeding that requires rigorous analysis and experimentation, and has a time limit of creation. 
![Fancy Cats](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/6.png)
* Exclusive Cats are a similar concept, but much rarer: it often come out to celebrate an event or serve a purpose. It cannot be bred by two existing kitties, but rather directly comes into being by the game developers’ overwriting of an existent kitty.
![Exclusive Cats](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/7.png)
* [Special Edition Kitties](https://guide.cryptokitties.co/guide/types-of-cats/special-edition-cats)  are cats with special artwork that are released for sale for in a limited quantity. Similar to Exclusive Cats, they have unique art, but they are more in number.
![Exclusive Cats](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/8.png)

## Basic Operations in CryptoKitties
The basic actions of CryptoKitties are buying, offer, breeding, selling or siring.
* Buying: A buyer can go to the public market and directly buy a cat from others
* Offer: A buyer can make a bid in ETH for any cat to its owner, who can choose to either decline or accept the bid.
* Breeding: Breeding demands either two kitties of your own or a public sire you choose to breed your cat with. Normally, a user would breed cats of the identical generation and the descendent cat’s generation would be the higher generation of the parent kitties plus one.
* Selling or Siring: A user can either sell the cat of her own or offer the kitty onto the public market for other users’ cats to breed with.

## Gas and Fees Requirements in CryptoKitties
What’s the “Blockchain” aspect of CrytpoKitties? One of the key mechanisms that ensure the game’s decentralized validity of transactions is gas and fees on the Ethereum network. Whenever a user conducts or simply cancels one of the actions we summarized above, her request is sent to the Ethereum network with miners figuring out the numbers and verifying the transactions. Once a new transaction gets validated, the Tx fee would go to the miners as a reward. The Tx fee is essentially determined by two things: gas price and the amount of gas used.

Gas price’s basic unit is Gwei, which is 10^-9 ether, and gas limit sets the ceiling for the computational power allowed for the miners. So, the maximum possible fee for a single transaction is simply multiplying gas price by gas limit. The reasonable gas price varies across different users: if she wants her transaction to get processed in a shorter amount of time, she would set a higher gas price. If setting gas limit too low, it is likely that a transaction cannot get through. Thus, it is suggested by CrypoKitties that users make use of the service by ETH Gas Station to set up the right gas price and that users follow recommended gas limit by MetaMask.

## Value of CryptoKitties
As digital collectibles, CryptoKitties also have varying values, so how is their value determined? In general, there are three aspects to consider when valuing a specific cryptokitty: rarity, utility and appearance, which reveal the motivation for people to buy and sell those cats. 
### 1. Rarity
First, low generation kitties, especially those Gen 0 cats are rare, as it was ordained in the white paper that only 50000 such cats would ever be created, which is also guaranteed by Blockchain. Second, those Fancy, Exclusive, Special Edition Cats have special value of their own. Third, as each cat would be granted an ID number in an ascending order, the lower ID cats would have higher value as they were created earlier. Fourth, sometimes developers release cats with some artwork mistakes, and those unintended flaws would be corrected shortly, so those “glitch” kittens will be of high value.
### 2. Utility
The value of CryptoKitties also come from its usefulness. A cat is useful for its quick “cooldown” speed – how fast a cat can breed another offspring after giving birth to one. Normally, a cat with low generation number has a faster cooldown speed, and the more it breeds, the more time it needs for cooldown. Also, purebred cats – cats with four identical genes for any block of “cattribute”, are valuable because they have a higher chance of breeding offspring with mutations.
### 3. Appearance
The most intuitive aspect of a cat’s value is its look. Users would pay a lot for a cat if it looks extremely good, ugly or just eccentric. Some traits such as colors, eyes and mouth, jewels, and even name are usually under the consideration of buyers. As people don’t always concur on aesthetics, this part of value determination is mostly subjective.
### 4. Sample Cats with High Value
So, how high are people willing to pay for a CryptoKitty? A [website](https://kittysales.herokuapp.com/) contains the purchase price of each kitty transaction and we can easily find out the most expensive cat transactions that ever existed. 

* On top of the list is [Dragon](https://www.cryptokitties.co/kitty/896775) sold for 600 ETH on September 4, 2018, which equals $172625.79 USD at time of [sale](https://etherscan.io/tx/0x09bd9357d29bef46a68a6ffdc915304288d69ca089412a2edec0c8d370b3944b). This ridiculously high transaction price has stirred many speculation that this might be [money laundering](https://www.reddit.com/r/ethtrader/comments/9cvze1/a_cryptokitties_cat_has_sold_for_600_eth/) in disguise, as on the face value the traded kitten has nothing particularly compelling, even though it got a fancy name and some jewels.	It may also simply be used as a swap of ETH between two parties with not too much additional value.
![Dragon](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/9.png)
* The second most expensive cat is [Founder Cat #18](https://www.cryptokitties.co/kitty/18) traded for 253.33 ETH on December 7, 2017. It is special for being one of the 50000 genesis cats without any parent, and it also looks adorable to many for having a pair of round innocent eyes.
![Founder Cat #18](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/10.png)
* The third most expensive purchase involves [Fluffy Founder](https://www.cryptokitties.co/kitty/4) traded for 247 ETH on December 7, 2017 as well. Its value comes from being one of the founding cats and also its Fluffy tail and a wise man’s eyebrows which appear for the first time among all cats.
![Fluffy Founder](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/11.png)

## Revenue Model and Business Advantages
CryptoKitties generates revenue by charging 3.75% of each transaction on the marketplace. Also, it receives revenue from sales of cats, which are limited to the 50000 cats predetermined in the white paper.

As the developers are clearly aware of the lack of knowledge of users, they adopt concise and clear layout and streamline the actions as straightforward as possible. They also choose a universally beloved animal – cat as the core subject, with colorful palettes, glamorous attributes (“cattributes”) and cheeky description. Beyond Blockchain experts, their target market is actually the general public, which is much different from its peer companies at time of initiation. As smart contract codes cannot be changed after launch, they carefully test CryptoKitties’ mechanics before officially setting it off.

Unlike non-Blockchain collectibles, CryptoKitties’s greatest advantage is that it does not have any central authority, whose existence would be a prerequisite for the collectibles’ value in non-Blockchain platforms. Also, as collectibles’ value largely depends on rarity and peculiarity, a central authority might not refrain from issuing more and more collectibles, diluting the value of current outstanding assets, while CryptoKitties does not have this problem at all because the supply is predetermined in the smart contract.

## The Underlying Protocol - ERC 721 and Non-Fungible Tokens (NFTs)
The whole project of CryptoKitties is based upon an Ethereum protocol [ERC 721](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md). This protocol is a standard interface for non-fungible tokens, which can be defined as “unique representations of goods or assets that take the form of digital tokens”, and “through the use of cryptography, NFTs can prove the authenticity, as well as ownership of such assets and goods” (NFT.nyc). And “tokens” are actually a set of crypto assets: according to Tasca, crypto assets can be classified into native coins and crypto tokens. Native coins are a kind of alterative coins to existing currencies like Bitcoin, whereas crypto tokens are coins embedded with some intrinsic values linked to specific asset, service and benefits. NFTs can be used for “securing digital ownership, protecting intellectual property, tracking digital assets and overall creating real world value” (NFT.nyc). They can even go beyond digital to represent physical property like houses and unique artwork. 

Besides CrytoKitties, there are a lot of existing NFT games as well, such as [Decentraland](https://decentraland.org/) in which users buy and sell scarce digital lands and [Gods Unchained](https://godsunchained.com/), a crypto trading card game. And apart from games, there are already a dynamic NFT application landscape which can be seen in the following graph made by Point Nine Capital.
![Landscape](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/12.png)
Also, [this website](https://forum.nftgecko.com/t/list-of-all-non-fungible-token-projects/65) provides a list of existing NFT projects.

## Evolution of CrytoKitties’ Popularity
CryptoKitties was an instant hit: on December 5, 2017, just one week after its launch, it had roughly 60k registered users, 100k existing cats, 5M USD in transactions processed and made up for 25% of the Ethereum traffic. In January 2018, it hits 250,000 users and one month later it has more than 500 thousand cats on the network. Later in March, it received [VC funding](https://www.coindesk.com/a16z-leads-12-million-funding-for-ethereum-app-cryptokitties) of $12M from Andreessen Horowitz and Union Square Ventures 

December 2017 was when people were most obsessed with CryptoKitties. In the below graph by [Bloxy](https://bloxy.info/token_stat/0x06012c8cf97bead5deae237070f9587f8e7a266d), it can be seen that CryptoKitties’ transfer amount peaked in December 2017 and has become relatively stable at 200,000 ever since.

![Token Amount](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/13.png)

A lot of [media](http://fortune.com/2018/06/18/cryptokitties/) dismiss this swift decline in popularity as a bubble burst and this whole idea of NFT would fail. However, a closer look at the data would give us another story. The below two graphs shows that after the December frenzy in 2017, the transaction volume has been stable while more NFT applications appear on the market and are gaining a substantial amount of user base. This is an indication that people do not lose interest in collectibles and NFTs, but rather have become mature in their transactions and flock to a wider variety of NFT services, with the pure onlookers leaving the platform.

![Transaction Volume](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/14.png)
![User Base](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/15.png)

Also, Google Trends tells us that the search interest in “cryptokitties” has not gone through that much of a decline after December 2017 and this search term is still relevant today. Interestingly, Google Trends also shows that China is the country with the most search interest in CrypoKitties.

![Google Trends](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/17.png)

As people’s interest in NFTs still persists, what can be the future for NFTs? This would be discussed in the next section.

## The Future of NFTs
CryptoKitties has cleared a completely new path for Ethereum developers. Even though CrypoKitties might not restore the glorious public hype in its first months after launch, NFT application will persist and has further development besides collectibles and gaming we have been discussing. NFTs are an efficient and reliable way of keeping and verifying people’s properties and qualifications that are unique and exclusively owned by themselves, whether digital or physical.
* NFTs can be applied to tickets as each ticket can now be verified and free of frauds without a central authority. A notable such usage has been brought up by [Crypto Tickets](https://crypto.tickets/). 
* NFTs can be used to as identity and certificates. National IDs, passports, driving licenses, contracts and patents can all be tokenized and NFTs can provide authentication and certification.
* NFTs can be used as a tool for charity and donation as well. [CryptoCare] (https://cryptocare.tech) is a pioneering platform that enables donations in ether and gives out a corresponding collectible to the donor if they commit to a cause listed on the platform.
* NFTs can serve as licenses that verify certification like CFA for any individual, without a central authority to manage bookkeeping or provide authentication.
* NFTs enable artists to tokenize their music, artwork that cannot be tampered with or legally infringed.
* NFTs would make car sales easy and reduce redundant intermediate transactions. Second-hand car purchases can be as simple as giving out ether and receive tokens on the Ethereum network, without need for trust or a centralized platform.

We can witness the evolution of transaction volume and active addresses of NFTs in the following two graphs. Even though transactions of ether have cooled down a lot for the whole 2018, NFTs have seen a slightly upward trend in both of the indicators. 

![Transaction Volume NFTs](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/18.png)
![Addresses](https://github.com/shepardzhang/PHBS_BlockChain_2018/blob/master/Pictures/19.png)

However, as the white paper of CryptoKitties contends, two issues are still impeding the real success of Non-Fungible Tokens and all other Blockchain applications: the public’s lack of knowledge of Blockchain technologies and their mistrust sewn by abuses of ICO. They result in a shortfall of real meaningful innovations. In order for CryptoKitties and NFT projects to become real success, developers and businesspeople need to think of real solutions to promote this technology and engage a wider public.
