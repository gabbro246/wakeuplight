# Wakeup Light Blueprint with Dashboard Card

[![Open your Home Assistant instance and start setting up this blueprint.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/246otters/wakeuplight/refs/heads/main/wakeuplight.yaml?token=GHSAT0AAAAAAC6TJQVMG6ZZKTZKF6VAMW4AZ5V7I5A)

## Inputs
| Name | Description | Default |
|---|---|---|
| **Alarm Time Helper** (`time`) | The time when the light reaches full brightness. | - |
| **Alarm Switch Helper** (`switch`) | Enables or disables the wake-up light. | - |
| **Alarm State Helper** (`state`) | Stores the alarm status. | - |
| **Light Entity** (`light`) | The light entity used for the wake-up sequence. | - |
| **End Brightness** (`brightness_pct`) | Maximum brightness percentage when wake-up is complete. | 100% |
| **Fade-in Duration** (`duration`) | Time in minutes over which the brightness increases. | 25 min |
| **Alarm Action** (`action`) | Optional action to execute at alarm time. | None |
