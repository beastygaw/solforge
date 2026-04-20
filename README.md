# ⚔️ NFT Arena — Solana NFT Card Game

> Built for Colosseum Hackathon 2026

## 🎮 Live Demo
👉 **https://beastygaw.github.io/nft-arena-web/**

## 📖 About
NFT Arena is an on-chain NFT trading card game built on Solana. Players can mint unique NFT cards with on-chain stats, build their collection, and battle other players — all powered by Solana's blazing fast blockchain.

## ✨ Features
- 🎴 **Mint NFT Cards** — Each card is a unique NFT on Solana devnet with on-chain stats (Attack, Defense, Rarity)
- 🃏 **Card Collection** — View all your minted cards with blockchain explorer links
- ⚔️ **Battle System** — Challenge opponents, winner determined by on-chain card power
- 👛 **Phantom Wallet** — Full wallet integration with connect/disconnect
- ⚡ **Solana Speed** — Transactions confirm in under 1 second

## 🛠️ Tech Stack
| Layer | Technology |
|---|---|
| Blockchain | Solana (Devnet) |
| Smart Contract | Rust + Anchor Framework |
| NFT Standard | SPL Token |
| Frontend | HTML5 + JavaScript |
| Wallet | Phantom Wallet Adapter |
| Hosting | GitHub Pages |

## 📋 Smart Contract
- **Program ID:** `2UKxt5rLyEcDP1TjoXnt78o97D13Xqc9oxqnEu4eBrCs`
- **Network:** Solana Devnet
- **Framework:** Anchor v0.29.0

## 🔧 Smart Contract Instructions
| Instruction | Description |
|---|---|
| `mint_card` | Mints a new NFT card with stats stored on-chain |
| `battle` | Battles two cards, updates win/loss on-chain |
| `get_card_stats` | Fetches card stats from blockchain |

## 🚀 How It Works
1. Connect your Phantom wallet (set to Devnet)
2. Go to **Mint** and choose a card to forge
3. Approve the transaction in Phantom
4. Your NFT card is now live on Solana blockchain
5. Go to **Battle** and challenge opponents
6. Winner is determined by combined Attack + Defense power

## 🎴 Card Rarities
| Rarity | Cards |
|---|---|
| 🟡 Legendary | Dragon Warrior, Shadow Wolf |
| 🔵 Rare | Ice Phoenix, Storm Eagle, Fire Sprite |
| ⚪ Common | Earth Golem |

## 🏗️ Local Development
```bash
# Clone the repo
git clone https://github.com/beastygaw/nft-arena-web

# Open index.html in browser
# No build step needed!
```

## 📁 Smart Contract Repo
👉 https://github.com/beastygaw/solana-nft-arena

## 👤 Builder
Built by **Farhad** for the Colosseum Hackathon 2026
