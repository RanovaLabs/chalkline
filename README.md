# Chalkline website

Static pages served by GitHub Pages, kept in their own public repository so the
app's source can stay private — GitHub Pages cannot publish from a private repo
on a free plan.

| Page | Purpose |
|---|---|
| `index.html` | Marketing homepage. Use this as the Marketing URL in App Store Connect and as the website on a Facebook page or ad account. |
| `privacy.html` | **Privacy Policy URL** for App Store Connect. Required, and App Review checks it resolves. Facebook also requires a privacy policy URL for business pages and lead ads. |
| `support.html` | **Support URL** for App Store Connect. Required. |

## Contact address

Support and privacy enquiries go to `ranovalabs@icloud.com`, the Ranova Labs
address shared by all its apps. The pages and the shared footer
(`assets/ranova-frame.css` styles it) link to it. If it ever changes, update
every page together — nothing in the app itself carries
the address, since Settings > Contact Support opens `support.html` rather than a
mail composer.

## If you register a domain later

Add a `CNAME` file containing the bare domain, point the DNS at GitHub Pages,
then update `LegalLinks` in the app so the in-app links match the live URLs.
