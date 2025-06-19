#  Morsy: Boundless Prover and Dev Role Guide

get instantly Boundless Guild roles (`Dev`, `Prover`, or both)

Before running the script, **make sure you have**:

- A **GitHub account older than 6 months**
- A **Discord account older than 6 months**
- A **Burner EVM wallet**

## Prerequisites

You can run this in local pc/laptop or any vps
system requirements:
atleast 4GB of memory
atleast 10GB of SSD


Go to **https://guild.xyz/boundless-xyz**
Connect your **MetaMask wallet**
What you can do is relink a burner wallet in your guild, just to claim role later you can switch back to your main wallet


**If you are visitng first time**
Connect A Burner Wallet
Link your **Discord** and **GitHub** accounts
Create an **Alchemy Base Mainnet RPC URL**

   - Go to [https://www.alchemy.com/](https://www.alchemy.com/)
   - Create a new app for **Base Mainnet**
   - Copy your RPC URL (Format: `https://base-mainnet.g.alchemy.com/v2/YOUR_API_KEY`)

---

## Required Balances

| Role | Requirements |
|------|--------------|
| Prover | `10 USDC` on base chain and $1-2 ETH On Base Chain |
| Dev    | `0.000001 ETH` on base chain and $1-2 ETH On Base|
| Both   | `10 USDC + 0.000001 ETH` and $1-2 ETH for fees both on base chain |

---

## ⚙️ Installation Steps

### 1. Connect to your server ( skip this step if you running on local pc/laptop )

```bash
ssh root@your-server-ip

```

2. Install dependencies
```
sudo apt update && sudo apt install -y curl git
```
3. Download and run the script
```
bash <(curl -s https://raw.githubusercontent.com/morsyxbt/boundless-prover-dev/main/boundless-prover.sh)
```
be patient, it may take some time


---

now enter your:

alchemy Base RPC URL

your wallet private key (input will be hidden)

your selected role: 1, 2, or click 3 if you need both

it will check your wallet balance

then automatically submit the transaction(s)



---

✅ After Successful Attempt

You will see a confirmation message like:

✅ GUILD QUEST COMPLETED!
🎉 Welcome to the Boundless Network!

Then go back to:

https://guild.xyz/boundless-xyz
…to complete and verify the rest of your Guild role quests.


---
