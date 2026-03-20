source.
A free, browser-based clothing sourcer that lets you search Depop, Grailed, Vinted, eBay, and Mercari Japan simultaneously with one click. Save search tags to track pieces you're hunting, get new listing counts daily, and optionally connect your free eBay API key to pull live results directly into the grid. No backend, no subscriptions — just open the file and go.
---
Features
One-click multi-platform search — hit Search and all five platforms open pre-filled in new tabs simultaneously
Saved search tags — save any search (e.g. "Helmut Lang SS99", "Arc'teryx Beta AR") and rerun it instantly
Daily new listing tracking — badge counts show how many new listings appeared since your last check
Favourites — heart any item to save it across sessions
Price filter — set a USD min/max to narrow results
Condition filter — filter by new, like new, good, or fair
Optional eBay live grid — add your free eBay Developer API key to pull eBay results natively into the app instead of opening a tab
No backend, no APIs required — works entirely in the browser, saved tags and favourites stored in localStorage
---
Platforms
Platform	Region	How it works
Depop	Global	Opens pre-filled search tab
Grailed	Global	Opens pre-filled search tab
Vinted	Global	Opens pre-filled search tab
eBay	US	Opens tab (or live grid with API key)
Mercari	Japan	Opens pre-filled search tab
---
Getting started
Option 1 — Use it locally
Download `index.html`
Open it in any browser
Done
Option 2 — Host on GitHub Pages (free)
Fork or clone this repo
Go to Settings → Pages
Set source to main branch / root
Your app will be live at `https://yourusername.github.io/your-repo-name`
---
Optional: eBay live results
To get eBay results appearing natively inside the grid instead of opening a tab:
Sign up free at developer.ebay.com
Create an app — takes about 2 minutes
Copy your App ID (Client ID) and Cert ID (Client Secret)
Paste them into the setup screen when you open the app
The eBay Developer API is free with 5,000 calls per day — more than enough for daily use.
---
Stack
Plain HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step.
