# Svara privacy

Last updated: September 19, 2026. This policy describes Svara 1.0 (build 7), submitted for App Review.

## Audio stays on your Mac

Svara processes and saves recordings locally. It has no audio upload feature, advertising, analytics SDK, Svara account, or cloud transcription service. If you save a file into an iCloud Drive or other synced folder, that provider may sync it independently of Svara.

## Recording permission

macOS asks for Screen & System Audio Recording permission. Svara uses Apple's capture framework to obtain audio from the application you choose. It registers audio output only, saves no screen frames, and does not record the microphone. Other audible tabs in the selected browser may be included.

## Local settings and library

Svara stores recording preferences, presets, and its library on your Mac. Library information includes titles, source application names, dates, filenames, and security bookmarks that let the app reopen files you selected. Editing a library title does not rename the underlying file. Removing a library entry leaves the audio file in place.

## Purchases

The Pro purchase is handled by Apple through the Mac App Store. Svara uses Apple-verified transaction information to determine whether Pro is unlocked and to restore purchases. Payment details are handled by Apple and are not sent to a Svara-operated server. Svara does not operate a purchase backend or collect your Apple Account password.

## Your controls

You can stop a recording at any time, remove library entries, delete audio files through Finder, and revoke recording permission in System Settings → Privacy & Security → Screen & System Audio Recording.

## Support

For privacy questions, use [GitHub support](https://github.com/pstarwars2026/svara/issues/new/choose). If you contact support through GitHub, the information you post is public and handled by GitHub. Do not include recordings, receipts, credentials, or personal information.

GitHub processes information you choose to submit in issues under its own policies. Issues are public. Do not post private recordings, credentials, personal file paths, or payment receipts. See [Support](SUPPORT.md) for the information useful in a bug report.

## Daily Free allowance

Svara stores daily recording usage, its reset schedule, and clock checkpoints locally in macOS Keychain. This record is separate from preferences, is not synchronized to other Macs, and is not sent to us. Pro has no daily allowance.
