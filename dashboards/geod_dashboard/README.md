# GEOD Home Assistant Dashboard

This is a reusable Home Assistant configuration to track GEOD token rewards:
- Daily token received
- Total balance
- Manual refresh button
- 6-hour update cycles
- Rolling 7-day reward history

## Setup

1. Replace the placeholder wallet address and API key in `sensors.yaml`:
   - `0xYOUR_WALLET_ADDRESS_HERE`
   - `YOUR_POLYGONSCAN_API_KEY`

2. Copy the files into your Home Assistant config directory.

3. Add Mini Graph Card via HACS (optional) for prettier graphs.

4. Import the dashboard manually or recreate with:
   - `sensor.geod_token_balance`
   - `sensor.geod_tokens_received_today`
   - `sensor.geod_next_update`
   - `sensor.geod_daily_rewards_history`

## Included Files

- `configuration.yaml`
- `sensors.yaml`
- `automations.yaml`
- `scripts.yaml`
