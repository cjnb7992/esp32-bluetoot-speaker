# ESP32 Bluetooth Speaker Project

This project is designed to create a Bluetooth speaker using the ESP32 microcontroller, which integrates with Home Assistant for voice commands and AI functionality.

## Project Structure

```
esp32-bluetooth-speaker
├── config
│   ├── speaker.yaml
│   └── secrets.yaml
├── custom_components
│   └── ai_voice
│       ├── __init__.py
│       ├── ai_voice.py
│       └── manifest.json
└── README.md
```

## Files Overview

- **config/speaker.yaml**: Contains the main configuration for the ESPHome Bluetooth speaker, including device settings, Bluetooth configuration, audio output, and Home Assistant integration for voice commands.

- **config/secrets.yaml**: Stores sensitive information such as API keys and passwords required for the configuration in `speaker.yaml`.

- **custom_components/ai_voice/__init__.py**: Initializes the custom AI voice component for Home Assistant, potentially containing setup code.

- **custom_components/ai_voice/ai_voice.py**: Implements the functionality of the AI voice component, including classes and methods for processing voice commands and integrating with AI services.

- **custom_components/ai_voice/manifest.json**: Provides metadata about the custom component, including its name, version, dependencies, and other configuration details required by Home Assistant.

## Setup Instructions

1. Clone this repository to your local machine.
2. Navigate to the `config` directory and edit `secrets.yaml` to include your sensitive information.
3. Configure `speaker.yaml` to set up your ESP32 device and Bluetooth settings.
4. Install the custom AI voice component by placing it in the `custom_components` directory of your Home Assistant installation.
5. Restart Home Assistant to load the new component and apply the configurations.

## Usage Guidelines

Once set up, you can use voice commands to control the Bluetooth speaker through Home Assistant. Ensure that your ESP32 is connected to the same network as your Home Assistant instance for seamless integration.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or additional features.