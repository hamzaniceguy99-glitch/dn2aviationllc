# DN2 Aviation — dn2aviation llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `dn2aviationllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/dn2aviationllc.mjs`).
> To change the content, edit that file and run `node build.mjs dn2aviationllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@dn2aviationllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
DN2 Aviation LLC is a Florida limited liability company providing aircraft management and aviation support services, formed in 2018. We work with aircraft owners on management, oversight and coordination, and the first thing we establish in writing is who holds operational control of any given flight. That question is not administrative. Offering air transportation to the public for compensation requires an air carrier certificate, and a management arrangement that quietly transfers operational control turns a private flight into an unauthorized commercial operation. The FAA treats illegal charter as an enforcement priority, and the owner carries much of the exposure, including the real possibility that an insurer declines a claim on a flight operated outside the rules it was underwritten for. We are not an air carrier and we do not hold out flights. Site: dn2aviationllc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
