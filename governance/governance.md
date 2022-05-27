# Governance

### Tracer DAO

Tracer is governed Tracer DAO, which empowers governors (people or stakeholders that own governance tokens) to decide on changes to the protocol from anywhere in the world without a point of central control. Tracer DAO uses democratic voting to keep decisions fair and all its rules are open – they can be seen in the governance contract [here](https://github.com/tracer-protocol/tracer-dao/blob/master/contracts/MultisigDAOUpgradeable.sol).&#x20;

Tracer DAO owns the Factory contracts and their market templates. It can change these, and some tracers (only the markets that specify DAO control), through a vote. A vote can also change the governance contract if the governors choose a new voting system or want to update some of the rules.&#x20;

To have their say on [proposals](https://snapshot.org/#/tracer.eth), governors use governance tokens to vote on the proposals that other members make to the rest of the DAO.

{% hint style="success" %}
View the DAO contract on [Etherscan](https://etherscan.io/address/0xa84918f3280d488eb3369cb713ec53ce386b6cba) or search by address: 0xA84918F3280d488EB3369Cb713Ec53cE386b6cBa
{% endhint %}

### Governance Tools

[**Discord**](https://discord.gg/peMMwVV6m2) **** allows the community to freely discuss protocol improvements. In some cases, Discord discussions lead to the drafting of system proposals on Discourse.&#x20;

****[**Discourse**](https://discourse.tracer.finance/) **** allows anyone to draft proposals for the community to review and express sentiment through polls. This is where community consensus is gauged, before voting occurs on Snapshot.&#x20;

****[**Snapshot**](https://snapshot.org/#/tracer.eth) is a “gasless” off-chain multi-governance client that allows Tracer DAO governors to vote on proposals without paying gas fees. Proposal consensus is then pushed on-chain via a Gnosis Safe multi-sig.&#x20;

[**Gnosis Safe**](https://gnosis-safe.io/) is used by trusted members to relay proposal consensus from Snapshot on-chain via a multi-sig.&#x20;
