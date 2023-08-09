# <B><U>Ripple Energy API integration for Home Assistant<B><U>

[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg)](https://github.com/hacs/integration)

Use me [Octopus.Energy 🐙](https://share.octopus.energy/iron-moose-196) referral code. You get £50 credit for joining and I get £50 credit.

# Work in progress
- HACS Integration
- Home Assistant UI WorkFlow
- json to sensors via HACS/HA UI integration

Updated: 9th August, 2023

# Pre Installation
You will require your Ripple Energy members API key as per available here: [Ripple Energy API Key](https://community.rippleenergy.com/new-feature-requests-yyqtfatb/post/ripple-api-yH0cTzuQ4GJMaYV?highlight=l8VWP51eyif7JlZ)

# Installation
<B><U>HACS<B><U>
1. Add this [repository}(https://github.com/MJP-76/RippleEnergyAPI) as "Custom repository" in "Integrations" menu in HACS (Home Assistant Community Store)
2. Install the integration in HACS
3. Restart Home Assistant

<B><U>Manual<B><U>
1. Download integration
2. Copy the folder custom_components/aladin-online from the zip to your config directory
3. Restart Home Assistant

# Post Installation
After restart of Home Assistant, integration can be configured through the integration setup UI


# Generated Sensors
The following sensors are generated from the Ripple Energy (https://rippleenergy.com/ ) API into Home Assistant

ripple_asset0_name
ripple_asset0_status
ripple_asset0_type

ripple_asset0_total_capacity_units
ripple_asset0_total_capacity
ripple_asset0_member_expected_annual_generation
ripple_asset0_member_expected_annual_generation_units
ripple_asset0_member_capacity
ripple_asset0_member_capacity_units

ripple_asset0_forecast
ripple_asset0_generation_latest_telemetry
ripple_asset0_generation_latest

ripple_asset0_generation_generation_unit

ripple_asset0_generation_total_to
ripple_asset0_generation_total_generated
ripple_asset0_generation_total_from
ripple_asset0_generation_total_estimate
ripple_asset0_generation_total_earned

ripple_asset0_generation_today_to
ripple_asset0_generation_today_generated
ripple_asset0_generation_today_from
ripple_asset0_generation_today_estimate
ripple_asset0_generation_today_earned

ripple_asset0_generation_yesterday_to
ripple_asset0_generation_yesterday_generated
ripple_asset0_generation_yesterday_from
ripple_asset0_generation_yesterday_estimate
ripple_asset0_generation_yesterday_earned

ripple_asset0_generation_this_week_to
ripple_asset0_generation_this_week_generated
ripple_asset0_generation_this_week_from
ripple_asset0_generation_this_week_earned
ripple_asset0_generation_thisweek_estimate

ripple_asset0_generation_last_week_to
ripple_asset0_generation_last_week_generated
ripple_asset0_generation_last_week_from
ripple_asset0_generation_last_week_earned
ripple_asset0_generation_lastweek_estimate

ripple_asset0_generation_this_month_to
ripple_asset0_generation_this_month_generated
ripple_asset0_generation_this_month_from
ripple_asset0_generation_this_month_earned
ripple_asset0_generation_thismonth_estimate

ripple_asset0_generation_last_month_to
ripple_asset0_generation_last_month_generated
ripple_asset0_generation_last_month_from
ripple_asset0_generation_last_month_earned
ripple_asset0_generation_lastmonth_estimate

ripple_asset0_generation_this_year_to
ripple_asset0_generation_this_year_generated
ripple_asset0_generation_this_year_from
ripple_asset0_generation_this_year_earned
ripple_asset0_generation_thisyear_estimate

ripple_asset0_generation_last_year_to
ripple_asset0_generation_last_year_generated
ripple_asset0_generation_last_year_from
ripple_asset0_generation_last_year_earned
ripple_asset0_generation_lastyear_estimate

