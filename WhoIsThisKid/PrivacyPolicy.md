# Privacy Policy — Who Is This Kid

_Last updated: 28 October 2026_

_Also available in: [Українська](https://github.com/Oneekz/Legal/blob/main/WhoIsThisKid/PrivacyPolicy_ua.md)_

Who Is This Kid keeps a family tree: relatives, birthdays, marriages and, with Premium, portraits that grow up over the years. It is built so that we can’t read any of it. This page says what the iPhone, iPad and Android apps and their server at family.oneekz.com handle, and what they don’t.

## Who we are

The app is made and run by Oneekz Productions LLC. Write to oneekz.productions [at] gmail [dot] com with any question about your data.

## End-to-end encryption

Everything you write in a tree, every photo, the colours chosen for each person and the names you give your devices are encrypted on your device before they leave it, with a key that only the tree’s devices hold. The key travels inside invite and device links, in the part after the “#”, which apps and browsers never send to any server. Our server stores the encrypted data and passes it between the tree’s devices, but it can’t open it. Neither can our hosting provider, Cloudflare, which carries the traffic, or anyone who gets a copy of the server.

So we never see names, dates, relations, photos, measurements, the tree’s name, device names or anything else you type.

## What the server does see

- Random ids for each tree, member, device and invite, each member’s role (owner, co-admin, editor, view-only), and when each member and device was added and last online.
- For each device, a public key it makes when it joins and a fingerprint (a one-way hash) of its access token. A device restored from iCloud Keychain or Google’s backup also has a recovery grant, stored the same way. A request to connect another device lasts 10 minutes and holds only encrypted data.
- How many records and photos a tree has, their sizes, and when they changed. Old versions are kept for 90 days, so the owner can undo changes.
- Whether a tree has Premium, until when, and where it comes from. For a subscription, that includes the identifiers Apple or Google give the purchase, the product, and its expiry and status, which the server checks with Apple or Google. It never learns who paid: no Apple ID, Google account, name, email or country.

There are no accounts. We don’t ask for or store your name, email address, phone number or a password.

## IP addresses

The server uses your IP address for a moment, to limit how many requests one network can make. It doesn’t store it. The web server in front of it writes an access log with IP addresses and the pages asked for, with invite codes and tree ids blanked out. That log is kept for a short time and then deleted as it rotates.

## On your device

Your device keeps a decrypted copy of the tree so it works offline. That copy is kept out of iCloud and Android backups. The tree’s key and your device’s access are kept in its secure storage. On an iPhone or iPad, iCloud Keychain can carry an encrypted recovery grant to your other Apple devices. On Android, Google’s Block Store carries it to a new phone only when Google can back it up with end-to-end encryption.

Portraits are taken and cropped on the device. Face guides in the camera, and the hair colour the 3D figures take from a portrait, are worked out on the device and never sent anywhere. Birthday and anniversary reminders are scheduled on the device itself. Nothing about them goes to the server.

## Payments

Premium is bought through the App Store or Google Play. Apple or Google handle the payment, and we never see your card or billing details. See Apple’s and Google’s privacy policies for what they keep.

## Google’s ML Kit on Android

The Android app uses Google’s ML Kit, inside the app, to find faces for the camera’s guides. Your photos stay on the phone. ML Kit itself sends Google diagnostics so Google can keep it working: the device model and Android version, the app’s name and version, an identifier for this installation that isn’t meant to identify you or your phone, and how the face finder performed (speed, image size and errors). It is sent encrypted and Google doesn’t pass it on. The iPhone and iPad apps use Apple’s own face detection, which sends nothing.

## What we don’t do

No advertising, no analytics of our own, no tracking across apps or websites, and no selling or sharing of data. The app contains no advertising or tracking code.

## Children

Families use the app to keep their children’s birthdays and portraits. That information is entered by relatives, and it is end-to-end encrypted like everything else. The app is meant to be run by adults: an invite for a child under 12 isn’t offered.

## How long data is kept

- Disconnecting a device ends that device’s access straight away; your other devices keep working.
- Leaving a tree ends your access on all your devices straight away. What you added stays in the family’s tree.
- When the owner deletes a tree, the server deletes all of it, photos included, straight away.
- If Premium ends, server photos stay available for 90 days, then are deleted. Downloaded photos stay on your phone.
- The server keeps each person’s current portrait. Older portraits stay on phones that downloaded them.
- Earlier versions of records are deleted after 90 days.
- Nightly copies of the server, which hold only encrypted data, are kept for 7 days.

## Where the data is

The server runs at Hetzner, in the United States, behind Cloudflare.

## Your rights

You can see, change and delete what’s in your tree in the app, depending on your role in it. Because we can’t read the contents, the app is also the only place they can be shown or corrected. For anything else, such as the metadata above, write to oneekz.productions [at] gmail [dot] com.

## Changes

If this policy changes, the new version appears here with its date.
