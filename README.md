# GymWars Website

The one-page website for GymWars, live at https://gymwarsapp.com/.

This folder is the GitHub repository YusufEmirUlutas/gymwarsapp.com. GitHub Pages publishes whatever is on `main`, so a pushed change goes live within a minute or two. The domain is registered at Cloudflare. Its DNS points the bare domain at GitHub Pages (185.199.108-111.153) and `www` at yusufemirulutas.github.io, all **Proxied**: Cloudflare serves the HTTPS certificate (SSL/TLS mode "Full", "Always Use HTTPS" on), because GitHub's own certificate request stayed stuck at "authorization created" for 12 hours. ultasdev.com/gymwars/ forwards here.

The legal pages stay on ultasdev.com (`/gymwars/privacy-policy.html`, `/gymwars/terms-of-service.html`, `/gymwars/support.html`, `/gymwars/community-guidelines.html`), and the store buttons load the shared helper from `https://ultasdev.com/assets/applink.js`, so they still open the App Store or Google Play from inside Instagram or TikTok.

## What's in the folder

- `index.html`: the page itself (words, layout, and the small bit of code that moves the card wall and flips the character cards).
- `assets/img`: real GymWars pictures only. The 22 original character cards as the app draws them, the 8 rank badges, and app screens from the App Store screenshot captures.
- `assets/fonts`: Bebas Neue and Archivo, the same fonts the app uses, with their free licences.
- `og-image.jpg`: the picture people see when the link is shared in a message or post.
- `favicon.png` and `apple-touch-icon.png`: the bull icon for browser tabs and home screens.
- `CNAME` and `.nojekyll`: tell GitHub Pages the domain and to serve the files as they are.

## Rules the page follows

- No prices, no "free", no trial and no star ratings anywhere.
- No character count, because it changes with every new character.
- Only real app screens and real character art. Nothing AI-made.
- English only for now.
- Fonts are stored with the site, not loaded from Google.
