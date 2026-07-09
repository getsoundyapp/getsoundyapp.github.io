# Soundy (getsoundy.app)

Official marketing site for **Soundy: Equalizer for SoundCloud**, a free, no-ads,
privacy-focused SoundCloud cloud music player for iPhone, iPad, Mac and CarPlay,
with a 10-band equalizer, playback speed control and full CarPlay support.

- App Store: <https://apps.apple.com/us/app/soundy-cloud-music-player-eq/id6778474045>
- Support: <support@getsoundy.app>

## Structure

```
.
├── index.html         # Landing page
├── support.html       # 30 FAQ + contact
├── privacy.html       # Privacy policy
├── terms.html         # Terms of service
├── 404.html           # Custom 404
├── how-to/            # How-to guides hub + articles (equalizer, speed, mixed mode, CarPlay)
├── css/styles.css     # All styles
├── js/main.js         # FAQ accordion + mobile nav
├── assets/            # Images (icon, OG)
├── robots.txt
├── sitemap.xml
├── llms.txt           # LLM/GEO discovery file
├── manifest.json
└── CNAME              # getsoundy.app
```

## Local preview

Any static server will do, for example:

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080/>.

## Deploy

Pushed to GitHub Pages on the default branch. The `CNAME` file maps the
custom domain `getsoundy.app`.
