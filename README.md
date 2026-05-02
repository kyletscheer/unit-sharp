# Unit Sharp

A mobile-first web app I built to help people (and myself) get better at mental math unit conversions. Instead of just giving you the answer, it challenges you to estimate conversions for length, mass, temperature, and more.

You can use this as a PWA.

Find it at https://kylescheer.com/unit-sharp. You can find a link to the iOS app version there also.

## Why I built this
I wanted a tool that didn't just feel like a calculator, but a trainer. It uses a tiered scoring system to let you know if you're "Spot On," "Close," or just in the "Ballpark."

## Features
  • Mobile-First: Custom calculator UI that actually works on a phone screen.
  • Two Modes: Chill "Practice" or high-pressure "Timed" rounds.
  • Tons of Units: Everything from basic Length/Mass to more niche stuff like Data, Nautical, and Power.
  • Custom Units: You can add your own conversion pairs with specific multipliers and offsets.
  • PWA Ready: Works as a standalone app on iOS and Android.

# The Tech
  • Stack: Pure Vanilla JS, HTML5, and CSS3. No heavy frameworks.
  • State: Uses localStorage to keep track of your history and custom units.
  • Responsiveness: Heavy use of CSS variables to keep the UI scaling perfectly.

# Scoring Logic
The app grades estimates differently depending on what you're converting:
  • Exact (Data/Angles): Strict margins (1% / 5% / 15%).
  • Physical (Length/Mass): Standard margins (3% / 10% / 25%).
  • Contextual (Temp/Time): More relaxed margins (5% / 18% / 40%).

# Setup
  Just open index.html in a browser or host it on any static site provider. Since there’s no backend, it's ready to go immediately.

Created by Kyle Scheer