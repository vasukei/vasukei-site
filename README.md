# VASUKEI — Website

A custom static website for vasukei.org.

## Files

- `index.html` — main website
- `style.css` — all styling
- `vasukei-emblem.png` — supplied Vasukei emblem
- `CNAME` — custom domain
- `README.md` — setup notes

## Before publishing

Search for `data-placeholder` in `index.html` and replace the `#` links with the real:
- Discord invite
- TikTok profile
- Payhip shop

The email currently uses `contact@vasukei.org`; change it if you want another address.

## GitHub Pages

1. Create a public GitHub repository.
2. Upload all files in this folder.
3. Go to Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the `main` branch and `/ (root)`.
6. Set the custom domain to `vasukei.org`.
7. In your domain's DNS settings, add GitHub's current A/AAAA records for the apex domain. GitHub's documentation lists the current records and recommends also configuring `www`.

The site is static HTML/CSS/JS, so no server or database is required.


## Current links

- Discord: https://discord.gg/FBYJvptn7
- TikTok: https://www.tiktok.com/@vasukei.org?lang=en
- Payhip: intentionally left pending

The V-agent visual archive is based on the image supplied in the conversation and is integrated into the page as a dark editorial visual rather than a standalone manga panel.
