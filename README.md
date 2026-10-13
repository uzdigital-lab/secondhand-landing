# SecondHand.uz — landing page

Mobile-first landing page for the SecondHand.uz Telegram channel. The main conversion is subscribing to the channel; the seller CTA opens the admin chat.

## Files
- `index.html` — responsive landing page
- `assets/secondhand-logo.png` — channel logo
- `assets/wardrobe-hero.webp` — lifestyle hero image
- `.nojekyll` — prevents Jekyll processing on GitHub Pages

## Links and tracking
- Telegram channel: https://t.me/+jUmExvhWjYY0Yjli
- Seller contact: https://t.me/Ladie_admin
- Meta Pixel ID: `1407486681003672`
- Events: `PageView` and custom `TelegramClick` with `placement`, `intent`, and `channel` parameters

## Publish on GitHub Pages
1. Upload the *contents* of this folder to the root of the `secondhand-landing` repository. Keep the `assets` folder intact.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**, branch `main`, folder `/(root)`, then save.
4. Wait for the Pages build to finish and open the generated URL.
5. Test `PageView` and `TelegramClick` in Meta Events Manager / Meta Pixel Helper.

## Before running ads
The three testimonial cards are illustrative draft copy, not verified customer quotes. Replace them with real subscriber feedback before publishing paid traffic.
