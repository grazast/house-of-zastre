# House of Zastre — Website

## Brand System
- **Colors**: Primary `#404040`, Secondary `#6b6b6b`, Accent/Gold `#dbc278`, Background `#f8f7f4`
- **Typography**: IBM Plex Sans (300, 400, 500, 600)
- **Motifs**: Diagonal harvest lines, grain elevator imagery, prairie-meets-west-coast identity

## Structure
- `index.html` — Public lander (loader → hero with video + title → about section → inquiry form)
- `admin.html` — Password-protected admin (inquiries viewer, projects hub)
- `logo.png` — Z/z monogram mark

## Deployment
- **Host**: Cloudflare Pages (connected to this GitHub repo, auto-deploys on push to main)
- **Domain**: houseofzastre.com

## TODO
- [ ] Replace video placeholder in hero with Sora-generated .mp4
- [ ] Animate the logo loader (draw-on SVG animation matching the Z mark)
- [ ] Replace localStorage with Cloudflare Workers + D1 for inquiry/project persistence
- [ ] Replace plaintext admin password with Cloudflare Access or Workers auth
- [ ] Add the animated SVG footer (Vancouver skyline + wheat field)
- [ ] Add file upload capability to Projects page
