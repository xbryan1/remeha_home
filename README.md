This is a custom fork of the original Remeha Home integration by msvisser (msvisser/remeha_home) and the customization by petarlaf (petarlaf/remeha_home_baxi_hvac).

This fork was created primarily to:

Provide Hot Water control for Baxi and integrate it in HomeKit via a switch to turn it on or turn it off.
Adapt the Climate control logic to work more reliably with the author's specific BAXI HVAC system (Heating & Cooling).
Testing: This fork has been developed and tested specifically on a Baxi PLATINUM BC IPLUS V200 INTEGRA system. While it may work on other Baxi or BDR Thermea models, compatibility is not guaranteed.

## Installation

### Install with HACS (recommended)
[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=msvisser&repository=remeha_home&category=integration)

1. Add this repository URL (https://github.com/xbryan1/remeha_home) as a custom repository in HACS (Integration type).
1. Search for "Remeha Home Baxi HVAC" (or similar) under Integrations and install it.
1. Restart Home Assistant.

### Install manually

1. Install this platform by creating a `custom_components` folder in the same folder as your configuration.yaml, if it doesn't already exist.
2. Create another folder `remeha_home` in the `custom_components` folder. Copy all files from `custom_components/remeha_home` into the `remeha_home` folder.

## Setup
1. In Home Assitant click on `Configuration`
1. Click on `Devices & Services`
1. Click on `+ Add integration`
1. Search for and select `Remeha Home`
1. Enter your email address and password
1. Click "Next"
1. Enjoy

## API documentation
For information on the Remeha Home API see [API documentation](documentation/api.md).

## Acknowledgements

Based heavily on the original work of msvisser (msvisser/remeha_home) and petarlaf (petarlaf/remeha_home_baxi_hvac).
