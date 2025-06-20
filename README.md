# GEOD Token Dashboard (Home Assistant)

Monitor your GEOD token balance, daily earnings, and update cycles using this Home Assistant dashboard.

## Features

- GEOD balance tracking via Polygonscan API
- Daily received tokens calculation
- Refresh button for manual updates
- 7-day graph of token rewards

## Setup Instructions

1. Add these to your `secrets.yaml`:

```yaml
geod_wallet_address: 0xYOUR_WALLET_ADDRESS
polygonscan_api_key: YOUR_POLYGONSCAN_API_KEY
```

2. Copy contents of `dashboards/geod_dashboard/` to your Home Assistant config.

3. Restart HA or reload YAML.

## HACS Installation

Add this repo as a custom repository under "Dashboards".
