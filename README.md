# Anki #5502 evidence

Before/after Android emulator screenshots: AnkiDroid 2.25.0alpha4 (Anki 26.05), Android 16, WebView 133.0.6943.137, 19 parameters, portrait, 22.5px frontend text.

After applies `overflow-y: hidden` to the disabled FSRS textarea through remote WebView inspection. No APK was rebuilt. Field height stays 242px; scroll height falls from 308px to the 240px client height as removing the scrollbar restores wrapping width.

These images are evidence only and are not part of the upstream code diff.
