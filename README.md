# ai-business

Demo websites for pitching local businesses.

## Demos

| Demo | Path | What it shows |
| --- | --- | --- |
| Fennick's Bakehouse (fictional) | `docs/bakery/index.html` | Live "open now" status, today's bake board, menu with prices, cake order form, opening hours, works on phones, light and dark mode |

Each demo is one self-contained HTML file with no build step and no images to host.

## Put it online for free (GitHub Pages)

1. On GitHub, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, pick `main`, set the folder to `/docs`, and save.
3. After a minute the demo is live at `https://<your-username>.github.io/ai-business/bakery/`.

GitHub Pages on a private repo needs a paid GitHub plan. Make the repo public, or use Cloudflare Pages (free) instead.

## Turn the demo into a real client's site

Everything business-specific is plain text in `index.html`:

- Name, address, phone and email: search for `Fennick`, `Mill Lane` and `01632`.
- Opening hours: the `HOURS` object in the script (minutes after midnight, `0` = Sunday).
- Bake board: the `BAKES` list. For a non-bakery, repurpose it as "today's specials" or "next available slot", or delete it.
- Colours and fonts: the tokens at the top of the `<style>` block.
- Remove the "Sample website" bar and footer note.
- The cake form only shows an on-page confirmation. For a live site, connect it to a form service such as Formspree, or swap it for a phone or email call to action.

## Suggested pitch pricing

- Site build: £150–£400 one-off
- Hosting, edits and hours updates: £15–£25 per month
