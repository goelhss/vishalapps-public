# CarMedia Privacy Policy

Effective date: September 4, 2026

CarMedia is a personal music and podcast application with optional user-enabled tools. It does not include advertising or an analytics SDK. CarMedia is an independent application and is not affiliated with Google, Finnhub, Sigma, participating libraries, or podcast publishers.

## Music And Podcasts

CarMedia reads music files or folders that the user permits Android to expose. Music metadata, favourites, queues, and playback state are stored on the device. Podcast feeds and audio are requested from their publishers only when the user refreshes or plays them. Those providers receive normal network information such as the device IP address.

## Accounts, Credentials, And Backups

Library usernames may be stored locally and are included with ordinary settings backups. Library passwords stay in the phone's selected password manager or encrypted local credential store unless the user explicitly selects credential inclusion for an encrypted backup.

Portable `.cmcfg` files are encrypted with a user-supplied Decode key. If the user connects Google Drive backup, CarMedia requests only the private Drive app-data permission and keeps one app backup hidden from normal My Drive. The default keyless Google backup excludes passwords and API keys. Optional credential backup encrypts the complete payload with a user-supplied Decode key. CarMedia never includes Google OAuth tokens, biometric Decode-key material, device identifiers, diagnostics, or transient caches in these backups.

## Optional Features

Optional features are disabled on a new installation and are enabled only by the user.

- Stocks sends requested ticker symbols and the user's own Finnhub API key to Finnhub. The key is stored securely on the device and is excluded from ordinary backups. CarMedia does not bundle a shared key, redistribute a common data feed, or provide investment advice.
- Sigma Schedule requests public schedule data from Sigma Martial Arts.
- Library Cards generates Codabar barcodes locally from saved numeric card numbers and connects to a selected catalog only when the user chooses a catalog action. Users may save custom HTTPS library links. CarMedia identifies and confirms a custom destination before trying saved credentials there.
- Voice controls and Voice Memos request microphone access only when used. System speech recognition is handled by the recognition provider configured on the phone.
- Feature Requests can use user-selected folders and photos. Files are created or shared only after a user action.
- Diagnostics are off by default. If enabled, logs may contain media names or folder information and leave the device only when the user shares them.

## Permissions And Retention

CarMedia explains access immediately before opening Android's permission dialog or picker and offers a Not now choice. Audio-library permission is used only to find and play local audio. Voice-command microphone access does not save command audio in CarMedia, while Voice Memo access records a file in private app storage. Camera capture is performed by the phone's camera app and returns only the captured image. Android's photo and folder pickers grant CarMedia access only to the items or locations the user selects.

Permissions can be revoked in Android Settings. App data, downloads, credentials, logs, and backups can be deleted from their corresponding in-app controls or by clearing or uninstalling the app. Google Drive backup is manual and runs only after the user taps Back up now.

## Contact

For privacy or support questions, contact Vishal Goel at goelhss@yahoo.com.

Copyright (c) 2026 Vishal Goel. All rights reserved.
