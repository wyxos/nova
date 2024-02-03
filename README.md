# NOVA

NOVA is a self-hosted, cross-platform media player tailored for local audio and video streaming. Designed to offer a
seamless experience for managing and playing your audio and video files across desktop and mobile devices, NOVA combines
intuitive library management with powerful playback features.

![NOVA preview](/preview.png "NOVA preview")

## Features

- **Local Streaming**: Enjoy your audio and video collection directly from your device, with no need for cloud storage.
- **Cross-Platform Compatibility**: Access your music library seamlessly on both desktop and mobile platforms.

## Getting Started

### Installation

The NOVA app is available as a packaged application for desktop platforms. Here's how to get started:

1. Download the latest version of NOVA from the [releases](https://github.com/wyxos/nova/releases) section.
2. Unpack the downloaded file and run the installer on your desktop.

### Accessing on Mobile

To access NOVA on your mobile device, you need to perform a few additional steps:

1. Launch NOVA on your desktop and navigate to the settings.
2. Configure the IP address and port for the server within the app's settings. This will allow your mobile device to
   connect to the desktop app over your local network.
3. Ensure the configured port is open in your Windows firewall and router settings. This step is crucial for enabling
   access from your mobile device.
4. If your IP address is dynamic (changes regularly), you may need to update these settings frequently. Alternatively,
   consider using a dynamic DNS service like No-IP to maintain a consistent domain name for your desktop app.

Once set up, enter the provided IP address and port in your mobile device's web browser to access NOVA.

### Usage

After installation, launch NOVA, navigate to the Settings screen (bottom cog icon) and add the folder where
your audio/video files are located. It will take a moment to index them all.

## Keyboard Shortcuts

NOVA supports a range of keyboard shortcuts to enhance your music listening experience, making it easier to control playback and rate your music without interrupting your workflow. Here are the shortcuts available:

### Rating Tracks

- **Rate a track**: Use `Alt + [1-5]` to rate the current track, where `1` is the lowest rating and `5` is the highest.

### Media Controls

- **Play/Pause**: `MediaPlayPause` toggles play/pause for the current track.
- **Next Track**: `MediaNextTrack` skips to the next track in your playlist.
- **Previous Track**: `MediaPreviousTrack` goes back to the previous track.

Ensure NOVA is focused or running in the background for these shortcuts to work effectively. These shortcuts are designed to integrate seamlessly with your media keys, providing you with quick access to NOVA's features directly from your keyboard.

# NOVA Feature Roadmap

As NOVA grows, I'm focused on enhancing your experience with this self-hosted, cross-platform media player. This roadmap outlines the features I'm planning to introduce, aimed at enriching your audio and video streaming within NOVA.

## Upcoming Features

### Core Enhancements
- **Mobile Access**: Extend your NOVA experience to your phone with a web-based solution.

### Planned Improvements
- **Playlist Management**: Tools for creating and managing playlists with ease.
- **User Interface Tweaks**: Enhancements like a right-click menu for quick actions and the ability to select multiple items easily.
- **Video Support**: Bringing video playback into the mix.
- **Metadata Handling**: Easy editing and updating of song metadata to keep your library organized.
- **Exercise Timer**: A timer feature for those who like to mix music with workouts.
- **Media Key Support**: Use your keyboard or headset buttons for hands-free control.
- **Navigation Links**: Quick links to artist and album views for faster library browsing.
- **Drag-and-Drop Library Management**: Easily add new content to your library.
- **Selective Track Deletion**: A feature to remove all tracks rated at a certain level from your library.
- **Server Management**: Directly control server operations from within NOVA.
- **Format Compatibility**: Support for a broader range of audio and video formats.

### Additional Features
- **Tagging and Lyrics**: Better organization and immersive listening with lyrics display.
- **Album Art**: Visual enhancements for browsing your collection.
- **Personalized Recommendations**: Exploring the possibility of AI-driven content suggestions.
- **Content Discovery**: Considering integration with popular services for a richer library.
- **Sharing and Social Features**: Options to share playlists or songs, with privacy in mind.
- **Custom Shortcuts**: Tailoring NOVA to fit your workflow with customizable keyboard shortcuts.
- **Audio Quality Improvements**: Investigating audio normalization and other quality enhancements.
- **Gesture Controls**: Intuitive controls for mobile users and efficient navigation through tracks.

## Future Direction
While aiming to make NOVA versatile, there are currently no plans for developing a native mobile app, focusing instead on ensuring broad access through a hybrid approach.

## Support

Your feedback and suggestions are welcome. While the source code of NOVA is not publicly available, I am keen
to hear your ideas for features or improvements. If you encounter any issues or have feature requests, please reach out
through the issue tracker associated with the download platform.

## Acknowledgments

- Special thanks to Vue.js for powering the app's dynamic interfaces.
- Gratitude to Electron for enabling cross-platform desktop app development.

