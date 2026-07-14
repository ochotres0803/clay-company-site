# CLAY TCG Website

Static corporate website and Instagram landing page for CLAY Co., Ltd., a Japanese trading card export business.

## Files

- `index.html` - Main website
- `assets/proof/` - Operational proof photos for inventory, packing, and shipment preparation
- `assets/video/packing-highlight.mp4` - Lightweight packing process video used on the site
- `assets/team/` - Team member photos for the staff introduction section
- `privacy.html`, `terms.html`, `commercial-transaction.html`, `shipping-customs.html`, `disclaimer.html` - Legal and trust pages
- `robots.txt`, `sitemap.xml`, `404.html` - Search and site support files

## Updating the Discord link

The Discord invite URL is managed in one place inside `index.html`:

```js
const DISCORD_URL = "https://discord.gg/UNxmMVdYY";
```

Change this value if the invite link changes.

## Future content to add

- More packing photos
- FedEx / DHL label preparation photos with private details hidden
- Inventory shelf photos
- Short vertical packing or dispatch videos
- Confirmed payment, cancellation, and return policy details
