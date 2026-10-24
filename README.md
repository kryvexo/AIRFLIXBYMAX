# Airflix Max

A polished Android media player for browsing and playing content from sources you choose.

[![Latest release](https://img.shields.io/github/v/release/kryvexo/AIRFLIXBYMAX?display_name=tag&sort=semver)](https://github.com/kryvexo/AIRFLIXBYMAX/releases/latest)
[![Android](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)](https://www.android.com/)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache--2.0-blue.svg)](LICENSE)

## Download

Get the latest APK from the [GitHub Releases page](https://github.com/kryvexo/AIRFLIXBYMAX/releases/latest). The current release is [Airflix Max v1.0.2](https://github.com/kryvexo/AIRFLIXBYMAX/releases/tag/v1.0.2).

To install, download the APK on your Android device, allow installation from that source if Android asks, and open the downloaded file.

## Features

- Browse, search, and keep track of movies and series.
- Stream through available content sources and continue playback from your progress.
- Use audio tracks and subtitles when the selected stream provides them.
- Choose Auto/adaptive playback or manually select a resolution offered by the selected stream.
- Use watchlist, downloads, external player, and external downloader features where available.
- Customize the app's appearance and playback preferences.
- Check for app updates from the GitHub Releases source in Settings.
- View a polished About screen with developer and project links.

## Video quality

The player displays the video tracks actually exposed by the selected source and supported by the device, with the highest available option shown first. Auto mode adapts to playback conditions; manual selection requests an available resolution.

Available quality can vary by title, source, network, and device decoding capabilities. If a stream only provides 720p, selecting 4K or 8K cannot create those missing versions or upscale the stream into genuine higher-resolution video.

## App information

| Property | Value |
| --- | --- |
| App name | Airflix Max |
| Current version | 1.0.2 |
| Android application ID | `com.max.airflix` |
| Minimum Android version | Android 9 (API 28) |

## Build from source

### Requirements

- Node.js and npm (use versions supported by the installed Expo SDK)
- Java Development Kit (JDK) 17
- Android Studio / Android SDK and an Android emulator or device

### Run on Android

```bash
git clone https://github.com/kryvexo/AIRFLIXBYMAX.git
cd AIRFLIXBYMAX
npm ci
npm run android
```

The `android` script prepares the project runtime and launches the Expo Android development build. For a production-signed APK, configure your own Android signing credentials; do not use a debug key for distribution.

### Checks

```bash
npm run lint
npm test
```

## Privacy and content notice

Airflix is a media player. It does not host, store, or distribute movies, shows, or other media. Content availability and rights are determined by the sources selected by the user. Use only sources and content that you are authorized to access, and follow applicable laws and source terms.

## Support and links

- Project and issue reports: [github.com/kryvexo/AIRFLIXBYMAX](https://github.com/kryvexo/AIRFLIXBYMAX)
- Developer GitHub: [github.com/kryvexo](https://github.com/kryvexo)
- Telegram: [@kryvexo](https://t.me/kryvexo)
- Instagram: [@maxgotiissues](https://instagram.com/maxgotiissues)
- Website: [maxown.online](https://maxown.online)

## License

This project is provided under the Apache License 2.0. See [LICENSE](LICENSE) for the license text and applicable notices.
