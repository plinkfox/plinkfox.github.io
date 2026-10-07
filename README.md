# plinkfox.com

The Plinkfox studio website: home, privacy policy, terms, support. It's plain HTML and CSS, with no
scripts, cookies or trackers. Hosted on GitHub Pages with the custom domain in `CNAME`.

| Path | Used by |
|---|---|
| `/privacy/` | Store listings, AdMob, the games' Settings → Privacy Policy (`privacy_url` tuning key) |
| `/terms/` | The games' Settings → Terms, the VIP screen (`terms_url`) |
| `/support/` | Store listings (support URL); the games' support email is `support@plinkfox.com` |
| `/app-ads.txt` | AdMob. **Add it once the AdMob account exists**: one line, `google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0` |

## Updating

Edit the files, commit and push. GitHub Pages redeploys in about a minute. When the privacy policy
changes, update its "Effective" date.

## DNS (Namecheap → Advanced DNS)

- **A records** for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- **CNAME** for `www`: `<github-user>.github.io`
- **Email:** forward `support@plinkfox.com` to `plinkfoxstudio@gmail.com` (Mail Settings → Email
  Forwarding).
