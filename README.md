# Saudia Hajj & Umrah — Hajj Conference & Exhibition 2026

Landing page for Saudia Hajj & Umrah as Strategic Sponsor of the 6th Hajj Conference & Exhibition
(Jeddah Superdome, 8–11 Nov 2026, Pavilion C62).

Static site: one `index.html` plus `assets/`. No build step, no dependencies.

## Run locally

```bash
python -m http.server 8793
```

Open http://127.0.0.1:8793. Serve it over HTTP; opening the file directly can block the fonts, images and video in some browsers.

## Where things are

| What | Where |
| --- | --- |
| Page, styles, scripts | `index.html` (CSS in `<style>`, JS at the bottom) |
| Hero background clips | `assets/video/{arafat,makkah,mina}.mp4`, list in the `hc` array in the script |
| Main film + playlist | `assets/video/recap.mp4` and the `.pl` buttons in `#story` |
| Gallery photos | `assets/img/g-*.jpg`, `data-c` sets the filter, `data-t` the caption |
| Logos, QR, keyline tiles | `assets/brand/` |
| Saudia Sans | `assets/fonts/` |
| Social links | `#social` section |

## Open items

- Social URLs are built from the handle `SaudiaHajjUmrah` and are unverified. Instagram, Facebook, TikTok and LinkedIn URLs are missing (covered by the Linktree button).
- Replace `recap.mp4` with the original-quality film (current file is a compressed 1024×576 WhatsApp export).
- Logos are booth-kit PNGs, not master artwork.
- Client sign-off still needed on the Operations HQ line, the "80+ years" claim and the Ministry accreditation wording.

## Licensing

Saudia Sans, the logos and the footage belong to Saudia / the client. Keep this repository private.
