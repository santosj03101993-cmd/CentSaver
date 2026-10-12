# CentSaver Publication Checklist

## Prepared
- [x] Mobile-friendly bilingual web prototype
- [x] Learning guides and quiz
- [x] Demo points clearly labeled as not real money
- [x] No fake ad revenue or payment integration
- [x] PWA manifest, icon, and service worker
- [x] Draft privacy policy and terms

## Still needed
- [ ] Publish to a free HTTPS host
- [ ] Replace privacy/contact placeholders and host the policy at a stable public URL
- [ ] Test on multiple Android screen sizes and browsers
- [ ] Check accessibility, links, offline behavior, and usability
- [ ] Decide whether to keep it as a free installable web app or prepare a native Android package
- [ ] If using Google Play, an eligible adult account holder completes registration
- [ ] Complete store listing, screenshots, content rating, and data-safety declarations
- [ ] Complete required testing and receive approval before calling it published

## Google Play notes
The account holder must be at least 18. Google Play Console registration has a US$25 one-time fee. New personal developer accounts created after 13 November 2023 generally need a closed test with at least 12 testers opted in continuously for 14 days before applying for production access. Rules can change; check official guidance:
- Registration: https://support.google.com/googleplay/android-developer/answer/6112435
- Testing requirements: https://support.google.com/googleplay/android-developer/answer/14151465
- User data and privacy policy: https://support.google.com/googleplay/android-developer/answer/10144311

## Before real monetization
- Review the advertising provider's current policies and app-readiness rules.
- Never click your own ads or ask others to click ads.
- Use test ads during development.
- Do not promise money for ordinary ad clicks.
- Confirm a rewards provider explicitly permits the reward model and target country.
- Confirm payout thresholds, fees, identity requirements, and supported Philippine payment methods before promising GCash.
- Build a secure server-side ledger and fraud prevention before handling real rewards. Browser local storage is not proof of real balances.
- Update privacy disclosures and data-safety answers for every SDK or service that collects or shares data.
