---
title: Privacy Policy
permalink: /privacy
---

# Privacy Policy — Geòlas

*Last updated: 15 November 2026*

Geòlas keeps your field notes to yourself. There is no Geòlas account, no Geòlas server, and no sign-in.

## What the app stores, and where

Your sites, samples, formations, notes, photos and voice notes are kept in a database inside the app's own container on your device.

If you're signed in to iCloud, the same data is also kept in your own iCloud account, so the same notes are on your iPhone, your iPad and your Mac. It goes into your account's private CloudKit database. Apple encrypts it, the developer has no access to it and no way to ask for access, and no other Geòlas user can reach it.

## What leaves your device, and why

Geòlas talks to the network for these things, all standard HTTPS:

- Geology lookups. When you log a site with "Look up the geology" switched on, or tap "Look up the geology" or "Fetch again" on a site, its coordinates — not your name or any identifier — are sent to the public map service of the geological survey that covers that point, to ask what bedrock and surface geology are there. That is the British Geological Survey for Great Britain; the Geological Survey of Northern Ireland (GSNI) for Northern Ireland, whose map service is hosted by the British Geological Survey; and Geological Survey Ireland for the Republic of Ireland. For a point close to the Northern Ireland border, both GSNI and Geological Survey Ireland may be asked. The request carries the coordinates, as a small box around the point, and, as with any web request, your device's IP address.
- Place search. Searching for a place name sends that search text to Apple Maps, or, if you switch it on, OpenStreetMap's Nominatim service, to find its coordinates.
- Notable geology nearby. When you open "Notable geology near here" from the map or a site, the point being searched around — where you are, the map's crosshair, or the site — and the distance you chose are sent to Geofabrik's Postpass service (a public OpenStreetMap database; if it doesn't answer, OpenStreetMap's Overpass service instead) and to the Wikidata query service, to find geological features near it. As with any web request, your device's IP address is seen too. Nothing else is sent: no name, no identifier, none of your notes. With no signal, only the places already inside Geòlas are listed and nothing is sent.
- Pages opened inside the app. Reference maps, the geological timescale, the BGS Geology Viewer, geopark boards, GeoGuide, and the Wikipedia, Wikidata and OpenStreetMap pages linked from "Notable geology near here" all load from their publishers' own websites, which see the request as they would from any browser. For the BGS viewer, the site's coordinates are part of the web address. For GeoGuide, the point you searched around is passed to its map inside the page, so that the map opens there.
- Other map apps. "Directions in Apple Maps", "Open in OS Maps" and "Open in Outdooractive" hand the place's coordinates to that app or website, under its own privacy policy.
- iCloud sync, described above — between your devices and your own iCloud account, under Apple's privacy policy, not this one.

None of this is linked to your identity by the developer, because the developer never sees it — these are direct requests from your device to each service, which has its own privacy policy. The one thing that does reach the developer is feedback you choose to send, described next.

## Feedback you send

Some pages have a feedback button, for suggesting a correction or an idea about Geòlas's own reference content — a reference site, a geopark board, a simulation — or about the app in general. It is never about your own sites or notes, and nothing is sent unless you write a message and tap Send.

If you're signed in to iCloud, your message is saved in Geòlas's iCloud database for the developer to read. It holds what you wrote, the name you give if you choose to give one, which page it's about (with what that page showed), and the app's version number. Apple adds an anonymous identifier for your iCloud account that is unique to Geòlas; it is not your name or your Apple ID, and the developer cannot turn it into either. If iCloud isn't available, the button opens your email app with the message filled in instead, and it is sent as an ordinary email from your own address.

Feedback is used only to improve Geòlas. To have any feedback you've sent removed, write to the address below.

## What the app does not do

- No analytics, telemetry or crash reporting.
- No advertising, and no advertising identifier.
- No tracking, and no data sold or shared with any other company.
- No Geòlas account, and no name or email address collected — unless you put one in feedback you choose to send.
- No third-party SDKs.

## Camera, microphone and location

Camera and microphone are used only when you choose to attach a photo or record a spoken note to a site — nothing is captured otherwise. Location is used to place a site on the map and to centre the map on you; it is stored as part of that site's own record, not tracked in the background.

## Reference content

The curated geological sites and the glossary are bundled inside the app and need no network connection to browse.

## Files you share out

Exporting your sites as JSON or GeoJSON uses the standard share sheet, so the file goes wherever you choose to send it and nowhere else.

## Children

Geòlas has no accounts, no messaging, and no user-generated content visible to anyone else. It collects nothing from anyone of any age beyond what's described above: everything except feedback you choose to send stays on your own device and in your own iCloud account.

## Coverage

Geology lookups cover Great Britain (British Geological Survey, bedrock and superficial deposits), Northern Ireland (Geological Survey of Northern Ireland, 1:250,000 bedrock and superficial deposits) and the Republic of Ireland (Geological Survey Ireland, 1:100,000 bedrock only). Sites can be logged anywhere; outside these areas Geòlas does not look up geology.

## Changes

If this ever stops being true, the policy will be updated before the change ships, and the date at the top will say when.

## Contact

Questions about privacy, or about the app: 88_intake.troupes@icloud.com
