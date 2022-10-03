---
date: 2022-10-03
author: imax
---
# Twitter reporting helper

Browser extension to streamline reporting on Twitter.

Configure presets of the answers to Twitter report dialogs and allow reporting
tweets/users with just a few clicks.

Ideally it should work in both Chrome and Firefox.

## Implementation ideas

There's no public API for reporting things, so you'll have to sniff HTTP
requests in browser devtools. Then, inject a content script into twitter.com
page that would send the relevant requests.
