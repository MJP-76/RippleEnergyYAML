# <B>Ripple Energy yaml integration for Home Assistant<B>
Use me [Octopus.Energy 🐙](https://share.octopus.energy/iron-moose-196) referral code. You get £50 credit for joining and I get £50 credit.

# Work in progress
- Create sensors via yaml in HA

Updated: 11th August, 2023

# Pre Installation
You will require your Ripple Energy members API key as per available here: [Ripple Energy API Key](https://community.rippleenergy.com/new-feature-requests-yyqtfatb/post/ripple-api-yH0cTzuQ4GJMaYV?highlight=l8VWP51eyif7JlZ)

# Installation
1. Copy the ripple_energy.yaml to /config/packages
2. Create an entry in your secrets.yaml for the entire API Key generated above
    - "ripple_energy_api_key:YOUR API KEY"
3. Restart Home Assistant

# Sensors
The following - Sensors are generated from the Ripple Energy (https://rippleenergy.com/ ) API into Home Assistant

<B>Working<B>
- Project 1 - Graig Fatha
- Project 2 - Kirk Hill
- Project 3 - Derril Water
- Project 4 - Project 4

The following attributes are added to each of the above sensors 
- "name"
- "type"
- "status"
- "total_capacity"
- "member_capacity"
- "member_expected_annual_generation"
WIP

<B>Work in progress<B>
All the other info ;)