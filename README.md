# Chalkline website

Static pages served by GitHub Pages, kept in their own public repository so the
app's source can stay private — GitHub Pages cannot publish from a private repo
on a free plan.

| Page | Purpose |
|---|---|
| `index.html` | Marketing homepage. Use this as the Marketing URL in App Store Connect and as the website on a Facebook page or ad account. |
| `privacy.html` | **Privacy Policy URL** for App Store Connect. Required, and App Review checks it resolves. Facebook also requires a privacy policy URL for business pages and lead ads. |
| `support.html` | **Support URL** for App Store Connect. Required. |

## Before you publish

**Replace `support@chalklineapp.com`.** It appears on `privacy.html`,
`support.html`, and in the app's `LegalLinks`. It is a placeholder — that domain
is not registered. Either register it, or swap in an address you already
control. A support URL whose contact address bounces is a real problem for users
and a weak point at review.

## If you register a domain later

Add a `CNAME` file containing the bare domain, point the DNS at GitHub Pages,
then update `LegalLinks` in the app so the in-app links match the live URLs.
