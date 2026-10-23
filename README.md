# Quite Cordial letters (back-issue archive)

A single static page (`index.html`) that holds every sent Quite Cordial letter.
Hosted on IONOS Deploy Now; every push to `main` redeploys it.

- **Not for search engines:** `noindex` meta tag + `robots.txt` (Disallow all).
- **No build step.** Plain HTML. Images live in `letters/`, referenced by relative path.
- **Updated by:** the scheduled task "Quite Cordial letter archive" (Tuesdays, or on request). It reads sent letters from the inbox and adds one entry to `LETTERS` and one `<template>` per letter. Instructions are in the comment at the top of `index.html`.
- **Signup link:** https://quitecordial.com/#waitlist
- Letter 1 is added only after it has actually been sent.
