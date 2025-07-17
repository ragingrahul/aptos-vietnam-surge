# Surge

A decentralized finance (DeFi) application built on the Aptos blockchain, featuring price oracles and token swapping functionality with a modern web interface.

### 🔮 Surge Contracts

A sophisticated volatility oracle that provides real-time volatility calculations for APT/USD using multiple statistical methods:

- **Multi-method volatility calculation** (Welford, EWMA, Composite)
- **Robust outlier detection** using Median Absolute Deviation
- **Time-weighted analytics** with decay factors
- **Confidence scoring** based on data quality
- **Pyth Network integration** for reliable price feeds

A volatility trading protocol that allows users to take long or short positions on volatility:

- **LONG Tokens (slAPT)**: Benefit from increasing volatility
- **SHORT Tokens (ssAPT)**: Benefit from decreasing volatility
- **Dynamic pricing** based on real-time volatility
- **Secure vault system** with resource account architecture
- **Comprehensive trading functions** with preview capabilities

## 📁 Project Structure

```
main repo/
├── surge-client/          # Next.js Frontend Application
│   ├── app/              # Next.js 13+ App Router
│   ├── components/       # Reusable UI components
│   ├── lib/             # Utilities and API integrations
│   └── public/          # Static assets
└── surge-contracts/      # Aptos Move Smart Contracts
    ├── surge_oracle/    # Price oracle implementation
    └── surge_swap/      # Token swap protocol
```

### Frontend (`surge-client/`)

- **Framework**: Next.js 14 with TypeScript
- **Styling**: Tailwind CSS with custom UI components
- **Features**: Analytics dashboard, price charts, responsive design
- **APIs**: CoinGecko integration for market data

### Smart Contracts (`surge-contracts/`)

- **Language**: Move (Aptos blockchain)
- **Oracle Contract**: Price feed management and updates
- **Swap Contract**: Automated market maker (AMM) functionality

## 📊 Features

### Web Application

- **📈 Analytics Dashboard**: Real-time market data and charts
- **💱 Token Swap Interface**: User-friendly trading interface
- **📱 Responsive Design**: Works seamlessly on desktop and mobile
- **✨ Modern UI**: Glowing effects and smooth animations
- **🔍 Market Data**: Integration with CoinGecko API

### Smart Contracts

- **🔮 Price Oracle**: Decentralized price feeds
- **💧 Liquidity Pools**: Automated market maker functionality
- **🪙 Token Management**: Secure token operations
- **⚡ High Performance**: Optimized for Aptos blockchain
