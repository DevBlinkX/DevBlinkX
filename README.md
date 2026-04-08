![BlinkX API](https://github.com/blinkX-demo/.github/blob/main/profile/banner.jpeg)

<div align="center">

# BlinkX API
  
Build automated trading workflows with real-time order execution, live market feeds, and portfolio APIs.

BlinkX API gives developers direct programmatic access to India's stock markets for executing your strategies across NSE and BSE.

<br/>

[![Python SDK](https://img.shields.io/badge/Python_SDK-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/blinkx/blinkx-python)
[![Java SDK](https://img.shields.io/badge/Java_SDK-E76F00?style=for-the-badge&logo=openjdk&logoColor=white)](https://github.com/blinkx/blinkx-java)
[![Go SDK](https://img.shields.io/badge/Go_SDK-00ACD7?style=for-the-badge&logo=go&logoColor=white)](https://github.com/blinkx/blinkx-go)
[![Node.js SDK](https://img.shields.io/badge/Node.js_SDK-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://github.com/blinkx/blinkx-nodejs)

</div>

---

## ⚡ What You Can Build

| Capability | Description |
|---|---|
| **Order Management** | Execute the full order lifecycle - up to **9 Orders Per Second** |
| **Live Market Feed** | WebSocket streaming for **1,000+ instruments** across NSE & BSE |
| **Historical Data** | Tick-by-tick and OHLCV candle data for backtesting and analysis |
| **Portfolio Management** | Real-time holdings, positions, P&L and margin data |
| **Authentication** | OAuth 2.0 - secure, stateless, daily-session based |

---

## 🚀 Quickstart

**1. Sign up, Create your APP and get your API key**

```
https://developeruat.blinkx.in/signup
```

**2. Install the SDK**

```bash
# To install Python SDK
pip install blinkx-python          
# To install Node.js SDK
npm install blinkx-nodejs          
# To install Go SDK
go get github.com/blinkx/blinkx-go 
# To install Java SDK

```

**3. Place your first order**

```python
# Authenticate with BlinkX API
from blinkx import TradeAPI

client = TradeAPI(
  api_key="bx_live_••••••••••••",
  access_token="eyJhbGci..."
)

# Place an order in real-time
order = client.place_order(
  symbol="RELIANCE",
  exchange="NSE",
  quantity=10,
  order_type="MARKET",
  side="BUY"
)

# → { "order_id": "BX20260323001", "status": "PLACED" }
```

---

## 📦 Repositories

| Repository | Language | Description |
|---|---|---|
| [blinkx-python](https://github.com/blinkx/blinkx-python) | 🐍 Python | Official Python SDK |
| [blinkx-java](https://github.com/blinkx/blinkx-java) | ☕ Java | Official Java SDK |
| [blinkx-go](https://github.com/blinkx/blinkx-go) | 🐹 Go | Official Go client |
| [blinkx-nodejs](https://github.com/blinkx/blinkx-nodejs) | 🟩 Node.js | Official Node.js SDK |

---

## 📚 Resources

- 📖 &nbsp;[API Documentation](https://developer.blinkx.in/docs/)
- 🔑 &nbsp;[Get Your API Key](https://developeruat.blinkx.in/signup)
- 📧 &nbsp;[General Enquiries](https://blinkx.in/contact-us)

---

## 📋 Platform Specs

```
Rate Limit          9 orders/second 
Max Orders/Day      14,000
Auth                OAuth 2.0 (daily session)
```

---

BlinkX API complies with all SEBI and exchange regulations for algorithmic trading in India.  
A **static IP address** is mandatory for all API integrations per NSE/BSE guidelines (effective August 2025).  

---

<div align="center">

**© 2026 BlinkX · Powered by JM Financial**  

</div>
