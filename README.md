# GoogleMaps-2-AppleMaps
This Shortcut script automatically extracts in bulk the Saved Places .json data from Google data export and adds the places (with a prompt) in Apple Maps. Primarily intended for macOS rather than iOS.

Intended uses:
- You have a Google account with saved (or "starred") places on Google Maps that you'd like to export/import into Apple Maps

How to use:
1. Navigate to https://takeout.google.com/
2. Click "Deselect All" and create a takeout that only uses the "Maps (your places)" data selected
3. Proceed with generating your Google Takeout request, wait for it to be processed and available for download
4. Download and extract the file that you get from Google
5. Open the Saved Places.json file with a text viewer of your choice (e.g. Sublim Text) 
6. Download this Shortcuts script: https://www.icloud.com/shortcuts/b70812c989a148d084b070ef4772988e
7. Copy paste your locations' .json text instead of the sample in this Shortcut
8. Follow the on-screen instructions to go through all your Google Maps saved places

Feature request or comments? Open a PR/Issue! :) 
