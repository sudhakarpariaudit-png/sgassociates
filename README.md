# SG Associates website

This repository contains the static website for Sudhakar & Gayathri Associates.

Files added:
- index.html
- about.html
- services.html
- contact.html
- style.css
- CNAME (www.sgassociates.com)

How to publish on GitHub Pages:
1. Go to this repository Settings → Pages and set the source to the `main` branch and root (/).
2. The Custom domain field should show `www.sgassociates.com` (or add it manually) — ensure DNS is configured as described below.

DNS settings (add these at your domain registrar):
- CNAME: Host `www` -> `sudhakarpariaudit-png.github.io`
- A (apex/root) records for `sgassociates.com` (optional but recommended):
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153

Google Search Console (Domain property) verification:
- In Search Console choose "Add property" → Domain and enter `sgassociates.com`.
- Google will show a TXT record like: `google-site-verification=...` — add that TXT to your DNS and then click Verify.

I cannot add DNS records or verify Google Search Console for you — please add the TXT record and let me know when done so I can help confirm.
