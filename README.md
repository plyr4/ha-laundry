# Home Assistant Laundry Module

This repository is a Home Assistant module designed to monitor and visualize laundry machine usage. Home Assistant is an open-source platform for home automation, allowing you to control and automate devices in your home. Learn more at [Home Assistant](https://www.home-assistant.io/).

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
![Dashboard Cards](img/cards.png)

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
