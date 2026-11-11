# Deployment

Static GitHub Pages placeholder. The only visible body text is `fiveamresearch.com`. No build step or external assets. Local browser verification passed through http://127.0.0.1:8766/fiveamresearch.com/.

Created public https://github.com/parrill/fiveamresearch.com and pushed main. Pages main / build passed with custom domain fiveamresearch.com. Origin content verified using curl --resolve fiveamresearch.com:80:185.199.108.153; public DNS remains on Squarespace parking. DNS access blocked at Squarespace login; browser vault has no saved login.

HTTPS: GitHub Pages obtains a free Let's Encrypt certificate automatically after domain/DNS validation. For stalled provisioning, remove and re-add the custom domain in Pages settings, then enable Enforce HTTPS when available.

Research DNS currently points to Squarespace. Planned DNS after Pages is configured: replace parking apex A records with 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; set www CNAME to parrill.github.io. Preserve unrelated mail/TXT records. DNS changes have not been applied; Squarespace login access is required.
