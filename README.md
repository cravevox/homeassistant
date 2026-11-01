# homeassistant
A repo for HA (Home Assistant)  Blueprints

## Blueprints

| Blueprint | What it does |
| --- | --- |
| [🐾 LitterMinder](blueprints/automation/litterminder.yaml) | Litter box visit counter and dirty flag, with mobile ("Mark cleaned" button), Alexa and TTS reminders, quiet hours, usage-trend and health alerts, and an optional air purifier boost. Needs only a motion sensor and three helpers. |
| [🫧 LaundryMinder](blueprints/automation/laundryminder.yaml) | Washer and dryer cycle-finished notifications. |
| [Litterbox Tracker (legacy)](blueprints/automation/clean-the-litter.yaml) | The original litter box tracker that LitterMinder replaces. |
| [🔋 BatteryMinder](blueprints/automation/batteryminder.yaml) | Low-battery alerts. |
| [🌧️ Weather Condition Alert](blueprints/automation/weather-condition-alert.yaml) | Weather condition notifications. |

To import a blueprint, open it on GitHub, copy the URL, and paste it into
Settings → Automations & scenes → Blueprints → Import blueprint. To update,
re-import the same URL — your automations keep their settings.
