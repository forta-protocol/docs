
Welcome to the Forta Network! We’re excited you’re here. 

The Forta Network monitors on-chain activity in real-time, detecting threats, security-related events and other noteworthy activity. The network is made up of thousands of detection bots developed by a community of Web3 developers and security experts. Each bot acts like a little security camera monitoring something specific on-chain. Some bots monitor generic threats (i.e. phishing attacks, rug pulls), and others monitor protocol-specific activity (i.e. Lido, Compound).

The output from all this monitoring and detection is what we call _threat intelligence_ - data that tells you the “who, what, when, where and how” about threats and security events.   

There are two primary actors in the Forta Network:

* **Users**, who consume threat intel generated by the network. Users could be Web3 wallets, DeFi protocols, or centralized exchanges looking for the latest threat intel to protect their customers.  
* **Developers**, who create and maintain detection bots. They could be a leading Web3 security team, an independent security researcher or a DeFi core dev using Forta to monitor their protocol. 

### **Users**

Users can access threat intel generated by any bot on the network. Certain bots the community feels are particularly high value have been packaged up into _Premium Feeds_, like the Scam Detector. Premium Feeds are owned and maintained by one or more reputable community members (teams and/or individuals) and must meet certain requirements for performance and precision. The price for each Premium Feed is set by the owner. Intel from the other bots on the network can be accessed under the network’s General subscription plan option.

You can see all the Premium Feeds &lt;here>. You can also browse the 1,000+ other bots on the network [here](https://app.forta.network/).

Intel from Premium Feeds and individual bots can be accessed either through Forta’s GraphQL API (pull) or by subscribing to a bot directly (push) to receive notifications via email, Slack, or Telegram, among other options. Purchasing one or more network subscriptions allows you to access both options. 

### **Developers**

Developers can use a suite of tools to build new detection bots. 



* **Build Detection Bots with the SDK:** Use the flexible Forta SDK to develop customized Detection Bots for your monitoring needs. [Get started here.](https://docs.forta.network/en/latest/getting-started/) 

* **Build Detection Bots with the Bot Wizard**: Create and deploy a Detection Bot through a UI, no code required. [Learn how to create your custom bot.](https://docs.forta.network/en/latest/wizard/) 

* **Want to outsource your bot development?** Get connected to community members with experience developing custom bots. Reach out to [andy@forta.org](mailto:andy@forta.org) for more details.



**Introduction**

The Forta Network acts like a giant, shared security camera and alarm system, monitoring public blockchains in real-time for threats, anomalies, security-related events and other noteworthy activity. Put differently, Forta is the “real-time monitoring layer” in the Web3 tech stack. The Network is comprised of two primary components - _detection bots_ and _scan nodes_. 


[**Forta Network Metrics Dashboard**](https://dune.com/rodri_forta/forta-network-metrics) 


_Detection Bots_

Detection bots are the equivalent of tiny cameras, built by developers and published on the network. What each bot monitors for is determined by the logic written by its developer. Bots vary in complexity, with some monitoring for a single condition (ex: a multi-sig transaction above a certain amount threshold), and others monitoring for a combination of different factors (ex: scam activity using a combination of advanced heuristics and machine learning models). When a bot finds what it’s looking for, it emits an alert. 

To prevent spam and malicious bots from being published and consuming network resources, developers are required to stake at least 100 FORT on each detection bot they publish. Bots without the minimum stake will be inactive. 

_Scan Nodes_

The other component of the network is scan nodes, and you can think of scan nodes as servers that provide capacity to the Forta Network. Scan nodes are responsible for running detection bots, providing them with blockchain data and publishing any alerts. 

Anyone can run a scan node as long as they stake the required amount of FORT tokens. Each scan node listens for blocks and transactions from a blockchain. Currently, the Forta Network runs scan nodes for EVM blockchains such as Ethereum, Polygon and BNB Chain (complete list of supported chains [here](https://app.forta.network/network)). Each scan node is assigned a set of detection bots to run by the Forta Network. 

When a new bot is published, it is randomly assigned to one or more scan nodes and begins running shortly thereafter. The scan node collects any alerts reported by the detection bots and publishes them.

To hold scan node operators accountable for operating in the best interest of the network, each scan node must be staked with at least 2,500 FORT. 

_Network Intelligence_

Collectively, the detection bots on the Forta Network are generating hundreds of thousands of alerts and other data points every hour. Users can subscribe to alerts from a specific detection bot using the [Forta App](https://app.forta.network/). They can also browse and search the latest alerts using the [Forta App](https://app.forta.network/alerts). Also, more technical users can query for alerts using the [Forta API](https://docs.forta.network/en/latest/api/) to integrate alert feeds right into their own applications.
