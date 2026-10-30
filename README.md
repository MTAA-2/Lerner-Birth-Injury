# Birthing Injury Claim Landing Page — GitHub Pages (static) version

A static (HTML + CSS only, no PHP) birth injury landing page for **Lerner and Rowe Injury Attorneys**, built on the framework of your uploaded Goldwater page (`index-3.html` / `style-3.css`) and filled with content from **birthinginjuryclaim.com**. Per your instruction this time, all branding and firm-information areas were converted to the sample site's firm.

## Kept from your framework, unchanged

- Page structure, classes, the MTAA CIPA block script, and your new Meta Pixel (`1665132690448359`).
- Your new form embed: `forms.mtaa.ai/f/nf_961934ed45284c819e54264e8cbc1682`, in the overflow form card — the container hangs past the hero over the section below it, the frame scrolls internally with `overflow: auto` if the embed runs tall, and your mobile values (form `margin-bottom: 1px`, following section `padding-top: 5px`) are preserved exactly.
- The call/text consent paragraph in the footer disclaimer.
- Footer legal links still point to your `privacy-policy.html` and `disclaimer.html` on justicehelpnow.com (your hosted legal pages from the framework). Say the word if you want them pointed elsewhere for this page.

## Firm information — converted to the sample site (Lerner and Rowe)

- Title/meta and header: Lerner and Rowe Injury Attorneys (text logo, as in the framework — no logo file was supplied).
- **No phone number anywhere.** The sample site displays none (only a "Phone" field in its form), so the framework's Goldwater phone was stripped: header span and footer phone block removed, and the now-unused `.header-phone` CSS rule removed — the same treatment as the stroke page.
- Footer contact: Lerner and Rowe Injury Attorneys / Lerner and Row Mass Tort LLC, 2701 E Camelback Rd STE 140, Phoenix, AZ 85016.
- Disclaimer: the sample site's exact sponsorship line — "THIS IS ATTORNEY ADVERTISING sponsored by Lerner and Row Mass Tort LLC, located at 2701 E Camelback Rd STE 140 Phoenix, AZ 85016." Note the sample spells the sponsor "**Row**" (not Rowe) in this line, while the firm itself is presented as "Lerner and **Rowe** Injury Attorneys." Both spellings are preserved exactly as the sample has them.
- Results: the sample's firm claims — a dedicated award-winning team, more than 240 years of combined personal injury litigation experience, over $1 billion recovered for clients across the nation, no fee until compensation is won; "Awarded Best Attorneys in America" and "Repeatedly Voted Best Personal Injury Law Firm — voted best 10 years in a row."
- Team block (replaces the Goldwater story): "Our Team of Legal Professionals" — Glen Lerner, Founder, Personal Injury; Kevin Rowe, Founder, Personal Injury.
- Copyright: © 2026 Lerner and Rowe Injury Attorneys.
- All Goldwater traces were removed and verified at zero: name, (877) 759-2418, the Tatum Blvd. address, the familyjusticefirm.com awards image, the national-network copy, and the triplets story.
- One inconsistency on the sample itself: its top banner says "Over 100 Years of Combined Experience" while its team section says "more than 240 years." This page uses the team section's 240-years figure, which is the one tied to the Lerner and Rowe claims.

## Colors (the only other CSS changes)

`css/style.css` is your uploaded `style-3.css` with **color values only** changed (diff-verified — every layout, spacing, and overflow rule untouched, apart from the `.header-phone` removal noted above), matched to the live birthinginjuryclaim.com palette, sampled from the rendered site on 2026-10-30:

- Black `#000000` / charcoal `#1a1a1a`–`#333333` for the top bar, hero gradient, dark section, and footer (their darkened-photo hero and black footer band)
- Bright yellow `#fff200` for the CTA buttons (black text, like their "Get Help Now"), the hero eyebrow, and highlights on dark backgrounds
- A deepened yellow `#cc9900` for the small accent text on light backgrounds (kickers, headline accents, checkmarks) — the sampled `#fff200` is illegible as small text on white, and the sample itself uses black headings on its white sections
- Light gray `#efefef` for the results band; black/dark-gray body text

Colors were sampled visually from the rendered page, so they are close approximations rather than values read from that site's stylesheet, and its hero is a darkened photograph rather than a flat color.

## Content (from birthinginjuryclaim.com)

- Hero: "Did Your Child Suffer an Injury at or Near the Time of Birth?" with that site's hero copy — negligence of an obstetrician or other health care provider, thorough investigation, standard of care, compensation for a lifetime of medical care, no fee unless the case is successful.
- Why Seek Legal Counsel — proving the physician was responsible and the extent of damage/loss, plus that site's firm copy: extensive experience handling birth injury cases, the complexities of medical liability, holding the responsible party accountable while you focus on healing and caring for your loved one.
- Birth Injuries — cerebral palsy explained (decreased oxygen/blood flow), plus HIE, brain injury/brain damage, developmental delays, intellectual disability, mental problems, **autism** (new on this sample), and seizure disorders; lifetime-care list (residential care, in-home supervision, therapies, assistive devices, medications, specialists, home modifications, surgeries).
- How It Happens — the same nine preceding-event cards the sample lists: emergency cesarean section; prematurity/preterm labor/cervical insufficiency; NICU stay following birth; resuscitation at birth; seizures in the newborn period; fetal distress; uterine rupture; placental abruption; cooling therapy / therapeutic hypothermia.
- What We Look At — from that site's form: the condition (cerebral palsy / HIE / brain injury or damage / developmental delay / autism / other injury), NICU stay length (1–3, 4–7, 8–14, or 15+ days), year of birth (recent years back to before 2016), and the state where the birth happened.

## Files

```
github-birthing-injury-claim-landing-page/
├── index.html
├── css/style.css   (your framework CSS, colors only changed + .header-phone removed)
└── README.md
```

Publish the same way as the other GitHub pages: upload to a repo keeping the structure, Settings → Pages → deploy from branch (root).
