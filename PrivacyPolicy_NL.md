# Privacy Policy for Railveal for iOS

Last updated: October 24, 2026

Railveal is a map app for viewing Dutch railway infrastructure on iPhone and iPad, with Siri, Shortcuts and CarPlay integration.

## Location and permissions

With your permission, Railveal uses your current location to center the map, determine nearby railway geocode and kilometrage information, and find nearby crossings or access points. This also applies to location features you invoke through Siri, Shortcuts or CarPlay. The app requests location access while in use and the best available accuracy; the actual accuracy depends on your iOS permissions and location conditions.

You can deny or revoke location access in iOS Settings. Manual map browsing and searching remain available. Railveal does not record a location history or request always-on background location access.

## Accounts and tracking

Railveal does not create user accounts, use advertising identifiers, display advertisements or include analytics or tracking services. It does not operate its own backend for storing your personal data.

## Network requests and external services

Railveal communicates directly with the services needed for the feature you use:

- **ProRail:** railway infrastructure, aerial imagery, cadastral data, geocodes and kilometrage. Requests can contain the visible map area, a selected coordinate, your current coordinate for location features, or a geocode and kilometer value you entered.
- **Apple MapKit:** the base map and address geocoding. Address searches are submitted to Apple's geocoding service to obtain a coordinate.
- **PDOK:** map images for the optional nationwide aerial-photo layer, requested for the relevant map area.
- **Apple Maps:** when you request navigation, including through Siri or CarPlay, Railveal passes the destination to Apple Maps and requests driving directions. For some selected locations near railway tracks, this destination is a suitable nearby gate or crossing rather than the selected point.
- **Google Maps or Apple Maps route links:** QR codes contain a driving-directions link with destination coordinates and, where included, a destination name. The QR image is generated on the device without contacting a QR-code service. Opening the encoded link sends the destination to the selected maps service. Anyone who scans the code can read its destination.
- **Spoor in Beeld / Georizon:** tapping the perspective button opens the external viewer with the selected location's RD coordinates in the URL.

As with normal internet requests, these providers can receive technical information such as an IP address, request time and requested resource. Their own privacy policies and retention practices apply. Railveal does not control their server logs.

## Local storage and retention

- **Favorites:** objects you explicitly save are stored locally in app preferences, including their coordinates, names, details and any associated navigation destination. They remain available across app sessions until you remove them using the star in the object details. Railveal does not synchronize them through its own server.
- **Siri and Shortcuts handoff:** pending actions and their selected objects or result lists can be stored locally so the app can continue an invoked action. The app accepts these handoffs for five minutes; it clears them when consumed or when subsequently read as expired. This is not a guarantee of deletion by a background timer after five minutes.
- **Other session data:** ordinary search text, results, map selections, measurements and current-location information are held for app operation and are not saved as a location history. Saving an object as a favorite is the explicit exception for selected objects.
- **Caches and device backups:** map and network components may cache data. iOS manages those caches and may include app data in device backups according to your device settings. Railveal does not provide its own cloud backup service.

## Clipboard and user-controlled sharing

When you tap a copy button, Railveal places the displayed RD coordinates, or measurement endpoints and distance, on the system clipboard. Other apps can receive that text when you paste it; system clipboard features are controlled by iOS. Displaying a QR code makes its destination available to anyone who scans it.

Siri and Shortcuts interactions are also subject to your Apple settings and Apple's handling of those services.

## Data sources

Railway infrastructure and cadastral data are supplied by ProRail with CC BY 4.0 attribution. The optional aerial layer is supplied by PDOK/Beeldmateriaal with CC BY 4.0 attribution. Apple supplies MapKit map and geocoding functionality. Attribution is shown in the app.

## Contact

For privacy questions about Railveal, contact FLI.
