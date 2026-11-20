# DigiNexus — Developer Website

Official developer website for the **DigiNexus** Google Play account:
https://play.google.com/store/apps/developer?id=DigiNexus

Live at: https://digi-nexus.org/

## Pages

- `/` — Home (apps, about, policy links)
- `/privacy-policy/` — Privacy Policy
- `/terms-and-conditions/` — Terms & Conditions
- `/contact/` — Contact & Support
- `/data-deletion/` — Data deletion requests
- `/app-ads.txt` — IAB app-ads.txt for Google AdMob (pub-3258007165061164)

## Tech

Plain static HTML/CSS, served by nginx (Alpine) via the included `Dockerfile`.
No backend, no database, no environment variables, no secrets.

Deployed on Coolify (main instance) from this repository. Auto-deploy is OFF —
deploy manually from Coolify after pushing changes.

## Contact

kaleemullahabc700@gmail.com
