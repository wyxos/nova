# NOVA

NOVA is a self-hosted, cross-platform media player tailored for local audio streaming. Designed to offer a
seamless experience for managing and playing your audio files across desktop and mobile devices, NOVA Player combines
intuitive library management with powerful playback features.

## Features

- **Local Streaming**: Enjoy your audio collection directly from your device, with no need for cloud storage.
- **Cross-Platform Compatibility**: Access your music library seamlessly on both desktop and mobile platforms.

## Getting Started

### Installation

The NOVA Player app is available as a packaged application for desktop platforms. Here's how to get started:

1. Download the latest version of NOVA Player from the releases section.
2. Unpack the downloaded file and run the installer on your desktop.

### Accessing on Mobile

To access NOVA Player on your mobile device, you need to perform a few additional steps:

1. Launch NOVA Player on your desktop and navigate to the settings.
2. Configure the IP address and port for the server within the app's settings. This will allow your mobile device to
   connect to the desktop app over your local network.
3. Ensure the configured port is open in your Windows firewall and router settings. This step is crucial for enabling
   access from your mobile device.
4. If your IP address is dynamic (changes regularly), you may need to update these settings frequently. Alternatively,
   consider using a dynamic DNS service like No-IP to maintain a consistent domain name for your desktop app.

Once set up, enter the provided IP address and port in your mobile device's web browser to access NOVA Player.

### Usage

After installation, launch NOVA Player, navigate to the Settings screen (bottom cog icon) and add the folder where
your audio files are located. It will take a moment to index them all.

## Support

Your feedback and suggestions are welcome. While the source code of NOVA Player is not publicly available, I am keen
to hear your ideas for features or improvements. If you encounter any issues or have feature requests, please reach out
through the issue tracker associated with the download platform.

## Acknowledgments

- Special thanks to Vue.js for powering the app's dynamic interfaces.
- Gratitude to Electron for enabling cross-platform desktop app development.

