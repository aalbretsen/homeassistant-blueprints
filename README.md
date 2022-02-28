# Home Assistant Blueprint Collection

## Deconz switch as dimmer for WLED strip
[[deconz_wled_dimmer.yaml](deconz_wled_dimmer.yaml)]
Blueprint which enables a [Deconz](https://www.home-assistant.io/integrations/deconz/) 
Friends of Hue switch to turn on, off and dim a [WLED](https://www.home-assistant.io/integrations/wled/) strip segment.

[![Imort this blueprint to your Home Assistant instance.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Faalbretsen%2Fhomeassistant-blueprints%2Fmain%2Fdeconz_wled_dimmer.yaml)

## Outdoor light
[[outdoor_light.yaml](outdoor_light.yaml)] Blueprint which reacts to Home Assistant sun events and triggers given scenes for outdoor light on and off. 
Will continuously trigger the scenes to counter for power outage or similar events preventing sun events to trigger the automation.

[![Imort this blueprint to your Home Assistant instance.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Faalbretsen%2Fhomeassistant-blueprints%2Fmain%2Foutdoor_light.yaml)

## Light Control - Motion sensor
[[light_control__motion.yaml](light_control__motion.yaml)] Blueprint for motion sensor controlled light.
- Restarts timer each time motion is detected.
- (Re)starts timer if light is manually turned on (or turned on by other source).
- Resets when light is manually turned off (or turned off by other source).
- Support for blocking value (block at night).

[![Imort this blueprint to your Home Assistant instance.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Faalbretsen%2Fhomeassistant-blueprints%2Fmain%2Flight_control__motion.yaml)

## Light Control - Motion and door sensor
[[light_control__motion_and_door.yaml](light_control__motion_and_door.yaml)] Blueprint for motion and door sensor controlled light.
- Restarts timer each time motion is detected.
- (Re)starts timer if light is manually turned on (or turned on by other source).
- Resets when light is manually turned off (or turned off by other source).
- Configurable if light shall be turned off when the door is closed.
- Support for blocking value (block at night).

[![Imort this blueprint to your Home Assistant instance.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Faalbretsen%2Fhomeassistant-blueprints%2Fmain%2Flight_control__motion_and_door.yaml)

## Light Control - Time of day
[[light_control__time_of_day.yaml](light_control__time_of_day.yaml)] Blueprint for time based light control.
- Up to 8 different time settings.
- Up to 4 override settings.

[![Imort this blueprint to your Home Assistant instance.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Faalbretsen%2Fhomeassistant-blueprints%2Fmain%2Flight_control__time_of_day.yaml)

## Light Control - Motion based time of day
[[light_control__time_of_day_and_motion.yaml](light_control__time_of_day_and_motion.yaml)] Blueprint for motion and time based light control.
- Restarts timer each time motion is detected.
- (Re)starts timer if light is manually turned on (or turned on by other source).
- Resets when light is manually turned off (or turned off by other source).
- Up to 8 different time settings.

[![Imort this blueprint to your Home Assistant instance.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Faalbretsen%2Fhomeassistant-blueprints%2Fmain%2Flight_control__time_of_day_and_motion.yaml)
