# Svara support

Svara 1.0 (build 9) and Svara Pro were resubmitted September 26, 2026 and showed Waiting for Review. Public app downloads are not available yet.

For support, use [GitHub support](https://github.com/pstarwars2026/svara/issues/new/choose). Issues are public: do not post recordings, purchase receipts, credentials, or personal information.

For a bug report or feature suggestion, [open a GitHub issue](https://github.com/pstarwars2026/svara/issues/new/choose). Include:

- macOS version and whether your Mac uses Apple silicon or Intel.
- Svara version, recording format, and a generic source-app name.
- What you expected, what happened, and short steps to reproduce it.
- An error message with personal details removed.

Do not post audio recordings, purchase receipts, credentials, or personal paths. If reporting an audio problem, describe it in words first.

## Recording access

Choose **Refresh Apps** when you want to select an audio source. This invokes Apple’s capture framework, which may show macOS’s native Screen & System Audio Recording permission request. Svara explains why it uses access and does not redirect you to System Settings. It saves audio only, without microphone audio or screen video.

If access is not granted, no recording starts and the app remains available. If you later change recording access in macOS, reopen Svara and choose Refresh Apps.

## Files and recordings

Browser capture can include all audible tabs in the selected browser. Unexpected silence may come from the source app or its recording restrictions. Svara does not unlock protected media.

Let Stop & Save finish before quitting. Force-quitting, losing power, or disconnecting the destination drive can leave an incomplete recording. Keep any partial file until you know whether it can be recovered.

## Pro purchases

Pro is a US $2.99 one-time Mac App Store purchase, with localized regional pricing. Restore Purchases is available in the Pro window and Svara application menu for the Apple Account that purchased it. There is no external purchase page or license-key seller.

## Free daily allowance

Free includes 10 minutes total per day across recording sessions on this Mac. Silence while recording counts too. The app shows the remaining time and next reset, and automatically stops and saves at the limit or reset. Start a new recording after the reset to continue. Pro removes this limit.

The reset schedule uses the timezone from initial setup; travel does not grant an additional allowance. Usage is stored locally in Keychain and survives restarting the app or resetting preferences. If the app closes unexpectedly, up to one second of reserved time may remain charged. Playback does not consume recording time.

If the allowance cannot be read, unlock your Mac and retry. Contact support if the error persists; include the displayed message without sharing Keychain data.
