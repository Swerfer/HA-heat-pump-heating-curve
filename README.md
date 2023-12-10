# HA-heat-pump-heat-curve

![alt 3-phase energy gauges card](https://github.com/Swerfer/HA-heat-pump-heating-curve/blob/main/images/heating_curve_card.jpg?raw=true)

## Prerequisites

Install [Lovelace card mod](https://github.com/thomasloven/lovelace-card-mod) from HACS.

## How to install

•	Create in your www folder a folder named 'heating_curve'.

•	Copy 'heating_curve_line.png' and 'heating_curve-grid.png' to the new created folder.

•	Copy the YAML from 'heating_curve_card.yaml' and past it in a new manual card.

•	Edit the entities in the yaml to your entities (at 2 places!). 

• min_out and min_water are the temperature entities at the left of the grid (-10/45°C).

• max_out and max_water are the temperature entities at the right of the grid (20/30°C).

•	Save the card and you’re done.

## Buy me a coffee
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/Swerfer)
