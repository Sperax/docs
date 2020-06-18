# Welcome to the Sperax Documentation # 


This site is for anyone who wants to learn about Sperax. Go to: 

> 1.0 [What Is Sperax](#what-is-sperax) <br/>
> 2.0 [Why Sperax BDLS](#why-sperax-bdls) <br/>
> 3.0 [Token Economy](#token-economy) <br/>
> 4.0 [Keep Up With Sperax](#keep-up-with-sperax) <br/>
> ### You are also welcome to read our [academic publications](docs/Paper/). ###


## 1.0 ## 
## What Is Sperax ## 

While the global economy is being severely impacted by the coronavirus crisis, **Sperax**, a Silicon Valley-based blockchain company, is aiming to build a trusted infrastructure for a decentralized economy that may provide far greater efficiency, flexibility and self-governance than the traditional economic model.

***Sperax provides a layer of financial services within the public blockchain stack through a native stablecoin and decentralized financial service providers.***

At the infrastructure layer, we developed **BDLS protocol**, which is an innovative consensus module that is more secure and efficient than other Byzantine Fault Tolerant protocols. On top of it, we introduced **Sperax stable coin** system. It is backed by fiat currency and is the first native stablecoin in public blockchain ecosystem. Developers could build decentralised applications without worrying about educating users about cryptocurrency. 

- For developer update, please check out [here](https://godoc.org/github.com/Sperax/bdls). 
- For Whiterpaper, please check out [here](https://sperax.io/speraxWhite.pdf). 

## 2.0 ## 
## Why Sperax BDLS: ## 
We make decentralized financial services accessible to all global citizens. 

| Problems In Designing A Secure PoS Blockchain                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Discover Sperax BDLS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Hard to ensure unpredictability & verifiable fairness of node identity** <br/> <br/> In a PoS based consensus protocol, validators are selected to generate or vote for new blocks based on whether they satisfy certain conditions. These conditions are generally determined by the coins each node controls on the network. It is important to ensure the fairness of selection. However, though quantities like future block hashes, block difficulty, or timestamps seem to be ideal sources of randomness on chain, they are vulnerable to manipulation by miners.  | **Secure and Unpredictable random beacon or RANDAO** <br/> <br/> RANDAO not only has the characteristics of unpredictability, but it is also more accessible and provably fair. RANDAO’s protocol adopts a commit-reveal process that presents a joint random number, generated from the random strings committed by various participants in a given window of time. After a user gets this shared random number via RANDAO, one can then generate his/her own random number via some hash function.                                                                                         |
| **Hard to design a secure protocol in the open internet Environment** <br/><br/> Most current BDLS protocols apply the gossip-based broadcast protocol, based on the existence of reliable peer-to-peer communication channels, for any pair of participants one might select. This requirement is generally equivalent to a complete network topology that only exists in closed environments. This assumption is definitely not the case in more realistic scenarios on the open Internet where we interact. Open networks are particularly susceptible to DoS attacks.    | **Security design in the type II partial synchronous networks** <br/><br/> Among partially synchronous networks, there are two widely accepted main types, illustrated  here . In the type II network, a realistic one, Denial of Service (DoS) attacks are allowed and no reliable broadcast channels are assumed before GST. We may assume that the network alternates between good and bad synchronous periods. SperaxBDLS adopts block-lock mechanisms & block self-proof mechanisms to ensure security against such potential forks, proving liveness and safety of the BDLS protocol. |
|**Hard to handle the problem of deadlock in a partial sync network** <br/><br/> Liveness guarantees that all the nodes eventually agree on some value and move on. However, in the realistic network, many attacks can be launched in the format where a malicious leader sends different messages to different nodes. Some popular BDLS protocols may reach deadlock when the network is partially sync. This deadlock is not resolved when the network regains synchronization because their liveness is not robust enough to survive in a realistic Internet environment. | **High efficiency consensus algorithm design** <br/> <br/> Scalability is one angle to evaluate blockchain systems. Another way is to understand the complexity of the messages passed. Although in general the performance of PoS consensus varies with the implementation, it can also be evaluated on the order of O(n2). In terms of the communication processes in SperaxBDLS however, there are only two unicast and two broadcast processes, with a O(4n) message complexity, which contributes to a linear consensus efficiency.                                                     |
## 3.0 ##
## Token Economy ##
The common practice for constructing a public blockchain stack is to build up the Layer 1 chain and then develop decentralised applications on top of it. There are technologies that help to facilitate more optimal network transactions (Layer 0). There are scalability and privacy solutions added to a public blockchain system to enhance performance and reduce cost (Layer 2).

***In order to enable a truly decentralised economic ecosystem and incentivise developers to join, Sperax issued two tokens - SPA and stable coin.***

| **SPA**                                                                                                                                                                                                                      | **sCOIN**                                                                                                                                                                                                                 |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SPA is the native utility token for the Sperax blockchain. It fuels the ecosystem and reflects the value of the network. SPA also grants token holders the right to participate in the governance process in the system. | Sperax stable coin sCOIN is a fiat-pegged stablecoin issued on the Sperax blockchain. It is also the first native stablecoin in the ecosystem. Sperax stable coin could lower the barrier of blockchain adoption for users. |

### Use Cases ###

- Payment Systems

> Sperax offers a global payment system based on stablecoins. Since it is based on a single currency, Sperax stablecoin could be used in respective markets to fulfill the need for payment similar to credit cards or mobile-based payment solutions. We work with payment gateways and merchants for the infrastructure so that SST could be more widely accepted. 


- Global remittance and transfer

> Sperax stablecoin network could support fast global transfers at a low cost. In designing the Sperax stablecoin network, we took into account the best practices of the current global currency transfer processes and leveraged on the features of blockchain technology to reduce the time and cost. Liquidity service providers act like the money transfer companies in our stablecoin network. 


- Decentralised financial services 

> Financial applications can build on our infrastructure. All the single-currency stablecoins are also issued on chain; considering that Sperax blockchain is compatible with the Ethereum Virtual Machine, a lot of the decentralised financial applications could also be supported by the Sperax stablecoin system. Sperax Foundation will build the first group of protocols to support basic currency features such as compound interest, lending and borrowing, token swaps etc. More complex financial products could be added by developers.

## 4.0 ##
## Keep Up With Sperax:##
- Website: https://sperax.io/
- Telegram: https://t.me/sperax
- Medium: https://medium.com/sperax
- Twitter: https://twitter.com/sperax_io
- Facebook: https://www.facebook.com/sperax/?ref=bookmarks
- LinkedIn: https://www.linkedin.com/company/sperax/?viewAsMember=true
- Contact：Gerry Wu | +1 857 218 9711 | gerry@sperax.io | contact@sperax.io



