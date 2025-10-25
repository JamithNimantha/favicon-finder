# Favicon Finder - Quickly fetch and download favicons for any website using Google and DuckDuckGo icon APIs. 

https://jamith.com/favicon-finder/

Tiny web tool to fetch, copy and download favicons for any website using several public favicon services.

Features
- Enter any website URL (https optional) and pick a favicon size.
- Fetch favicons from multiple services at once:
  - Google (https://www.google.com/s2/favicons)
  - DuckDuckGo (https://icons.duckduckgo.com)
- Copy the direct icon URL or download the image using the provided buttons.

Quick local test

Open `index.html` directly in a browser or serve the directory with a simple static server.


Notes about included services
- Google: fast direct favicon endpoint using `?domain=` and `&sz=`.
- DuckDuckGo: provides `.ico` via `icons.duckduckgo.com/ip3/{domain}.ico`.
