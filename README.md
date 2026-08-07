# Easyccounting website

## Status
- ✅ Domain bought (GoDaddy)
- ✅ Email fully working (pedro@easyccounting.com via Zoho — MX, SPF, DKIM all verified)
- ✅ GitHub repo created, files uploaded
- ✅ Site content updated (name, email, pricing +tax)
- ✅ GitHub Pages live at https://pedrosab.github.io/easyccounting-website/
- ✅ Custom domain (easyccounting.com) connected via DNS
- ✅ Calendly link added

## Reference: how this was set up
- **GitHub Pages:** Settings → Pages → Source: main branch, root folder
- **DNS (GoDaddy):** 4 A records (Name @) pointing to GitHub's IPs, 1 CNAME (Name www) pointing to pedrosab.github.io
- **Email (Zoho, free tier, web-only):** MX records (mx.zoho.com, mx2.zoho.com), SPF TXT record, DKIM CNAME — all added via Zoho's one-click GoDaddy connect

No build tools, no hosting bill.


