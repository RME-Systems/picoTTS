# PicoTTS for Android (5.0 to 16+)

A standalone port of the classic SVOX Pico TTS Engine from AOSP, updated for modern Android devices with broad compatibility from **Android 5.0 (API 21) up to Android 16+ (API 36)**.

## Features

- **Broad compatibility**: Works on Android 5.0 (Lollipop) through Android 16+.
- **16 KB page size support**: Compatible with Android 15+ kernels.
- **Multi-architecture**: Full native support for `arm64-v8a`, `armeabi-v7a`, `x86`, and `x86_64`.
- **Supported languages (6 voices)**:
  - 🇩🇪 German (`de-DE`)
  - 🇬🇧 English UK (`en-GB`)
  - 🇺🇸 English US (`en-US`)
  - 🇪🇸 Spanish (`es-ES`) — *with automatic matching for Latin American and US Spanish locales*.
  - 🇫🇷 French (`fr-FR`)
  - 🇮🇹 Italian (`it-IT`)
- **TalkBack & Accessibility safe**:
  - Automatically matches regional variants (e.g., `es-US`, `es-MX`, `es-CL` use the Spanish voice).
  - Safety fallback to English for unsupported system languages (e.g., Portuguese) so screen readers never go silent.
- **Instant setup**: Voice packs are extracted automatically on first start — **no device reboot required**.

## Installation

Just install the APK and select PicoTTS as your preferred engine in Android Text-to-speech settings.

## Credits & Acknowledgments

- **SVOX AG & Google / AOSP**: Original creators and maintainers of the SVOX Pico Text-To-Speech engine.
- [ericJrdn/picoTTS](https://github.com/ericJrdn/picoTTS): Initial rework to run PicoTTS as a standalone application on Android 9+.
- [IsHacker003/picoTTS](https://github.com/IsHacker003/picoTTS): Fork from which this repository originates.
