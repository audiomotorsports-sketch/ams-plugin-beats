# Cursor / Grok Bot — LA Car Beats guinea pig

Copy everything below the line. **lacarbeats.com only.** Screenshot phone before production.

---

You are editing **lacarbeats.com** only. One pass. Do not open other network repos. Do not touch audiomotorsport.com (no S). Do not invent images. Do not rewrite the homepage.

## Job
Insert a quote plugin **immediately under the existing banner**. Offers, FAQs, SEO copy, and chat stay.

## Files
1. Save `ams-plugin-beats.css` as `/assets/css/ams-plugin-beats.css`
2. In the homepage `<head>`, after the other stylesheets, add:
   `<link rel="stylesheet" href="/assets/css/ams-plugin-beats.css">`
3. Save `ams-plugin-beats.html` and paste it as specified below.

## HTML insert
Find this exact close on the homepage:

```
</section>
<section class="offer-cards" id="offers">
```

The `</section>` belongs to `<section class="hero-banner">`.

Paste the full contents of `ams-plugin-beats.html` **between** those two tags:

```
</section>          ← hero-banner ends. Do not edit this section.
   *** PASTE PLUGIN HERE ***
<section class="offer-cards" id="offers">
```

## Do not
- Touch `<section class="hero-banner">` or its images
- Touch `.topbar`, `.site-header`, footer
- Touch `ams-chat.js` or `#ams-chat` (chatbot stays)
- Delete `#offers` / the ticket stack
- Change `:root` colors (this desk is red `--accent: #C41E3A`, not hub gold)
- Download or generate photos — use plates already on this site:
  - `/assets/offers/cstyle/plates/plate-pioneer-w3000nex.png`
  - `/assets/offers/cstyle/plates/plate-kicker-dual-cvs.png`
  - `/assets/offers/cstyle/plates/plate-thinkware-q200.png`
  - `/assets/offers/cstyle/plates/plate-kenwood-dmx4710s.png`
- Restyle the chatbot
- Send door links off lacarbeats.com

## Sticky bar
The plugin includes `.ams-plug-sticky` (Text | Call) with `right: 88px` so `#ams-chat` keeps the bottom-right corner.

Plugin CSS hides `.mobile-cta-bar` **only while** `#ams-plug-beats` is on the page (`body:has(#ams-plug-beats)`). Do not delete `.mobile-cta-bar` HTML.

## Phone / email
- Call: `tel:+13105138800` — (310) 513-8800
- Text: `sms:+12134291092` — (213) 429-1092
- Email link only: audiomotorsports@gmail.com

## Door URLs (on this site)
- Pioneer W3000NEX → `/services/head-units-carplay/`
- Kicker Dual 12 → `/services/bass-amps-subwoofers/`
- Thinkware Q200 → `/shop/` (Beats has no dash-cam URL; do not send to lacaralarm in this pass)
- Kenwood DMX4710S → `/shop/car-stereos/`

No prices in the plugin.

## Done when
- Banner is identical
- Proof + “Text the year, make, and model. We quote the job.” sit directly under the banner
- Four plate cards, no AI photos
- Offer tickets still exist below the plugin
- Phone screenshot: Text | Call sticky on the left, chatbot clear on the bottom-right
- “Text us a quote” opens SMS to +1 213-429-1092 with year/make/model if filled
- Call is (310) 513-8800
- Header Call at the top is unchanged

Screenshot **phone** before production merge to branch `v1`.
