KANJI QUIZ N2 - HTML/PWA

READY-TO-OPEN:
Open index.html directly in a browser. The quiz, 3,320 vocabulary items,
35-Day structure, flashcards, search, timer, and local progress work offline.

PWA:
For full Add to Home Screen + offline service-worker behavior, host this folder
on HTTPS (GitHub Pages, Netlify, Cloudflare Pages, etc.). Then open the URL on
iPhone Safari or Android Chrome and choose Add to Home Screen.

DATA:
Day 1-33 = 100 each
Day 34 = 20
Day 35 = reserved
Total = 3,320 source vocabulary / 3,500 slots.

IMPORT:
The standalone version accepts CSV. Export future Excel data as CSV with columns:
Kanji, Reading, Meaning
Then use Database -> Import CSV.

NOTE:
A browser cannot reliably execute arbitrary local XLSX/PDF imports without
additional libraries. The PWA therefore keeps the runtime lightweight and
uses CSV for user additions. The full source project can later add XLSX/PDF
parsing when served as a web app.
