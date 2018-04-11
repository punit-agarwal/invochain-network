# invochain-network
Blockchain Application | Trade Network

---

### This is a demonstration of trading in Blockchain.

**Name of network**: invochain-trade

**This business network defines:**

**Participant:** Trader

**Asset:** Commodity

**Transaction(s):** Transaction

**Event:** TradeNotification

---

This business network contains 3 traders
  + Punit Agarwal
  + HR
  + CEO
Each Trader can see only transactions related to his trades and have the ability to trade his products.

This business network also contains 1 regulator
  + CTO
  
Regulator has the ability to view all the trades, performed by each trader.

---
Rules are written in **Permissions.acl**

Access control rules (the language that defines ACLs) fall into two main areas:

    + authority to access system, network or administrative resources and operations in the System namespace (governing Network and System operations) ; and
    + authority to access resources or perform operations within a given business network itself (like Create, Read, Update assets), via domain specific business network ACLs.

+ Participants, Commodities and Transactions are defined in models/trading.cto file.
+ The logic is mentioned in lib/logic.js


To see a working of this, please click [here](https://drive.google.com/open?id=1nEfx5ZhMZ62JhHOQ_fcADsjh-Gb4TgHS)
