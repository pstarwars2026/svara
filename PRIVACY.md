# Svara privacy

Last updated: September 19, 2026. This describes the current development design; the policy will be checked against the final App Store release.

## Audio stays on your Mac

Svara processes and saves recordings locally. It has no audio upload feature, advertising, analytics SDK, Svara account, or cloud transcription service. If you save a file into an iCloud Drive or other synced folder, that provider may sync it independently of Svara.

## Recording permission

macOS asks for Screen & System Audio Recording permission. Svara uses Apple's capture framework to obtain audio from the application you choose. It registers audio output only, saves no screen frames, and does not record the microphone. Other audible tabs in the selected browser may be included.

## Local settings and library

Svara stores recording preferences, presets, and its library on your Mac. Library information includes titles, source application names, dates, filenames, and security bookmarks that let the app reopen files you selected. Editing a library title does not rename the underlying file. Removing a library entry leaves the audio file in place.

## Purchases

The planned Pro purchase is handled by Apple through the Mac App Store. Svara uses Apple-verified transaction information to determine whether Pro is unlocked and to restore purchases. Payment details are handled by Apple and are not sent to a Svara-operated server. Svara does not operate a purchase backend or collect your Apple Account password.

## Your controls

You can stop a recording at any time, remove library entries, delete audio files through Finder, and revoke recording permission in System Settings → Privacy & Security → Screen & System Audio Recording.

## Support

GitHub processes information you choose to submit in issues under its own policies. Issues are public. Do not post private recordings, credentials, personal file paths, or payment receipts. See [Support](SUPPORT.md) for the information useful in a bug report.
