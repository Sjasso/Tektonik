# only 4 creative people

hazme un brochure de metal arquitectonico

This design system was generated mechanically from the onboarding brand form — no AI was involved. Every token in `styles.css` traces to a form input or a documented default, so it is a faithful starting point, not an interpretation. Edit `styles.css` to retune the look; keep this guide in step with what the CSS actually does.

## How to use this

- Link the one stylesheet from every page — `<link rel="stylesheet" href="styles.css">` (adjust the relative path) — and take every color, font, spacing, radius and shadow from its variables (`var(--color-*)`, `var(--font-*)`, `var(--space-*)`, `var(--radius-*)`, `var(--shadow-*)`). Never hard-code a hex, a font name or a px value the tokens already carry.
- Each color role carries a 100-900 tonal ramp (`--color-neutral-100` … `--color-accent-2-900`) generated in OKLCH on a shared perceptual lightness scale. On this dark ground use the dark steps (700-900) for tinted fills, hovers and subtle borders, 500 as a role base, and the light steps (100-300) for text on those tints.
- For elevation use `--shadow-sm/md/lg` (already tuned to the ground) rather than ad-hoc box-shadows.

## Color

Page ground `#1b1b1b` with text `#ede9e9`, surface `#292929`, and accents `#a88a8a` / `#b8a3a3`.

The form's brand colors, in the order given, and the role each was assigned (assignment is by documented rules — ground-suitability by luminance, accents by chroma, text by contrast):

- `#1b1b1b` — page background (--color-bg)

## Type

- Headings (--font-heading): Archivo (loaded from Google Fonts by styles.css)
- Body (--font-body): Inter (loaded from Google Fonts by styles.css)

## Assets

- Logo: `assets/logo.png` (preview card: `brand/logo.html`)
- Reference screenshot: `assets/reference/01-Cordillera Residencial.png` (preview card: `brand/reference-01.html`)
- Reference screenshot: `assets/reference/02-Fachada Jasso-OFC-Nov25-Entrega-2.jpg` (preview card: `brand/reference-02.html`)
- Reference screenshot: `assets/reference/03-Fachada_Jasso.jpg` (preview card: `brand/reference-03.html`)
- Reference screenshot: `assets/reference/04-Winston Data Center.png` (preview card: `brand/reference-04.html`)

The reference screenshots are stored for consultation — the generator does not analyze them (it uses no AI), so nothing in the tokens was derived from them. When designing with this system, open them for layout and mood cues.
