# Farm Puro Homepage Mockup

_Started 2026-05-25 09:40 UTC_

---

## User

Design a full homepage mockup for Farm Puro Chutneys — a premium D2C Indian chutney brand.  BRAND IDENTITY (from our brand brief): - Primary colour: Deep green #2D6A2D - Secondary colour: Warm brown #6B3A1F - Background: Cream #FAF7F2 - Accent: Gold #C8860A - Heading font: Playfair Display - Body font: Inter - Tone: Premium, authentic, warm, rooted in Indian tradition  SECTIONS TO DESIGN (in this order): 1. HEADER — sticky, logo left, nav centre (Home, Shop, About, Recipes, Contact), cart icon right 2. HERO — full viewport height, deep green background, large Playfair Display headline, subheadline, 2 CTA buttons (Shop Now in gold, Our Story in outline), subtle leaf pattern background 3. TRUST BAR — 4 icons in a row: Made Fresh | No Preservatives | Natural Ingredients | Authentic Taste 4. FEATURED PRODUCTS — grid of 4 product cards: image, name, short description, price in INR, Add to Cart button 5. BRAND STORY — 2 columns: left image, right heading + 2 paragraphs + CTA link 6. WHY FARM PURO — 3 cards on cream background with icons, headings, body text 7. TESTIMONIALS — 3 quote cards with star rating, name, city 8. NEWSLETTER CTA — brown background, email input, subscribe button 9. FOOTER — logo, 4 link columns, copyright bar  Design for desktop (1280px wide). Show realistic placeholder text, not lorem ipsum. Make it feel premium and authentically Indian.

## Assistant

_[tool: list_files]_

_[tool: copy_files]_

_[tool: copy_files]_

_[tool: write_file]_

_[tool: done]_

_[tool: fork_verifier_agent]_

Built **Homepage.html** — a desktop (1280px) mockup for Farm Puro Chutneys following your brand brief.

**Design notes**
- **Type system:** Playfair Display for headlines (with italics for emphasis like *"nani's kitchen"*), Inter for body, monospaced eyebrow labels in gold caps for rhythm.
- **Hero:** Full-viewport deep green with a subtle gold leaf-pattern SVG overlay, your Coriander Mint jar floating on a soft glow, a rotating cream "₹40 off" stamp, three trust stats below.
- **Featured products:** Real product photos (Coriander Mint, Tamarind Date, Coconut, Garlic Red) with region eyebrow, dashed-rule price/CTA split, star ratings, Bestseller/Limited/Hot tags.
- **Brand story:** Curry leaf jar image with a green "38 years of tradition" badge, drop-cap opening paragraph, signed by 3rd-gen founders.
- **Premium touches:** dotted-line dividers, ornamental section eyebrows, FSSAI license number in footer, UPI/RUPAY badges, copper-kadhai / paata / Sadashiv Peth language for authentic rooting.

If you want variations of the hero layout, product card style, or color emphasis — happy to add them as Tweaks or a design canvas.

## User

is there anything that you would change as per the additional material attached?

## Assistant

_[tool: read_file]_

_[tool: read_file]_

_[tool: copy_files]_

Yes — several meaningful gaps between what I built and the brand strategy/product catalog. Here's what I'd fix:

**Things I got wrong or invented**
1. **Body font** should be **DM Sans**, not Inter (brand strategy is explicit)
2. **"Since 1987" / "38 years of tradition" / founder names (Aarav & Meera Joshi) / "Sadashiv Peth flat"** — I invented all of this. The brief has no founding year or founder story. Removing.
3. **Product count** — there are **9 products**, not "12 regional recipes"
4. **Hero headline** should lead with the real tagline: *"From the farm. Fresh to your table. Always Pure."*
5. **Voice** — strategy bans words like "curated/artisanal" and prefers "stone-ground / sun-dried / made this week". I had a few of these to clean.

**Things I missed**
6. **Three brand pillars** (Purity you can taste · Regional soul · Made this week) should drive the trust bar + Why section
7. **Proof points** — "30-day shelf life", "batch date on every lid" — these are killer differentiators
8. **Real taglines & descriptions** for products (e.g. *"The loudest jar on the table — and the first empty"* for Garlic Red Thecha)
9. **Chilli Red #E8531A** for "Hot/Limited" tags instead of using green/gold for everything

Applying as **Homepage v2.html** now.

_[tool: str_replace_edit]_

_[tool: str_replace_edit]_

_[tool: str_replace_edit]_

_[tool: str_replace_edit]_

_[tool: grep]_

_[tool: str_replace_edit]_

_[tool: done]_

_[tool: fork_verifier_agent]_

**Homepage v2.html** is live with the brand-aligned changes:

| Change | What & why |
|---|---|
| **Font system** | Body now **DM Sans** (was Inter), per brand strategy |
| **Hero headline** | "From the farm. Fresh to your table. *Always pure.*" — the real tagline |
| **Hero eyebrow** | Replaced "Since 1987" with the actual proof points: *Made this week · 30-day shelf life · batch date on every lid* |
| **Hero stats** | 9 recipes · 30-day shelf · 0 preservatives (was 12 recipes / 4.9★ / 100% natural) |
| **Trust bar** | Subcopy rewritten around the three brand pillars |
| **Products** | 4 cards now use real catalog names, taglines and "Sweet/Light/Bold/Cooling" region labels; "View all 9 chutneys" |
| **Tag color** | Added Chilli Red #E8531A for Hot/Limited tags (per extended palette) |
| **Brand story** | Removed invented year, founder names, and "Sadashiv Peth flat". Headline is now the emotional benefit *"The taste of home, wherever home is"*. Stamp shows "9 Regional Recipes" |
| **Why section** | Rewritten to the three messaging pillars verbatim: *Purity you can taste · Recipes with a regional soul · Made this week, not months ago* |
| **Testimonial #2** | Replaced the "dosa cart owner" line (slightly off-strategy) with one that surfaces the batch-date proof point |

Kept your original gold #C8860A (your brief locked it; strategy doc has a slightly different "Turmeric Gold #C8982A" — happy to swap if you prefer that one).

The original **Homepage.html** is still in the project if you want to compare side-by-side.

