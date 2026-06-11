# The Palms at Crystal Beach RV Resort

Static website draft for `palmsatcrystalbeach.com`.

## Cloudflare Pages

Upload or connect this folder as the site root:

`outputs/palms-site`

The site includes:

- `index.html`
- `styles.css`
- `script.js`
- `robots.txt`
- `sitemap.xml`
- `_redirects`
- optimized web images in `assets/images`

## Banner Video

The original banner video is currently about 82 MiB:

`Paual_sVineyardWebLoop.mp4`

Cloudflare Pages has a 25 MiB maximum size for a single site asset, so the video should not be uploaded directly to Pages in its current form. The local draft uses the video for preview, but the deployable ZIP excludes it. For production, host the video at a future URL such as:

`https://static.palmsatcrystalbeach.com/palms-loop.mp4`

Best options:

- Compress the video below 25 MiB and place it at `assets/video/palms-loop.mp4`, then update the hero video source.
- Host the full video through Cloudflare R2, Cloudflare Stream, or another video CDN and update the hero video URL.

Until then, the hero uses the optimized aerial image as its poster/background.

## Items To Confirm

- Final beach house booking link
- Final email address for the rebranded resort
- Whether to keep the existing Rent Manager booking and tenant login URLs
- Any policy details for pets, parking, utilities, minimum stays, and holiday dates
