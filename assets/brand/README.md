# EnJoin Labs / TenderInbox brand assets

Palette: teal #0E7C7B · amber #F2A93B (dark amber #D98E1E on light backgrounds) · ink #0F1A1A · white.
Type: Inter 700 for "EnJoin", Inter 600 tracked +5 for "LABS". Lockup SVGs reference Inter by name; the PNGs have it baked in.

## enjoinlabs/
| File | Use |
|---|---|
| enjoinlabs-icon.svg / -512 … -16.png | Rounded tile. Site, social avatars, Stripe branding icon |
| enjoinlabs-icon-square.svg / -512.png | Square tile for stores that apply their own corner mask |
| enjoinlabs-mark-teal.svg / -white.svg | Bare mark, no tile. Teal on light surfaces, white on teal/dark |
| enjoinlabs-lockup-light.svg / -2x.png | Mark + wordmark for light backgrounds (transparent) |
| enjoinlabs-lockup-dark.svg | Same for dark backgrounds (transparent) |
| enjoinlabs-lockup-dark-bg.svg / -2x.png | Dark lockup on ink background (social headers, email footer) |
| favicon.ico (16/32/48), apple-touch-icon.png (180) | enjoinlabs.dev `<head>` |

## tenderinbox/
| File | Use |
|---|---|
| tenderinbox-icon.svg / -512 … -16.png | Pipedrive Marketplace app icon (upload the 512 PNG), product pages |
| tenderinbox-icon-square.svg / -512.png | Square variant if Marketplace masks corners |
| favicon.ico, apple-touch-icon.png | /tenderinbox/ pages and app.enjoinlabs.dev |

## Site `<head>` snippet
```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/enjoinlabs-icon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
```
