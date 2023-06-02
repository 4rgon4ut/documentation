---
description: Security is the first priority of the Gnosis team, bug bounty program
keywords: [gnosis security, gnosis bounty, bug bounty program, gnosis immunefi]
---

# Bug Bounty

## Immunefi Bug Bounty

Bounties are an important tool for testing and enhancing application and contract security. We appreciate the skilled hackers and programmers within the community and believe in rewarding those working to protect and strengthen the ecosystem. Working in partnership with [Immunefi](https://immunefi.com/),  we will be releasing additional bounties in the near future, and invite the community to help identify any possible exploits we may have missed.

Security is the #1 priority of the Gnosis team. This bounty program is not being enacted in response to any know exploits, we are proactively implementing to ensure safety and soundness of our applications and protect users and their funds.

There are two ongoing bug bounty programs: [Bridges bug bounty](https://immunefi.com/bounty/gnosischain/) and [web/app bug bounty](https://immunefi.com/bounty/gnosischainwebapp/).

Each bug bounty program requires different assets in scope and both offer rewards determined by thread level.

## Web/app Bounty
### Asset in scope

Assets in scopes includes Gnosis Chain documentation, forum, lock, RPC, beacon chain explorer, checkpoint, and block explorer.

Only the following assets in the table are considered. If an impact can be caused to any other asset managed by Gnosis that isn’t on this table but for which the impact is in the Impacts in Scope section below, you are encouraged to submit it for the consideration by the project. This only applies for Critical impacts.

For specific assets, only specific thread level bug reports may be submitted.

| Type | Target | Only High/Critical severity |
| --- | --- | --- |
| Websites and Applications - Doc (Gnosis Chain) | http://docs.gnosis.io | ✅ All level |
| Websites and Applications - Forum (Gnosis Chain) | http://forum.gnosis.io | ⚠️High |
| Websites and Applications - Lock (Gnosis Chain) | http://lock.gnosis.io | ✅ All level |
| Websites and Applications - RPC GBC (Chiado Testnet) | http://rpc-gbc.chiadochain.net | ✅ All level |
| Websites and Applications - RPC (Chiado Testnet) | http://rpc.chiadochain.net | ✅ All level |
| Websites and Applications - RPC (Gnosis Chain) | http://rpc.gnosischain.com | ✅ All level |
| Websites and Applications - RPC GBC (Gnosis Chain) | http://rpc-gbc.gnosischain.com | ✅ All level |
| Websites and Applications - RPC (Bicocca) | http://rpc.bicoccachain.net | ✅ All level |
| Websites and Applications - Beacon (Chiado Testnet) | http://beacon.chiadochain.net | 🆘 Critical |
| Websites and Applications - Blockscout (Chiado Testnet) | http://blockscout.chiadochain.net | 🆘 Critical |
| Websites and Applications - Checkpoint (Gnosis Chain) | http://checkpoint.gnosischain.com | 🆘 Critical |
| Websites and Applications - Beacon (Gnosis Chain) | http://beacon.gnosischain.com | 🆘 Critical |
| Websites and Applications - Explorer (Bicocca) | http://blockscout.bicoccachain.net | 🆘 Critical |

### Reward by Thread Level

Rewards are distributed according to the impact of the vulnerability based on the [Immunefi Vulnerability Severity Classification System v2.2.](https://immunefi.com/immunefi-vulnerability-severity-classification-system-v2-2/)

| Impact | Reward |
| --- | --- |
| Critical* | USD $15,000 to USD $50,000 |
| High* | USD $10,000 to USD $15,000 |
| Medium | USD $5,000 |
| Low | USD $1,500 |

*All Critical and High web/app vulnerabilities are scaled based on internally established team criteria, taking into account the exploitability of the bug, the impact it causes, the report quality (at the discretion of the team), and the likelihood of the vulnerability presenting itself, which is especially factored in with bug reports requiring multiple conditions to be met that are currently not in place. However, there is a minimum reward of USD 10 000 for High impact web/app impact vulnerabilities and USD 15 000 for Critical web/app impact vulnerabilities. Rewards will be provided at the determined fair value by the team depending on these conditions, assuming that the bug report is in-scope of the bug bounty program.

All web/app bug reports must come with a PoC with an end-effect impacting an asset-in-scope in order to be considered for a reward.

Only the following impacts in scope are accepted within this bug bounty program.

| Impact | Scope |
| --- | --- |
| Critical | Execute arbitrary system commands |
| Critical | Retrieve sensitive data/files from a running server such as /etc/shadow, database passwords, and blockchain keys(this does not include non-sensitive environment variables, open source code, or usernames) |
| Critical | Taking down the application/website |
| Critical | Taking state-modifying authenticated actions (with or without blockchain state interaction) on behalf of other users without any interaction by that user, such as, changing registration information, commenting, voting, making trades, withdrawals, etc. |
| Critical | Direct theft of user funds |
| Critical | Malicious interactions with an already-connected wallet such as modifying transaction arguments or parameters, substituting contract addresses, submitting malicious transactions |
| Critical | Injection of malicious HTML or XSS through NFT metadata |
| High | Injecting/modifying the static content on the target application without Javascript (Persistent) such as HTML injection without Javascript, replacing existing text with arbitrary text, arbitrary file uploads, etc. |
| High | Changing sensitive details of other users (including modifying browser local storage) without already-connected wallet interaction and with up to one click of user interaction, such as email or password of the victim, etc. |
| High | Subdomain takeover with already-connected wallet interaction |
| Medium | Changing non-sensitive details of other users (including modifying browser local storage) without already-connected wallet interaction and with up to one click of user interaction, such as changing the first/last name of user, or en/disabling notification |
| Medium | Injecting/modifying the static content on the target application without Javascript (Reflected) such as reflected HTML injection or loading external site data |
| Medium | Redirecting users to malicious websites (Open Redirect) |
| Low | Changing details of other users (including modifying browser local storage) without already-connected wallet interaction and with significant user interaction such as iframing leading to modifying the backend/browser state (demonstrate impact with PoC) |
| Low | Any impact involving a publicly released CVE (demonstrate impact with PoC) |
| Low | Temporarily disabling user to access target site, such as locking up the victim from login, cookie bombing, etc. |

### Out of scope & Rules

**The following vulnerabilities are excluded from the rewards for this bug
bounty program:**

- Attacks that the reporter has already exploited themselves, leading to damage
- Attacks requiring access to leaked keys/credentials
- Attacks requiring access to privileged addresses (governance, strategist)
- Incorrect data supplied by third party oracles
    - Not to exclude oracle manipulation/flash loan attacks
- Basic economic governance attacks (e.g. 51% attack)
- Lack of liquidity
- Best practice critiques
- Sybil attacks

**The following activities are prohibited by bug bounty program:**

- Any testing with mainnet or public testnet contracts; all testing should be
done on private testnets
- Any testing with pricing oracles or third party smart contracts
- Attempting phishing or other social engineering attacks against our employees
and/or customers
- Any testing with third party systems and applications (e.g. browser
extensions) as well as websites (e.g. SSO providers, advertising networks)
- Any denial of service attacks
- Automated testing of services that generates significant amounts of traffic
- Public disclosure of an unpatched vulnerability in an embargoed bounty

Please visit [Immunefi bounty page](
https://immunefi.com/bounty/gnosischainwebapp/) for more details.

Tweet: https://twitter.com/gnosischain/status/1651285327125053440



## Bridge(Omnibridge, xDAI Bridge) Bounty

### Asset in scope

All smart contract bug from Gnosis Chain Bridges includes ETH-xDAI Omnibridge, xDAI bridge, BSC-xDAI Omnibridge.

| Type | Target |
| --- | --- |
| Smart Contract - DAI-xDAI TokenBridge contract on the Ethereum Mainnet | https://etherscan.io/address/0x4aa42145Aa6Ebf72e164C9bBC74fbD3788045016 |
| Smart Contract - DAI-xDAI OmniBridge contract on the Gnosis chain | https://blockscout.com/xdai/mainnet/address/0x7301CFA0e1756B71869E93d4e4Dca5c7d0eb0AA6 |
| Smart Contract - ETH-xDAI OmniBridge contract on the Ethereum Mainnet | https://etherscan.io/address/0x88ad09518695c6c3712AC10a214bE5109a655671 |
| Smart Contract - ETH-xDAI OmniBridge contract on the Gnosis chain | https://blockscout.com/xdai/mainnet/address/0xf6A78083ca3e2a662D6dd1703c939c8aCE2e268d |
| Smart Contract - BSC-xDAI OmniBridge contract on the Binance Smart Chain | https://bscscan.com/address/0xf0b456250dc9990662a6f25808cc74a6d1131ea9 |
| Smart Contract - BSC-xDAI OmniBridge contract on the Gnosis chain | https://blockscout.com/xdai/mainnet/address/0x59447362798334d3485c64D1e4870Fde2DDC0d75|
|  |  |

### Reward by Thread level

The quantity of rewards awarded are based on the [Immunefi Vulnerability Severity Classification System V2.2](https://immunefi.com/immunefi-vulnerability-severity-classification-system-v2-2).

All smart contract bug reports must come with a PoC with an end-effect impacting an asset-in-scope in order to be considered for a reward.

Only the following smart contract impacts are accepted within this bug bounty program:

|  Smart Contract Impact | Reward |
| --- | --- |
| Critical* | Up to USD 2,000,000 |
| High | USD $10,000 |
| Medium | USD $1,000 |

*All Critical smart contract vulnerabilities are further capped at 10% of economic damage, primarily taking into consideration the funds at risk. However, there is a minimum reward of **USD 50 000**.

Payouts are handled by the Gnosis Chain team directly and are denominated in USD. However, payouts are done in USDT for payments up to USD 100 000. All remaining rewards are paid in STAKE.

### Out of scope & Rules

**The following vulnerabilities are excluded from the rewards for this bug bounty program:**

- Attacks that the reporter has already exploited themselves, leading to damage
- Attacks requiring access to leaked keys/credentials
- Attacks requiring access to privileged addresses (governance, strategist)
- Incorrect data supplied by third party oracles
    - Not to exclude oracle manipulation/flash loan attacks
- Basic economic governance attacks (e.g. 51% attack)
- Lack of liquidity
- Best practice critiques
- Sybil attacks

**The following activities are prohibited by bug bounty program:**

- Any testing with mainnet or public testnet contracts; all testing should be done on private testnets
- Any testing with pricing oracles or third party smart contracts
- Attempting phishing or other social engineering attacks against our employees and/or customers
- Any testing with third party systems and applications (e.g. browser extensions) as well as websites (e.g. SSO providers, advertising networks)
- Any denial of service attacks
- Automated testing of services that generates significant amounts of traffic
- Public disclosure of an unpatched vulnerability in an embargoed bounty

Please visit [Immunefi bounty page](https://immunefi.com/bounty/gnosischain/) for more details.

More info -> [https://medium.com/immunefi/xdai-stake-hosts-2-000-000-bug-bounty-on-immunefi-3760e0687616](https://medium.com/immunefi/xdai-stake-hosts-2-000-000-bug-bounty-on-immunefi-3760e0687616)



## What’s next?

- [Submit a bug](https://bugs.immunefi.com/)
- Any questions about the program? Reach out to us in our [Discord](https://discord.gg/gnosischain) channel!

## FAQ

1. Is the bug bounty program is time limited?    
    No.
    
2. How to submit a bug on Immunefi?      
    https://medium.com/immunefi/a-hackers-guide-to-submitting-bugs-on-immunefi-1e6b7ada71a9
