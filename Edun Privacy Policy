# Edun Privacy Policy

**Last updated: 7 September 2026**

Edun is a step-tracking app. It reads how much you have walked, keeps a record
of it so you can look back, and lets you compare that record with people you
choose to compare it with.

This policy explains exactly what leaves your phone, who can see it, and how to
get rid of it.

## Who we are

Edun is made and operated by **Akınalp Fidan**, an individual developer in
Türkiye. There is no company behind it.

For anything in this policy, write to **akinalpfdn@gmail.com**.

## How you sign in

Edun uses **Sign in with Apple** and nothing else. There is no password to
choose and no password for Edun to store.

Apple gives Edun two things: an identifier that means "this person", which is
unique to Edun and useless anywhere else, and an email address. If you use
Apple's *Hide My Email*, that address is a relay Apple generates for Edun alone,
and Edun never learns your real one.

You then pick a username and a display name. Those are yours to choose and are
what other people see.

## What Edun collects

### From Apple Health, with your permission

Edun asks iOS for read access to three things:

| | |
|---|---|
| Step count | the number the whole app is built around |
| Walking and running distance | shown beside your step count |
| Flights climbed | shown beside your step count, and left blank when Health has none |

Edun only ever **reads** from Health. It never writes to it, and it cannot see
anything you have not granted. You can withdraw that permission at any time in
**Settings › Privacy & Security › Health › Edun**, and the app keeps working —
the screens simply have nothing to draw.

### What is uploaded to the Edun server

Once you are signed in, the app sends your step record to the Edun server, so it
survives a new phone and so competitions can be scored:

- **A daily step total** for each calendar day, in your own local dates.
- **An hour-by-hour breakdown** of each day's steps. This is what draws the
  shape of your day on the Today screen and what decides the morning bonus.
- **The time-zone offset** the day was recorded in, so a day that starts in one
  country and ends in another still counts once.
- **A label saying where the figure came from** — for example `healthkit.iphone`.

When you first create an account, Edun imports up to the last 365 days, once.
After that it uploads the current day roughly every five minutes while the app
is open, and stops when you leave it.

Distance and flights are read from Health and shown on your phone. They are not
uploaded.

### Your account

| | |
|---|---|
| A username and display name | you choose both; other people see them |
| An email address | the one Apple returns, real or a Hide My Email relay |
| A sign-in identifier from Apple | the opaque subject in Apple's token — not your Apple ID or password |
| The date the account was created | |
| An internal account ID | a random UUID, meaningless outside Edun |

Sessions are kept as a hash of the token, never the token itself.

### What Edun works out from your walking

Level, experience points, current and longest streak, best single day, how many
days you met your goal, how many mornings you were out early, and how many times
you have broken your own record.

### Competition

Friendships and blocks; groups you belong to and invitations to them; duels you
have taken part in and their results; your position in a league season.

### Purchases

If you buy anything, Edun stores the transaction identifier Apple gives it and
what that purchase entitles you to. **Edun never sees your card, your billing
address, or anything else about the payment.** Those stay with Apple.

## What other people can see

This is the part most policies leave vague, so here it is in full. Anyone who
can open your profile in Edun — someone who searched for your username, a
friend, or a member of a group you are in — sees:

- your username and display name
- the date you first walked with Edun
- your lifetime steps and lifetime XP
- your best single day
- your current streak, goal days, morning days and record breaks
- your steps this week, this month and this year
- how many duels you have won

They do **not** see your email address, your hour-by-hour breakdown, or any
individual day other than your best. You can block someone, which ends any live
duel between you and takes away their access to your profile.

## Who else touches your data

Edun has no analytics, no advertising, and no third-party SDKs of any kind
inside the app. Your data reaches exactly these parties:

| Who | What they get | Why |
|---|---|---|
| **Cloudflare, Inc.** (US) | traffic between your phone and the server passes through it | it sits in front of the API and terminates the HTTPS connection |
| **A virtual server in the European Union** | everything listed above | the Edun server and its PostgreSQL database run there |
| **Apple** | a sign-in token; purchase receipts | Sign in with Apple; verifying what you bought |

Nothing is sold. Nothing is shared for advertising. Nothing goes to a data
broker.

## Health data specifically

Apple asks that this be said plainly, and it is true:

- Health data from Edun is **never used for advertising or marketing**.
- Health data from Edun is **never sold**, and never shared with anyone else for
  their own purposes.
- It is used only for the features described here: your own history, your
  progression, and the competitions you choose to enter.

## Where it is kept, and for how long

Your data sits in a PostgreSQL database on a virtual server in the European
Union, reached only over HTTPS.

It is kept until you delete your account. Revoked sessions are cleaned up
automatically well before that.

On your phone, Edun keeps your sign-in tokens in the iOS Keychain, and a small
amount of ordinary app state — your goal, your progression, whether you have
seen the introduction — in standard app storage. Deleting the app removes both.

## Deleting your account

You can delete your account from inside Edun. It is immediate, and it is not a
flag on a row that stays: the account is removed and the database deletes
everything hanging off it — your step history, your hourly breakdowns, your
progression, your friendships, blocks, group memberships, duels, devices and
entitlements.

There is no restore. If you sign up again afterwards, you start from nothing.

## What Edun does not do

Edun does not read your location, your contacts, your photos, your camera or
your microphone. It does not use the advertising identifier and never asks for
tracking permission, because it does not track you — across apps, across
websites, or at all. There are no advertisements in Edun.

## Children

Edun is not directed at children under 13 and does not knowingly collect data
from them. If you believe a child has created an account, write to
akinalpfdn@gmail.com and it will be deleted.

## Your rights

You can ask for a copy of what Edun holds about you, ask for it to be corrected,
or ask for it to be erased — the last of which you can also do yourself, in the
app, at any time. Write to **akinalpfdn@gmail.com** and you will get an answer
within 30 days.

If you are in Türkiye, these rights come from KVKK (Law No. 6698). Because the
server is in the European Union, your data is processed outside Türkiye; by
creating an account you consent to that transfer, and you can end it at any time
by deleting your account.

If you are in the European Economic Area or the United Kingdom, these rights
come from the GDPR. The lawful basis is the contract you enter by creating an
account, together with your explicit consent for health data.

## Changes

If this policy changes in a way that affects what is collected or who can see
it, the date at the top changes and the app tells you before the change takes
effect. Small corrections just update the date.

## Contact

**akinalpfdn@gmail.com**
