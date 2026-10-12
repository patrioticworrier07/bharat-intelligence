# Bharat Intelligence — live-feed update

## Update your existing GitHub Pages site
1. Download and extract this ZIP on your phone.
2. Open https://github.com/patrioticworrier07/bharat-intelligence
3. Tap **Add file → Upload files**.
4. Upload the new `index.html`, replacing the existing one.
5. Commit to `main`, then wait a minute or two and refresh https://patrioticworrier07.github.io/bharat-intelligence/

## What works
- India and global headlines are requested from the public GDELT DOC API when the page loads, with refresh buttons and automatic refresh every 15 minutes.
- If browser access to the API is blocked or the service is unavailable, the panel shows an explanatory message rather than silently staying empty.
- Cyber advisories, disaster alerts, economy, and space panels link to official public sources.

## Limitations
- Static GitHub Pages cannot safely keep private API keys. This version does not require an API key for the headline feeds.
- The map markers are illustrative, not real incident locations.
- News articles are not automatically verified; check publisher, dates, and corroboration.
- This is an independent project, not an official government/intelligence service.
