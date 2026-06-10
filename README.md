# LitVM Ecosystem Research Hub

Research-driven exploration of the LitVM ecosystem through real protocol testing and infrastructure analysis.

## 📋 Overview

This project documents comprehensive testing of LitVM (Litecoin Virtual Machine) protocols and infrastructure, providing factual analysis of the ecosystem's capabilities and limitations.

## 🔬 What We Tested

### 1. **Custom ERC-20 Token Deployment**
- **Platform:** Lester Labs
- **Token Name:** Sidorenkov Test Token (STT)
- **Contract:** `0xEA0ff2E2E3a311b5599BBEAc3aF9B06766CBCD53`
- **Status:** ✅ Fully functional
- **Balance:** ~998,870 STT

### 2. **OmniFun DEX**
- **Function:** DEX with bonding curve launchpad
- **Tested:** ✅ Full cycle
  - Created LP pool (zkLTC/STT)
  - Swap executed: 0.001 zkLTC → 19.56 STT
  - Removed liquidity
- **Status:** ✅ Permissionless, works perfectly

### 3. **Ayni Lending Protocol**
- **Function:** Lending/borrowing (Aave-like)
- **Tested:** ✅ Full cycle
  - Supply: 0.02 wzkLTC
  - Borrow: 0.5 USDC
  - Repay: ✅ Works
  - Withdraw: ✅ Works
- **APR:** 5% variable
- **Status:** ✅ Production-ready

### 4. **SweepHaus NFT Launchpad**
- **Function:** NFT deployment and minting
- **Tested:** ✅ Full cycle
  - Deployed ERC-721 collection
  - Contract: `0x5A3a4AEaC0FA78E845f1f4eB7941a0d312b08F26`
  - Minted NFT (free, 0 zkLTC)
- **Status:** ✅ Permissionless, instant deployment

### 5. **ZNS Domains**
- **Function:** .lit domain registration
- **Tested:** ✅ Domain created
- **Bonus:** Participated in raffle (5 entries, $10 USDC prize)
- **Status:** ✅ Works

### 6. **LitVMSwap Aggregator**
- **Function:** Liquidity aggregator
- **Tested:** ⚠️ Limited
  - Custom tokens visible ✅
  - Pool creation possible ✅
  - Swaps return 0 output ❌
- **Finding:** Requires manual whitelist via Telegram
- **Status:** ❌ NOT permissionless

## 📊 Infrastructure Assessment

### ✅ WORKING:
- Custom ERC-20 deployment
- DEX functionality (OmniFun)
- Lending protocol (Ayni)
- NFT launchpad (SweepHaus)
- Domain registration (ZNS)

### ❌ BROKEN/LIMITED:
- LitVMSwap aggregator (requires whitelist)
- Arkada (quests broken, 0 points)
- No mainnet bridge (testnet only)

## 🔗 Important Links

- **Testnet:** https://testnet.litvm.com/
- **Explorer:** https://liteforge.explorer.caldera.xyz
- **OmniFun:** DEX with working swaps
- **Ayni:** https://ayni.fi (lending protocol)
- **SweepHaus:** https://sweep.haus/ (NFT launchpad)
- **ZNS:** https://zns.bio (domains)

## 📝 Wallet & Contracts

**Our Wallet:**  
`0xc44E8559bAe34b958341c25361DD4B34C522Fe8e`

**Key Contracts:**
- STT Token: `0xEA0ff2E2E3a311b5599BBEAc3aF9B06766CBCD53`
- SweepHaus NFT: `0x5A3a4AEaC0FA78E845f1f4eB7941a0d312b08F26`
- LitVMSwap Pool: `0xF456737D17C2Bbb348fd4F7D1b000D62A46FB3b5`

## 🎯 Key Findings

1. **LitVM is a working testnet** with functional DeFi primitives
2. **Mainnet NOT launched** - all activity is testnet-only
3. **Most protocols are permissionless** (except LitVMSwap)
4. **Team communication is weak** - Discord responses rare
5. **Hackathon organization is poor** - unclear rules, no prizes listed

## 💡 Conclusion

LitVM has working infrastructure (DEX, lending, NFT, domains) but suffers from weak communication and unclear roadmap. Suitable for testing and research, but not ready for production use until mainnet launches.

---

**Research Period:** June 5-10, 2026  
**Total Time Invested:** ~5 hours  
**Status:** Active observation mode# litvm-ecosystem-research-hub
Research-driven exploration of LitVM ecosystem through real protocol testing
