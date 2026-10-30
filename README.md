# BeginnerCryptoGuide

A beginner-friendly guide to crypto: what it is, how wallets and exchanges work, what gas fees are, the security basics, and the first steps you can take without getting scammed. No prior knowledge is assumed.

> This guide is educational only, not financial advice. Never invest money you cannot afford to lose, and never share your seed phrase with anyone.

## 1. What is crypto, in plain language

Cryptocurrency is digital money that runs on a public ledger called a **blockchain** instead of a bank's private database.

- A **blockchain** is a shared record of transactions, copied across many computers. Once a transaction is recorded and confirmed, it is very hard to change.
- A **coin** (like BTC or BNB) is the native asset of its own blockchain. A **token** (like many ERC-20 / BEP-20 tokens) is an asset created by a smart contract on someone else's blockchain.
- A **wallet** does not actually "hold" your coins inside your phone. Your coins live on the blockchain; your wallet holds the **keys** that prove you own them and let you move them.

The single most important idea in crypto: **whoever controls the keys controls the coins.** That is why seed-phrase safety matters more than anything else in this guide.

## 2. Wallets: custodial vs non-custodial

### Custodial wallet (an exchange account)
The exchange holds your keys for you. You log in with an email and password, like a bank app.
- Pros: easy to recover if you forget your password; easy to buy and sell.
- Cons: if the exchange is hacked, frozen, or goes bankrupt, your funds can be stuck. "Not your keys, not your coins."

### Non-custodial wallet (your own wallet app)
You hold your own keys, usually as a 12- or 24-word **seed phrase**.
- Pros: nobody can freeze your wallet; you are fully in control.
- Cons: if you lose the seed phrase, nobody can recover your funds for you. There is no "forgot password" button.

**Beginner rule of thumb:** keep small, everyday amounts on a reputable exchange if you must, and learn a non-custodial wallet with small amounts first. Never keep your life savings in a single place you do not fully understand yet.

## 3. Your seed phrase: the one rule that matters most

Your seed phrase is a list of words that can recreate your entire wallet on any device.

- **Write it on paper**, by hand, and store it somewhere safe and private — not in a photo, not in a cloud note, not in an email, not in a chat message.
- **Never type it into a website** that you reached from a link, a DM, or an ad. Real wallets never ask for your seed phrase through a link.
- **Never share it** with "support", a friend, or anyone offering to help recover your account. Anyone who has it can take everything, instantly, and that cannot be undone.
- **Never photograph it.** Photos get backed up to the cloud automatically, and cloud accounts get compromised.

If someone asks for your seed phrase, that is the scam. Stop, close the page, and do not continue.

## 4. Exchanges: buying your first crypto

A typical first purchase looks like this:

1. Create an account on a reputable exchange and turn on two-factor authentication (2FA) with an authenticator app, not SMS alone.
2. Complete identity verification if the exchange requires it.
3. Deposit local currency through the exchange's official deposit method.
4. Buy a small amount first — a test amount — and confirm it arrives before buying more.
5. Learn how to withdraw to your own wallet with a tiny test withdrawal before moving larger amounts.

**Before every withdrawal, check three things, slowly:**
1. The destination address — copy it, do not type it by hand, and compare the first and last characters.
2. The network — sending on the wrong network is one of the most common and most expensive beginner mistakes. The network you choose on the exchange must match the network your receiving wallet supports for that asset.
3. The amount and fee — confirm the fee and the amount that will actually arrive.

Crypto transactions are generally **irreversible**. There is no bank to call to reverse a send to the wrong address.

## 5. Gas fees, explained simply

A **gas fee** is the small payment you make to the network's validators/miners to process your transaction.

- Every blockchain has its own fee token: ETH on Ethereum, BNB on BNB Chain, and so on.
- Fees go up when the network is busy and down when it is quiet. You are paying for computation and network space, not for the exchange.
- A transaction with too little gas can get stuck or fail — and a failed transaction can still cost you gas.
- Always keep a small amount of the network's native coin in your wallet for gas, separate from the tokens you hold. A wallet full of tokens but with zero native coin cannot send anything.

**Practical tip:** before any important transaction, do a tiny test transaction first. A few cents of gas spent on a test is far cheaper than a large amount sent to the wrong place.

## 6. Security basics: the 10 habits

1. Unique, long password for every crypto account. Use a password manager.
2. 2FA with an authenticator app or security key on every exchange and email account.
3. Seed phrase on paper only, stored offline, never photographed or shared.
4. Never log in from a link in an email, DM, or post. Open the app or type the address yourself.
5. Bookmark the real exchange and wallet sites you use, and only use those bookmarks.
6. Check the address, network, and amount before every send — every single time.
7. Start with tiny test amounts for every new wallet, network, or contract.
8. Revoke token approvals you no longer need, and never approve "unlimited" amounts casually.
9. Keep your recovery email secure too — it can reset almost everything else.
10. If something promises guaranteed returns, doubling, or "free money for connecting your wallet", assume it is a scam until proven otherwise.

## 7. Common scams, and how to spot them

| Scam | How it looks | How to avoid it |
|---|---|---|
| Phishing site | A login page identical to the real exchange, reached from a link | Only use bookmarks or the official app |
| Fake support | Someone DMs you offering to "fix" your wallet | Real support never DMs first and never asks for your seed phrase |
| Giveaway / doubling | "Send 1, get 2 back" from a celebrity or exchange account | No legitimate project doubles your money for sending it |
| Fake airdrop | A token appears in your wallet, and its website asks you to connect and "claim" | Do not interact with unknown tokens; connecting can drain your wallet |
| Impersonation | A friend's hacked account sends you a link or asks for a loan in crypto | Verify through another channel before sending anything |
| Fake app | A wallet or exchange app that looks real but steals your keys | Only install from the official store listing linked by the project's own site |

**Rule of thumb:** urgency + a link + a request for your keys, password, or approval = stop. Verify through an independent channel first.

## 8. Your first week: a safe checklist

- [ ] Set up 2FA on your exchange account and on your email.
- [ ] Create a non-custodial wallet and write the seed phrase on paper.
- [ ] Buy a small test amount on an exchange.
- [ ] Withdraw a tiny test amount to your own wallet and confirm it arrives.
- [ ] Send a tiny test amount back, or between your own wallets, and confirm it.
- [ ] Practise checking address, network, and fee before every send.
- [ ] Read one scam example from the table above and explain it to yourself in your own words.

If you can do all of that with small amounts, you understand the mechanics. Only then consider larger amounts — slowly.

## 9. Terms you will keep seeing

- **Address:** your public account identifier, like an account number. Safe to share for receiving.
- **Private key / seed phrase:** your secret proof of ownership. Never share.
- **Gas:** the fee paid to process a transaction on a blockchain.
- **Smart contract:** code on a blockchain that runs automatically when its conditions are met.
- **DEX / CEX:** decentralised exchange (no central company holds your funds) vs centralised exchange (a company does).
- **Slippage:** the difference between the price you expected and the price you actually got, common on DEX swaps.
- **Market cap:** price multiplied by circulating supply — not the same as how much money is "in" a project.
- **Volatility:** how much and how fast a price moves. Crypto is highly volatile; prices can fall sharply and stay down.

## 10. Frequently asked questions

**Is crypto anonymous?**
Mostly no. Most blockchains are pseudonymous: your address is public, even if your name is not attached to it. Transactions can often be traced.

**Can I recover crypto sent to the wrong address?**
Almost always no. That is why test transactions and triple-checking matter so much.

**Should I buy the coin everyone is talking about today?**
Hype is not research. Understand what the project does, who runs it, what the token is actually for, and what could go wrong — before buying, not after.

**Do I need a hardware wallet?**
Not on day one. A hardware wallet is worth considering once the amount you hold would hurt to lose, because it keeps your keys offline. Learn the basics first.

**Is this guide financial advice?**
No. It teaches mechanics and safety. What to buy, when, and how much are decisions only you should make, with money you can afford to lose.

## Next steps

When you are comfortable with this guide, the natural next topics are wallet security in depth, how to read a transaction before signing it, and how decentralised finance works — each covered in its own guide in this collection.
