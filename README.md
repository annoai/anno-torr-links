# Anno Torr — Links

Everything page for Anno Torr. Built with plain HTML + CSS. Deployed on Vercel via GitHub.

## Updating content

Edit `index.html` directly — offers, descriptions, and links are all in plain text.
Push to `main` and Vercel auto-deploys within ~30 seconds.

## Updating offer links

Search for `href="#"` in `index.html` and replace each `#` with the real URL.

## Adding Free Resources

Find the `FREE RESOURCES` comment block in `index.html`, uncomment it, and populate with your resources using the same `offer-row` structure.

## Deployment

1. Push this repo to GitHub
2. Import into Vercel → Framework: **Other**
3. Deploy — no build settings needed
4. Optionally connect `annotorr.com` in Vercel → Settings → Domains

## Brand tokens

Colours and fonts are defined as CSS custom properties at the top of `style.css` under `:root`.
