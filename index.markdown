---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

| Project | Date | Value At Risk | Unpaid Amount | Description | Details | 
| --- | --- | --- | --- | --- | --- |
|  Arbitrum   |  Sep 2022   |  352,000 ETH   |  1200 ETH   |  [A compromised deposit contract allowed theft of all incoming deposits.](https://medium.com/@0xriptide/hackers-in-arbitrums-inbox-ca23272641a2)   |  The largest deposit during bug bounty negotiation was 351,803 ETH. The max bounty for a critical vulnerability was advertised as $2mm. The white hat was only awarded 25% of the max bounty (400 ETH).   | 
|  Aave   |  Nov 2022   |  $40M ($1.5M stolen)   |  $250K   |  CRV economic exploit  |  An attacker targeted Aave's treasury using an economic exploit of CRV borrowing/lending on the protocol. The white hat showed Aave the wallet, the attack path, and how to stop it days before the attack occurred. Over $40m was at risk. [$1.5m was actually taken from the exploit, which was stopped midway by private individuals leading a short squeeze.](https://cointelegraph.com/news/aave-purchases-2-7m-crv-to-clear-bad-debt-following-failed-eisenberg-attack)  Aave paid no bug bounty.   |
|  dHEDGE    |  April 2023   | $14.44M   |  $25K   |   Managers can steal tokens from users using malicious swap paths.  |  [dHEDGE responded that the issue is "well-known" and that it is impossible to fix.  They did not fix the issue and paid a $500 payment for "goodwill".](https://mirror.xyz/0x6746Cae57DA75D77137f7749582f511B4d9f866c/fU6YVrXulTL5z5qMraVTDJmnUiPP8NH17XGzDJLvq1k)  |
|   Magic Link  | May 2023    | ~$10M  |  $3000   | [Iframe Phishing](https://twitter.com/NanakNihal/status/1684301807885996033) | Magic Link claims their wallet to be unphishable. Yet it was found to be vulnerable to iframe phishing, more pernicious than standard phishing as there is no URL bar. Magic Link ignored the vulnerability after eight reminders over a month-long period until it began receiving public scrutiny about the presence of a potential unknown vulnerability. The whitehat suggested a payment of more than $3000 and Magic Link ignored the hacker, paid nothing, and publicly announced its patch as a "new security feature" and their "investment in security" rather than an unpaid whitehat's finding. |
|   Magic Link  | April 2023    | ~$20M  |  $2000   | [Clickjacking can drain wallets](https://twitter.com/NanakNihal/status/1684301807885996033) | All user funds, which are here estimated to be above $20M, were at risk, with minimal user interaction needed to steal them. Magic Link's max bounty is $3000. Magic Link paid $1000, falsely claiming it is not critical because it needs a dashboard misconfiguration or XSS to be exploited (it needs neither). Magic Link refused to coordinate a timeline to fix it for months until this issue received more public scrutiny; at that point, they fixed it in days. |
|  unitaryHACK    |  June 2023   | $100   |  $100 |   They don't pay you for the completed bounties  |  [unitaryHACK stopped responding to the emails asking for the payment to be made.](https://unitaryhack.dev/hackers/rum1887/)  |
|     |     |     |     |     |     |
|     |     |     |     |     |     |
|     |     |     |     |     |     |
|     |     |     |     |     |     |
|     |     |     |     |     |     |
|     |     |     |     |     |     |
