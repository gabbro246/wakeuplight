# Wakeup Light Blueprint

## Inputs
| Name                | Description                                    | Default |
|---------------------|--------------------------------|---------|
| **Alarm Time Helper** (`time`) | The time when the light reaches full brightness. | - |
| **Alarm Switch Helper** (`switch`) | Enables or disables the wake-up light. | - |
| **Alarm State Helper** (`state`) | Stores the alarm status. | - |
| **Light Entity** (`light`) | The light entity used for the wake-up sequence. | - |
| **End Brightness** (`brightness_pct`) | Maximum brightness percentage when wake-up is complete. | 100% |
| **Fade-in Duration** (`duration`) | Time in minutes over which the brightness increases. | 25 min |
| **Alarm Action** (`action`) | Optional action to execute at alarm time. | None |

## Actions
1. **Update Alarm State:**
   - Displays time remaining until the alarm triggers.
   - Shows `off` when disabled.
   - Shows `Alarm! 🚨` when the alarm is triggered.
2. **Gradual Brightness Increase:**
   - Light starts at minimum brightness when the fade-in duration begins.
   - Light brightness gradually increases every minute.
3. **Alarm Trigger:**
   - When the wake-up time is reached, the light is set to full brightness.
   - Any additional actions specified in `action` are executed.

## Installation
1. Copy this blueprint into your Home Assistant automations.
2. Configure the required helpers and add a light entity.
3. Adjust settings such as fade-in duration and brightness percentage as needed.
4. Enjoy a smooth wake-up experience with your Home Assistant smart light setup!

## Quick Import
[![Open your Home Assistant instance and start setting up this blueprint.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/246otters/wakeuplight/refs/heads/main/wakeuplight.yaml)

