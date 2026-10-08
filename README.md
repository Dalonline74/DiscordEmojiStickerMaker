# Discord Emoji & Sticker Maker

Android app for turning normal images into Discord-ready emoji and static stickers.

## Current build
- Emoji preset: 128×128 PNG
- Sticker preset: 320×320 PNG
- Image picker, drag and pinch-to-zoom
- On-device ML Kit subject/background removal
- Optional white sticker outline
- Export to Pictures/DiscordMaker
- Android share sheet

The Android source package is stored in `source/` as Base64 ZIP parts so GitHub Actions can reconstruct and build the project reliably.

Open **Actions → Build Android APK** to see APK builds. Successful builds publish a **DiscordEmojiStickerMaker-debug** artifact containing `app-debug.apk`.
