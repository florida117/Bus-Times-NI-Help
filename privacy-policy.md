# Privacy Policy — Bus Times NI

**Version 1.0 · 26 November 2026**

Applies to the Bus Times NI apps for iOS, iPadOS and Android.

Bus Times NI is an independent, unofficial app developed by Kurtis Bell. It is not
produced or published by Translink, Metro, Ulsterbus or Glider, and is not endorsed by or
affiliated with them.

## The short version

**The app collects no personal data.** There are no accounts, no sign-in, no analytics, no
advertising, and no tracking of any kind. Nothing you do in the app is reported back to the
developer, and no profile of you is built or held anywhere.

If you allow it, the app uses your location to find the bus stops near you and to plan a
journey from where you are. Your location is sent only in that request to Translink. It is
never stored, and never sent to the developer.

## What the app stores

Your favourite stops, starred routes and pinned buses, the direction you last viewed each
route in, and which route lists you have folded away are stored **on your device**. They
are not transmitted to the developer.

On iOS and iPadOS, favourite stops, starred routes and pinned buses also sync across your
own Apple devices through iCloud key-value storage. That sync happens inside your personal
iCloud account, which is controlled by you and governed by Apple's privacy policy: the
developer has no access to it and cannot see its contents. The Android app has no
equivalent sync; its data stays on the one device.

Uninstalling the app removes this data from the device.

## Your location

The app asks for permission to use your location while you are using it. You can say no:
every feature still works by searching for a stop instead.

If you allow it, your location is read only when you ask for it: when you look for stops
near you, or choose "Current location" in the journey planner. It is then sent to Translink
Open Data as part of that one request, so that Translink can answer with the stops or
journeys near you. The app does not track your location in the background, does not keep a
history of where you have been, and does not store your location at all once the answer
has arrived.

On Android you can allow approximate location instead of precise. The app still works, but
Android moves an approximate location by up to a couple of kilometres, so the nearest stops
it finds may not be the nearest to you.

## Data the app sends

To show live information, the app requests data from two Translink services:

- **Translink Open Data** (`opendata.translinkniplanner.co.uk`): stop search, departures,
  bus routes, journey planning, and stops near your location when you ask for them.
- **Translink service updates** (`www.translink.co.uk`): disruption notices.

These requests contain only what is needed to answer them: the stop, route or journey you
are looking at, and your location only when you have asked for stops or journeys near you.
They carry no name, no account, no device identifier and no advertising ID. The Translink
API key used is registered to the developer, not to you, and does not identify you.

Because these are network requests, Translink will see your device's IP address, as it
would for any internet request. Its handling of that is covered by its own privacy policy,
not this one. The app sends nothing to Translink beyond the request itself.

## What the app does not do

- It does not track your location in the background or store it.
- It does not access your contacts, photos, camera, microphone, calendar or files.
- It does not use analytics, crash-reporting or advertising SDKs of any kind.
- It does not share or sell data to anyone, because it holds none to share.

The Android app requests three permissions: `INTERNET`, and `ACCESS_FINE_LOCATION` and
`ACCESS_COARSE_LOCATION` for stops near you.

## Children

The app is not directed at children and collects no data from anyone, including children.

## Changes to this policy

Material changes will be published here with an updated version number and date. The
in-app link in each released version points at the policy as it stood when that version
shipped.

## Contact

See [contact details](https://github.com/florida117/Bus-Times-NI-Help/blob/main/contact-details.md)
