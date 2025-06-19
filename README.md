# 🧩Boundless Prover and Dev Role Guide

Get Boundless Guild Roles (`Dev`, `Prover`, or both) Instantly
Before running the script **make sure you have**

**GitHub Account Older Than 6 Months**
**Discord Account Older Than 6 Months**
**Burner EVM Wallet**

## Prerequisites
you can run this in
local pc, laptop or any vps

## System Requirements
atleast 4GB of memory
atleast 10GB of SSD

## Now Follow the steps

go to **https://guild.xyz/boundless-xyz**
connect your **Main EVM Wallet**

**Note**
add a secondary burner wallet in your guild just to claim role
don't remove the primary ( main ) wallet

now link your **discord** and **gitHub**

create an **Alchemy Base Mainnet RPC URL**
- go to [https://www.alchemy.com/](https://www.alchemy.com/)
- create a new app for **Base Mainnet**
- copy your RPC URL (Format: `https://base-mainnet.g.alchemy.com/v2/YOUR_API_KEY`)

---

## Required Balances

| Role | Requirements |
|--------|--------------|
| Prover | `10 USDC` + gas fee |
| Dev    | `0.000001 ETH` + gas fee |
| Both   | `10 USDC + 0.000001 ETH` + $1-2 gas fee |

**Note:** everything should be on Base chain

---

## Installation Steps

1. Connect to your server ( skip this step if you running on local pc/laptop )

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

You will see a confirmation message like

✅ GUILD QUEST COMPLETED!
🎉 Welcome to the Boundless Network!

Then go back to:

https://guild.xyz/boundless-xyz
…to complete and verify the rest of your Guild role quests.


---

## Made With ❤️ by Morsy
