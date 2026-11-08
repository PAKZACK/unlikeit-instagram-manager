# UnLikeIt — Instagram Management Tool

**Status: Archived / not currently working.** This is a historical, experimental JavaScript project shared for portfolio and learning purposes. It is not maintained or endorsed by Instagram or Meta.

## Overview

UnLikeIt is a browser-injected JavaScript tool previously used through Chrome DevTools. It includes a custom dashboard for follower relationship analysis, a whitelist, and an interaction-cleaning interface. It uses DOM manipulation, asynchronous requests, client-side storage, and browser event handling.

## Features implemented in the source

- Custom full-screen **Relations** dashboard and floating launcher
- Following/follower comparison and non-follower/mutual views
- Local whitelist and selection controls
- Interaction-cleaning panel with configuration and progress display

## How it was used

The original script was run manually in the Google Chrome Developer Tools Console while signed in to Instagram. The file also includes userscript metadata, but it was developed and used as a console script.

**It is not recommended to run this archived version on a personal account.** It depends on undocumented Instagram APIs and page structure, and may no longer work. Automated account changes can carry account-restriction or data-loss risks. Never paste code into a logged-in website without reviewing it first.

## Known limitations

- Internal GraphQL query hashes and endpoints are hardcoded and potentially obsolete.
- Some operations treat HTTP failure responses as success.
- UI selectors depend on Instagram's changing interface.
- Automated tests are not included.
- This repository is provided for review of a past project, not as a supported Instagram automation tool.

## Technologies

JavaScript (ES6+), HTML/CSS (dynamic injection), DOM APIs, Fetch API, LocalStorage, Chrome DevTools.

## Attribution and license

Check third-party attribution before republishing or reusing any code. The original source includes a Ko-fi link to a third party; this archive preserves the supplied code without asserting ownership of that link. No open-source license has been selected; all rights remain with their respective owners.
