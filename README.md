# Lee Method Roadmap

A Bruce Lee–inspired training plan for three gym days a week, laid out over 15 years.

- **Roadmap:** five phases from Foundation to Longevity, with realistic targets for each
- **My week:** pick your 3 gym days and add optional 15-minute home sessions
- **Today's session:** a checklist with how-to explanations, time estimates and rest times
- **24 Hour Fitness:** the same workout matched to typical 24 Hour Fitness equipment, with backups
- **Progress:** log sessions and fitness tests, see streaks and charts
- **Rest timer:** a floating button in the corner of every tab. Tap to rest for 1:30 (the default), use −15 / +15 to adjust; it rings and buzzes when it's time to go again and remembers your last setting
- **Round timer:** timed rounds with a bell for bag work, rope and drills
- **Add to phone:** a button at the top installs the page as a home-screen app (PWA). On iPhone it shows the Safari steps; on a computer it shows a QR code to open it on your phone. Works offline once opened.
- **Languages:** switch between English, Simplified Chinese (简体) and Traditional Chinese (繁體) at the top of the page

It's a static site with no build step: `index.html`, plus `manifest.webmanifest`, `sw.js` (offline cache), `icons/` and `vendor/qrcode.js` (MIT, Kazuhiko Arase) for the app install. On a regular website, progress is saved in your browser's local storage, so it stays on that device and browser.

Not medical advice. Check with a doctor before starting if you have heart, joint or back problems.
