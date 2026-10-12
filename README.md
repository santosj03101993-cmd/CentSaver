# CentSaver prototype

CentSaver is a mobile-friendly bilingual (English/Tagalog) progressive web app prototype.

## What's working
- Home, Learn, Quizzes, Rewards, and Wallet views
- English/Tagalog language switch
- A demo quiz that adds 10 demo points for a correct answer
- Demo points persist in the same browser using localStorage
- Reset demo wallet
- Install prompt where supported
- Service worker cache for offline use after first successful visit on a supported HTTPS host

## Important limits
- The balance always shows ₱0.00. Demo points have no cash value.
- There is no ad network, sponsor, backend, account system, cash-out, or payment connection.
- Do not add ordinary ad-click rewards or click your own ads. Check every provider's policies before integrating ads or offerwalls.
- This is a front-end prototype, not a secure production rewards platform. localStorage can be edited by the user and must never be used as proof of real earnings.

## Run locally
1. Unzip the folder.
2. Open `index.html` in a modern browser to test the basic UI and quiz.
3. For install/offline testing, serve the folder over HTTPS or use localhost. Service workers and PWA installation usually do not work from a `file://` URL.

## Free hosting / PWA setup
1. Create a GitHub account if you don't already have one.
2. Create a public repository named `centsaver` and upload `index.html`, `manifest.json`, `sw.js`, and `icon.svg`.
3. In repository Settings → Pages, publish from the main branch and root folder.
4. Open the HTTPS Pages URL on Android Chrome. Use the browser menu → Add to Home screen / Install app if offered.
5. Test on your own device and ask a few trusted testers for usability feedback. Don't collect personal or payment details in this prototype.

Free hosting providers and their terms can change; check current terms before publishing.

## Legitimate monetization checklist
1. Build original useful content and make the app reliable and accessible.
2. Add a privacy policy, contact information, terms, and clear disclosures before collecting user data or showing ads.
3. An eligible adult should review the current Google AdMob eligibility, app readiness, consent, and policy requirements before applying. Approval is not guaranteed.
4. Never click your own ads, ask others to click them, disguise ads as buttons, or promise rewards for ordinary ad clicks. Rewarded-ad formats and offer providers have specific rules; use only arrangements explicitly allowed by the provider.
5. Test with provider test ads during development; never use live ads for testing.
6. For real rewards, use a trusted offer/reward provider that explicitly supports your app type and country, has clear payout terms, and permits your reward model.
7. Confirm payout method, identity/tax requirements, minimum threshold, fees, and timing before promising GCash. Never ask users for their GCash MPIN or OTP.
8. If the developer is under 18, involve a parent/guardian. Google Play developer accounts require an adult; AdMob has adult account-holder requirements. The adult must genuinely own/manage the relevant account and comply with the provider's terms.

## Before launch
- Replace demo UI with a server-backed account and ledger if real rewards are introduced.
- Add abuse prevention, secure authentication, privacy controls, support, and accounting.
- Never represent demo points as cash or advertise guaranteed earnings.
