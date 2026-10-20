# GlassPad Web sound (archive)

A frozen copy of GP Test 6.05 (20 Oct 2026) that always plays the old Web sound (Web Audio), kept in case it's needed after the app moves to the native engine everywhere.

- Play it: https://alexichristou.github.io/glasspad-web-sound/
- New work happens in AlexiChristou/glasspad (test.html). Don't develop here.
- Own storage: localStorage keys prefixed `gpws:`, IndexedDB `gpws-glasspad*`, service worker cache `glasspad-websound-*`, so it never touches GP Test's saved data on the same site.
- Matching source: glasspad repo tag `web-sound-final`.
