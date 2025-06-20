# GEOD Token Dashboard for Home Assistant

![GEOD Dashboard Preview](assets/geod_dashboard_preview.png)

---

A simple plug-and-play **Home Assistant dashboard** for tracking your GEOD token stats:

- GEOD token balance
- USD value (live price from WhiteBIT)
- Tokens received today
- 7-day reward history
- Manual refresh button

---

##  What's Included

- YAML sensors for GEOD balance, price, USD value, and daily received
- Lovelace layout (gauge, graphs, buttons)
- HACS support with metadata
- Preview image

---

## Setup Instructions

1. **Clone or download this repo**
2. Place contents of `dashboards/geod_dashboard/` in your Home Assistant config folder
3. Add the following to your `secrets.yaml`:

```yaml
geod_wallet_address: 0xYOUR_WALLET_ADDRESS
polygonscan_api_key: YOUR_API_KEY
