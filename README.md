# Home Assistant Laundry Dashboard

This is a Home Assistant setup for tracking and visualizing laundry machine usage. Learn more about Home Assistant at [home-assistant.io](https://www.home-assistant.io/).

## Automations
Automations notify you when:
- **Washer In Use:** The washer starts running.
- **Dryer In Use:** The dryer is active.
- **Laundry Available:** Both machines are idle.

## Configuration
Sensors track power usage and machine activity. Template sensors provide readable statuses for easier understanding.

## Dashboard
The dashboard uses the ApexCharts card to show:
- **Power Trends:** Washer and dryer power consumption.
- **Current Status:** Machine activity.

"Now" is centered on the graph, showing 24 hours of history on the left and future time on the right.

## Example
<img src="img/cards.png" alt="Dashboard Cards" width="600">

## Setup
1. Install integrations:
   - [SonoffLAN](https://github.com/AlexxIT/SonoffLAN)
   - [ApexCharts Card](https://github.com/RomRider/apexcharts-card)
2. Copy files to your Home Assistant configuration directory.
3. Restart Home Assistant.
4. Access the dashboard via the `Laundry` view.

## Editing
Use the [Visual Studio Code Add-on](https://community.home-assistant.io/t/home-assistant-community-add-on-visual-studio-code/107863) for easier editing.

## Documentation
- [Configuration YAML](https://www.home-assistant.io/docs/configuration/yaml/)
- [Automation YAML](https://www.home-assistant.io/docs/automation/yaml/)
