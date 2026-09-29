# Privacy Policy - Beam of Light

**Last Updated:** September 22, 2026

## Summary

Beam of Light has no accounts and never asks for your name, e-mail or phone number. There are no ads, no advertising SDKs and no in-app purchases. We collect anonymous statistics about how levels are played so we can balance the game, and we never track you across other apps or websites.

## What we collect

To understand how the game is played we use **Google Analytics for Firebase**. It records five events:

- `level_start`, `level_resume`, `level_pause`, `level_end` — one measurement per attempt at a level
- `play_day` — a count of distinct days on which the game was opened

Each event carries only gameplay facts:

- Which level: its internal name and number, the challenge type, the board shape, and a hash of the level layout used to tell revised levels apart
- How the attempt went: seconds actively spent, number of moves, number of mistakes, beams remaining, and whether the attempt succeeded, failed, was restarted or paused
- Broad progress: how many days you have played, the highest level you have reached, and the highest level you have completed
- Which build: whether the app is a public release or a test build

Alongside these, the Analytics SDK automatically collects an **app-instance identifier** (a random value generated on install), the app version, device model, operating system, language, and a coarse country or region derived from your masked IP address. All of it travels encrypted over TLS.

Each attempt also carries a randomly generated attempt identifier. It exists so that a single attempt's events can be joined together, and it is not connected to you or to any other attempt.

## What we do not collect

We do not collect your name, e-mail address, phone number, contacts, photos, calendar, files or precise location. The game requests no device permissions other than vibration.

We do not use an advertising identifier. On Android the `AD_ID` permission is explicitly removed from the app, and on both platforms the Analytics SDK is started with ad storage, ad user data and ad personalisation all switched off. Nothing the game collects is used for advertising, and no data broker or advertising network receives it.

There are no in-app purchases, no leaderboards and no account system, so there is nothing to bill, rank or sign in to.

## What stays on your device

Your chosen language, sound and haptic settings, reduced-motion preference, level progress and whether you have seen the tutorial are stored locally through your device's own storage. This save data is not uploaded to us.

## Who processes the data

Google processes the analytics data on our behalf ([Google Privacy Policy](https://policies.google.com/privacy)). Apple and Google also process the app distribution itself as the operators of the App Store and Google Play. We do not sell data and we do not share it with advertisers.

## Legal basis and retention

Where the GDPR or the Turkish KVKK applies, our legal basis is legitimate interest in understanding and balancing level difficulty. Analytics records are kept for the retention period configured in our Firebase project, which does not exceed 14 months, and are then deleted automatically.

## Children's privacy

The game is suitable for all ages. We do not knowingly collect personal information from children, and the statistics we collect are not linked to an identity.

## Your choices

The game currently has no in-app switch for analytics. Deleting the app stops all collection and invalidates the app-instance identifier; reinstalling creates a new one, unconnected to the old.

For questions, corrections or a deletion request, write to the address below and tell us the approximate dates and the device you played on, so that we can locate the anonymous records.

## Changes to this policy

If the game changes what it collects, this document and its date will be updated before the new version is released.

## Contact

- **E-mail:** akinalpfdn@gmail.com
- **Website:** https://akinalpfdn.com
