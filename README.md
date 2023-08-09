# <B>Ripple Energy API yaml integration for Home Assistant<B>

[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg)](https://github.com/hacs/integration)

Use me [Octopus.Energy 🐙](https://share.octopus.energy/iron-moose-196) referral code. You get £50 credit for joining and I get £50 credit.

# Work in progress
- Create sensors via yaml in HA

Updated: 9th August, 2023

# Pre Installation
You will require your Ripple Energy members API key as per available here: [Ripple Energy API Key](https://community.rippleenergy.com/new-feature-requests-yyqtfatb/post/ripple-api-yH0cTzuQ4GJMaYV?highlight=l8VWP51eyif7JlZ)

# Installation
1. Copy the rippleenergyyaml.yaml file to /config/packages directory
3. Restart Home Assistant

# Generated - Sensors
The following - Sensors are generated from the Ripple Energy (https://rippleenergy.com/ ) API into Home Assistant

<B>Sensors created<B>
WIP

<B>Sensors not created yet<B>

API response:
{"email": "YOUR_MEMBER_LOGIN_EMAIL", "copyright_notice": "Not to publish or distribute. Only for personal use.", "generation_assets": [

{"name": "Project 4", "type": "Windfarm", "status": "N/A", "total_capacity": 42.0, "total_capacity_units": "MW", "member_capacity": 0.0, "member_capacity_units": "W", "member_expected_annual_generation": 0.0, "member_expected_annual_generation_units": "MWh", "generation": {"generation_unit": "kWh", "latest_telemetry": {}, "latest": {}, "today": {"from": "2023-08-09T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "yesterday": {"from": "2023-08-08T00:00:00Z", "to": "2023-08-09T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "this_week": {"from": "2023-08-07T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "last_week": {"from": "2023-07-31T00:00:00Z", "to": "2023-08-07T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "this_month": {"from": "2023-08-01T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "last_month": {"from": "2023-07-01T00:00:00Z", "to": "2023-08-01T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "this_year": {"from": "2023-01-01T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "last_year": {"from": "2022-01-01T00:00:00Z", "to": "2023-01-01T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "total": {"from": "2000-01-01T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}}, "forecast": []}, 

{"name": "Derril Water", "type": "Solarfarm", "status": "Prelimary", "total_capacity": 42.0, "total_capacity_units": "MW", "member_capacity": 8568.641, "member_capacity_units": "W", "member_expected_annual_generation": 8.4, "member_expected_annual_generation_units": "MWh", "generation": {"generation_unit": "kWh", "latest_telemetry": {}, "latest": {}, "today": {"from": "2023-08-09T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "yesterday": {"from": "2023-08-08T00:00:00Z", "to": "2023-08-09T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "this_week": {"from": "2023-08-07T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "last_week": {"from": "2023-07-31T00:00:00Z", "to": "2023-08-07T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "this_month": {"from": "2023-08-01T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "last_month": {"from": "2023-07-01T00:00:00Z", "to": "2023-08-01T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "this_year": {"from": "2023-01-01T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "last_year": {"from": "2022-01-01T00:00:00Z", "to": "2023-01-01T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "total": {"from": "2000-01-01T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}}, "forecast": []}, 

{"name": "Kirk Hill", "type": "Windfarm", "status": "N/A", "total_capacity": 18.8, "total_capacity_units": "MW", "member_capacity": 2559.465, "member_capacity_units": "W", "member_expected_annual_generation": 8.12, "member_expected_annual_generation_units": "MWh", "generation": {"generation_unit": "kWh", "latest_telemetry": {}, "latest": {}, "today": {"from": "2023-08-09T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "yesterday": {"from": "2023-08-08T00:00:00Z", "to": "2023-08-09T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "this_week": {"from": "2023-08-07T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "last_week": {"from": "2023-07-31T00:00:00Z", "to": "2023-08-07T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "this_month": {"from": "2023-08-01T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "last_month": {"from": "2023-07-01T00:00:00Z", "to": "2023-08-01T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "this_year": {"from": "2023-01-01T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "last_year": {"from": "2022-01-01T00:00:00Z", "to": "2023-01-01T00:00:00Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}, "total": {"from": "2000-01-01T00:00:00Z", "to": "2023-08-09T08:57:03.812Z", "contains_estimate": false, "generated": 0.0, "earned": 0.0}}, "forecast":  []}]}