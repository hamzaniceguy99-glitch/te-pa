# TE-PA — building, demolition & masonry

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `te-pa.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/te-pa.mjs`).
> To change the content, edit that file and run `node build.mjs te-pa` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@te-pa.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are TE-PA, a construction business in Tielt-Winge in Flemish Brabant, trading since February 2018. We build and renovate homes, demolish and strip out, carry out masonry and structural work, and do sanitary work. One fact decides more of a demolition budget than the machines do, and clients almost never hear it until the invoices arrive. In Flanders, rubble from a demolition that has been traced through a recognised follow-up scheme, with the certificate that goes with it, is accepted by a crusher as low environmental risk material and can become certified recycled aggregate. The identical rubble, from the identical building, with no traceability behind it, counts as high risk: it is handled separately, it costs considerably more, and it can be refused outright. The follow-up plan that makes the difference has to exist before the permit application, not after the first wall comes down. Above the volume thresholds it is compulsory anyway, and below them it still usually pays for itself. We settle that, and the asbestos inventory, before quoting a demolition. Site: te-pa.shop
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
