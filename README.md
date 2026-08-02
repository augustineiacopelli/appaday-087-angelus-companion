# AppADay 087 &middot; Angelus Companion

**A guided companion for praying the Angelus and the Regina Caeli, with the versicles and responses laid out to pray along and a gentle bell chime at the three traditional hours.**

Part of [AppADay](https://augustineiacopelli.github.io/appaday/), a project by Augustine Iacopelli in which one complete, mobile-friendly web app is designed and shipped every single day.

## What it does

The prayer sits at the center of the app in two forms. A guided mode walks through one section at a time, from the Annunciation through the Incarnation to the concluding collect, with the Hail Mary written out in full at each of the first three versicles and a rubric to bow the head at "And the Word was made Flesh." A full-text mode lays the whole prayer out to read straight down. Both open and close with the Sign of the Cross and end with the traditional invitation to offer the Angelus for the intentions of the Holy Father.

The app follows the liturgical year on its own. In Auto mode it computes the date of Easter and, from Easter Sunday through Pentecost, prays the Regina Caeli in place of the Angelus, with a short note explaining the change. You can also pin it to the Angelus or the Regina Caeli by hand.

Reminders ring the traditional Angelus bell at 6 AM, noon, and 6 PM, rendered in the browser as the customary three-three-three-nine toll, with a single-call option and a countdown to the next hour. Because browsers do not permit audio to play until you have interacted with the page, the chime asks you to tap once to enable sound, and it rings only while the page stays open. Any time the individual hours can be turned on or off, and every setting is remembered in your browser.

## How it is built

A single self-contained file of vanilla HTML, CSS, and JavaScript. No build step and no dependencies beyond Google Fonts. The bell is synthesized with the Web Audio API; the season logic uses the Computus algorithm for the date of Easter. Nothing leaves your device and no account is required.

## Run it

Open `index.html` in any modern browser, or visit the live version at `https://augustineiacopelli.github.io/appaday-087-angelus-companion/`.

---

*Ship something every day. It compounds.*
