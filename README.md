DEPRICATED: Please switch integration to https://github.com/briancmpbll/home_assistant_custom_envoy.git; this is the integration which will be maintained and contains all changes ie 3-Phase suppert etc.

This is a HACS custom integration for enphase envoys. This integration is based upon the integration of @briancmpbll with the following modifications:

- Data is refreshed every 30 seconds
- Works for D5 as well as D7 firmware
- Option to show phase specific data for 3-phase systems
- Seven day sensors are removed due to misreadings (Energy dashboard provides weekly / monthly / yearly readings)

# Installation

1. Install [HACS](https://hacs.xyz/) if you haven't already
2. Add this repository as a [custom integration repository](https://hacs.xyz/docs/faq/custom_repositories) in HACS
4. Restart home assistant
5. Add the integration through the home assistant configuration flow
