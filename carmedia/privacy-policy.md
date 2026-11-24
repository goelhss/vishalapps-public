# CarMedia Privacy Policy

Effective date: November 24, 2026

CarMedia is a personal music and podcast application with optional user-enabled tools. It does not include advertising. The optional Gemini Nano feature uses Google ML Kit, whose diagnostic collection is described below. CarMedia is an independent application and is not affiliated with Google, Finnhub, Sigma, participating libraries, or podcast publishers.

The developer does not receive or sell your schedule text or Nano output. Google ML Kit collects SDK diagnostics when initialized for the optional Nano feature, as described below. Any network transfers described below go directly from the user's device to a service the user has chosen for the requested feature, such as the user's own Google Drive account, a media search provider, a podcast publisher, Finnhub, Sigma, or a selected library catalog.

## Music And Podcasts

CarMedia reads music files or folders that the user permits Android to expose. Music metadata, favourites, queues, and playback state are stored on the device. When the user chooses to find a podcast by name, the app sends the search term and storefront country to Apple's podcast directory. The search term can include a spelling or name variant suggested on the device. The app checks the selected public feed with its publisher before it is added. Feed and episode requests go to their publishers for verification, refresh, download, or playback.

Lyrics search sends the song title and, when available, artist name to LRCLIB. If the user tries alternate titles, the app sends the selected search terms suggested on the device. It sends no music files or folder paths to the directory or lyrics service. These services and publishers receive standard connection information such as the device IP address.

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

## Optional Gemini Nano and Local Prompts

When a user runs a feature that uses Nano, such as Read via LLM, Ask, or an alternate media lookup, PersonalConsole initializes Google ML Kit once per app process and may download or prepare Gemini Nano through Android's AICore service. At the user's request, the on-device model receives bounded public Sigma schedule text, available local Google Calendar records or saved church assignments, or the text typed/dictated into Ask LLM. For media assistance, the model uses the entered show name, the song filename and its title and artist tags, or the spoken podcast request and saved show names, depending on which action the user takes. The model runs locally. When the app uses a suggested term for a directory or lyrics search, that term is sent as described above. The Dictate control uses on-device speech recognition when available; it does not silently fall back to cloud speech. Prompt text and generated responses are processed on-device and are not sent to a cloud inference service. Calendar results are validated and displayed temporarily; they do not overwrite saved or manual schedules. General prompt drafts and completed responses may be retained in private activity saved state during navigation/recreation; no permanent chat-history store is created. The model has no app-control tools and cannot bypass website logins.

Google documents that ML Kit collects device and application information, user/device or other identifiers and per-installation identifiers, performance metrics, API configuration, input/output sizes, feature versions, event types and error codes for diagnostics and usage analytics. This SDK collection is separate from PersonalConsole's optional local diagnostic logs. The app defers ML Kit initialization until a feature requests Nano; users can use the app without this feature. Google encrypts this collected diagnostic data in transit and states that it is not transferred to third parties. See [Google's ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure) and [ML Kit terms and privacy](https://developers.google.com/ml-kit/terms).

## Permissions And Retention

CarMedia explains access immediately before opening Android's permission dialog or picker and offers a Not now choice. Audio-library permission is used only to find and play local audio. Voice-command microphone access does not save command audio in CarMedia, while Voice Memo access records a file in private app storage. Camera capture is performed by the phone's camera app and returns only the captured image. Android's photo and folder pickers grant CarMedia access only to the items or locations the user selects.

Permissions can be revoked in Android Settings. App data, downloads, credentials, logs, and backups can be deleted from their corresponding in-app controls or by clearing or uninstalling the app. Google Drive backup is manual and runs only after the user taps Back up now.

## Contact

For privacy or support questions, contact Vishal Goel at goelhss@yahoo.com.

Copyright (c) 2026 Vishal Goel. All rights reserved.
