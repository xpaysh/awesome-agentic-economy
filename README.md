# Awesome Agentic Economy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🗺️ **The Definitive Map & Launchpad for the Agentic Economy** - From Zero to Production in 5 Minutes

🚀 The first comprehensive resource covering the entire agentic economy stack - protocols, tools, and boilerplates to build autonomous AI agents that can discover, communicate, and transact value independently.

[![GitHub stars](https://img.shields.io/github/stars/xpaysh/awesome-agentic-economy?style=social)](https://github.com/xpaysh/awesome-agentic-economy)
[![Boilerplate Repo](https://img.shields.io/badge/🔧_Boilerplates-agentic--economy--boilerplate-blue)](https://github.com/xpaysh/agentic-economy-boilerplate)
![Market Size](https://img.shields.io/badge/Market_Size-$5T_by_2030-brightgreen)
![Protocols Tracked](https://img.shields.io/badge/Protocols-12+_Active-orange)

## 🎯 Quick Start - Choose Your Path

**🏗️ Builder?** → [5-Minute Vending Machine](https://github.com/xpaysh/agentic-economy-boilerplate) - Clone & run working examples  
**🧭 Explorer?** → [4-Layer Stack Guide](#-the-4-layer-stack-framework) - Understand the full ecosystem  
**🚀 Enterprise?** → [Protocol Decision Tree](#-protocol-selector-quiz) - Find your optimal stack  
**📊 Investor?** → [Market Analysis](#-market-analysis) - Growth metrics & forecasts

---

## 🗺️ The 4-Layer Stack Framework

The agentic economy operates on four fundamental layers. Understanding this stack is key to building successful autonomous agents:

```mermaid
graph TB
    A[Identity & Trust Layer] --> B[Discovery Layer]
    B --> C[Communication Layer] 
    C --> D[Commerce Layer]
    
    A1[Who am I? Who can I trust?] --> A
    B1[How do I find other agents?] --> B
    C1[How do we talk to each other?] --> C
    D1[How do we exchange value?] --> D
```

### 🔐 Layer 1: Identity & Trust (The "Passport")
*How do agents prove identity and establish trust?*

| Protocol | Description | Key Feature | Status |
|----------|-------------|-------------|---------|
| **Google's AP2 Mandates** | Verifiable Credentials for agent authorization | VCs + Audit trails | ✅ Production |
| **Visa's Trusted Agent Protocol (TAP)** | Agent verification vs bot detection | Cloudflare integration | 🚧 Beta |
| **W3C DIDs/Verifiable Credentials** | Decentralized identity foundation | Open standards | ✅ Standard |
| **Mastercard "Know Your Agent"** | TradFi-to-agent identity bridge | Card network integration | 🚧 Pilot |

### 📍 Layer 2: Discovery (The "Yellow Pages")  
*How do agents find each other and discover services?*

| Protocol | Description | Key Feature | Status |
|----------|-------------|-------------|---------|
| **Google's A2A Agent Cards** | JSON manifests for agent capabilities | Service descriptions | ✅ Production |
| **Olas (Autonolas)** | On-chain registries via NFTs | Decentralized discovery | ✅ Production |
| **IBM's ACP Registry** | Agent capability registries | Enterprise focus | 🚧 Beta |

### 💬 Layer 3: Communication (The "Language")
*How do agents communicate and coordinate?*

| Protocol | Description | Key Feature | Status |
|----------|-------------|-------------|---------|
| **Google's A2A Protocol** | Agent-to-agent communication standard | Real-time coordination | ✅ Production |
| **Anthropic's MCP** | Agent-to-tool communication | Context sharing | ✅ Production |
| **IBM's ACP Wire Format** | Cross-framework agent communication | Human-agent inclusion | 🚧 Beta |

### 💰 Layer 4: Commerce (The "Transaction")
*How do agents exchange value and complete transactions?*

| Protocol | Origin | Focus | Key Features | Weekly Volume |
|----------|--------|-------|--------------|---------------|
| **x402** | Coinbase + Cloudflare | Crypto-native micropayments | HTTP 402, instant settlement, zero fees | 500K+ transactions |
| **AP2** | Google + 60 orgs | Enterprise payment authorization | Payment-agnostic, auditable, VCs | Enterprise adoption |
| **ACP** | OpenAI + Stripe | Consumer commerce | ChatGPT checkout, fraud prevention | Millions of transactions |
| **Pay3** | Pay3 Platform | Stablecoin automation | USDC/USDT, autonomous payouts | Telegram/TON focus |
| **Agent Pay** | Mastercard | TradFi integration | Tokenized payments, wallet integration | Global card networks |

---

## 🚀 The Rosetta Stone: Working Examples

Instead of just documentation, we provide **working vending machine agents** implemented with each major protocol stack:

### 🎮 [Boilerplate Repository](https://github.com/xpaysh/agentic-economy-boilerplate)

```bash
# Get started in 30 seconds
git clone https://github.com/xpaysh/agentic-economy-boilerplate
cd agentic-economy-boilerplate

# Choose your protocol and run
cd x402-vending-machine && npm start      # Crypto micropayments
cd ap2-vending-machine && npm start       # Enterprise authorization  
cd acp-stripe-vending-machine && npm start # Consumer checkout
cd pay3-vending-machine && npm start      # Stablecoin automation
cd mastercard-vending-machine && npm start # TradFi integration
```

**🎯 Each example demonstrates**:
- Authentication & authorization
- Service discovery
- Payment processing
- Error handling
- Security best practices

---

## 🧭 Protocol Selector Quiz

Not sure which protocols to use? Answer these questions to get your recommended stack:

### 🔍 What's your primary use case?
- **🤖 AI Agent Micropayments** → x402 + MCP + A2A
- **🏢 Enterprise B2B Automation** → AP2 + A2A + Enterprise Identity
- **🛒 Consumer AI Commerce** → ACP (OpenAI/Stripe) + MCP
- **🌐 Cross-Chain DeFi Agents** → Pay3 + Olas + MCP
- **💳 Traditional Finance Integration** → Mastercard Agent Pay + AP2

### 🏗️ What's your technical background?
- **Web2 Developer** → Start with ACP (Stripe) + MCP
- **Web3 Developer** → Start with x402 + Olas
- **Enterprise Developer** → Start with AP2 + A2A
- **AI/ML Engineer** → Start with MCP + your preferred payment layer

### 📊 What's your transaction volume?
- **< 1K/month** → x402 (zero fees)
- **1K-100K/month** → ACP or AP2
- **100K+/month** → Enterprise solutions (AP2 + custom)

---

## 📚 Deep Dive Documentation

### 📖 [Protocol Documentation](./protocols/README.md)
- [Identity & Trust Protocols](./protocols/identity-trust.md)
- [Discovery Protocols](./protocols/discovery.md)  
- [Communication Protocols](./protocols/communication.md)
- [Commerce Protocols](./protocols/commerce.md)

### 🛠️ [Implementation Guides](./implementations/README.md)
- [SDKs & Libraries](./implementations/sdks.md)
- [Frameworks & Tools](./implementations/frameworks.md)
- [Security Best Practices](./implementations/security.md)

### 💡 [Use Cases & Patterns](./use-cases/README.md)
- [AI Agent Micropayments](./use-cases/micropayments.md)
- [Multi-Agent Coordination](./use-cases/coordination.md)
- [Autonomous Marketplaces](./use-cases/marketplaces.md)
- [Enterprise Automation](./use-cases/enterprise.md)

---

## 📊 Market Analysis

### 🚀 Growth Metrics (2025)
- **Market Size**: $5T projected by 2030
- **Protocol Adoption**: 88% of executives piloting agents
- **Transaction Growth**: 492% year-over-year (x402)
- **Enterprise Adoption**: 46% fear falling behind without agents

### 📈 Live Protocol Stats
- **x402**: 500K+ weekly transactions, $180M+ ecosystem value
- **ACP**: Powers millions of AI-user transactions via ChatGPT
- **AP2**: Backed by 60+ organizations including PayPal, Mastercard
- **MCP**: Essential for Claude integrations, growing rapidly

### 🔮 2025 Predictions
- Multi-protocol agents become standard (hybrid stacks)
- Enterprise adoption accelerates with compliance frameworks
- Cross-chain interoperability becomes critical
- AI-to-AI marketplaces reach mainstream adoption

---

## 🌟 Ecosystem Projects

### 🏆 Featured Implementations
- **[Claude x402 Integration](link)** - Anthropic's Claude with crypto payments
- **[GPT-4 AP2 Enterprise](link)** - OpenAI + Google enterprise workflow
- **[Telegram Pay3 Bots](link)** - Autonomous Telegram payment bots
- **[Multi-Agent Coordination](link)** - A2A + multiple payment rails

### 🎯 Developer Showcases
*Submit your project: [Contribution Guidelines](./community/CONTRIBUTING.md)*

---

## 👥 Community & Resources

### 💬 Join the Community
- **Discord**: [Agentic Economy Builders](link)
- **Twitter**: [@AgenticEconomy](link) 
- **Newsletter**: [Weekly Protocol Updates](link)
- **Telegram**: [Protocol Updates Channel](link)

### 📅 Upcoming Events
- Monthly Protocol Sprint Calls
- Quarterly Ecosystem Conference
- Weekly Twitter Spaces

### 🤝 Contributing
We're actively looking for:
- Protocol documentation improvements
- New boilerplate examples
- Security audit reviews
- Market research data
- Community translations

See our [Contributing Guide](./community/CONTRIBUTING.md) for details.

---

## 🔗 Related Resources

### 🎯 Other Awesome Lists                                                                                              
- [Awesome x402](https://github.com/xpaysh/awesome-x402) - Deep dive on HTTP 402 payments                              
- [Awesome AI Agents](link) - General AI agent resources                                                               
- [Awesome Web3 Payments](link) - Crypto payment protocols                                                             

###  xpay.sh Ecosystem
- [xpay.sh](https://www.xpay.sh/) - The official website for xpay.sh.
- [GitHub](https://github.com/xpaysh) - The GitHub organization for xpay.sh.
- [Docs](https://docs.xpay.sh) - The official documentation for xpay.sh.
- [Discord](https://discord.gg/qtanBNnJ) - Join the xpay.sh community on Discord.

### 📚 Official Documentation                                                                                           
- [x402 Foundation Docs](https://docs.x402.org)                                                                        
- [Google A2A Protocol](https://developers.google.com/a2a)                                                             
- [Anthropic MCP](https://modelcontextprotocol.io)                                                                     
- [OpenAI ACP Documentation](https://platform.openai.com/docs/acp)
---                                                                                                                    

                                                                                                                       

## 📄 License                                                                                                           

                                                                                                                       

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)          

                                                                                                                       

This work is licensed under [Creative Commons Zero v1.0 Universal](LICENSE).                                           

                                                                                                                       

---   

**🚀 Ready to build the agentic economy? Start with our [5-minute boilerplates](https://github.com/xpaysh/agentic-economy-boilerplate) and join thousands of developers building autonomous agent systems!**