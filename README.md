This is a HACS custom integration for enphase envoys. This is a fork from [@posixx's fork](https://github.com/posixx/home_assistant_custom_envoy) of [@briancmpbll's integration](https://github.com/briancmpbll/home_assistant_custom_envoy). @posixx made the following modifications:

- Data is refreshed every 30 seconds
- Works for D5 as well as D7 firmware
- Option to show phase specific data for 3-phase systems
- Seven day sensors are removed due to misreadings (Energy dashboard provides weekly / monthly / yearly readings)

@wtadler then modified the integration to provide proper lifetime energy sensor readings for Envoy-S setups that have no consumption metering.

# Installation

1. Install [HACS](https://hacs.xyz/) if you haven't already
2. Add this repository as a [custom integration repository](https://hacs.xyz/docs/faq/custom_repositories) in HACS
4. Restart home assistant
5. Add the integration through the home assistant configuration flow
