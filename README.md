# Mahkus

Personal link-in-bio page.

Live at: https://mahkusg.github.io/

## Analytics (Cloudflare Web Analytics)

1. Create a free Cloudflare account: https://dash.cloudflare.com/sign-up
2. Go to **Analytics & logs → Web Analytics → Add a site**
3. Hostname: `mahkusg.github.io` (manual/JavaScript setup)
4. Copy the site token into `analytics-token.js`:

```js
window.CF_WEB_ANALYTICS_TOKEN = "your-token-here";
```

5. Push to GitHub. Dashboard shows:
   - Home page visits
   - Per-button clicks as top pages under `/r/youtube/`, `/r/amazon/`, etc.
