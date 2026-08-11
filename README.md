# LNRO Intake PWA v2

Mobile-first Progressive Web App for Paul Davis LNRO Intake.

## Improvements
- Professional LNRO app shell and Home Screen experience
- Mobile bottom navigation: New Intake, Saved, Settings
- Saved Intakes manager with Open/Delete actions
- Current-draft autosave to local device storage
- Draft restore/dismiss workflow
- Offline/online status indicator
- Local JSON backup export
- Existing PDF, Excel, email, territory lookup, map, and intake functionality preserved

## Deploy
Publish the contents of this folder to an HTTPS GitHub Pages site. Open the published site in Safari and use Share → Add to Home Screen.


## v4 route feature
- Office start: 3135 Carroll Ave, Suite A, Lynchburg, VA 24501.
- Uses OpenStreetMap Nominatim to geocode the office when needed.
- Uses OSRM driving routing to draw the fastest route to the selected job address and show distance/time.
- Route services require internet access.


### PDF redesign
The Create PDF actions now generate a more professional Paul Davis/LNRO-branded report with bold section headers, structured field cards, improved typography, pagination, territory/routing summary, and internal-use footer.
