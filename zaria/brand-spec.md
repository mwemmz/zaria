# Zarira Engineering Solutions — Brand spec

Extracted from `mqjfnhjv-image.png` (logo).

## Tokens (CSS custom properties)

```css
--bg:      #888888;
--surface: #ffffff;
--fg:      oklch(12% 0 0);
--muted:   oklch(44% 0 0);
--border:  oklch(72% 0 0);

--copper:       oklch(50% 0.10 35);  /* primary workhorse */
--copper-bright: oklch(58% 0.11 38);
--gold:         oklch(80% 0.16 72);  /* sparing accent */
--gold-bright:  oklch(88% 0.14 72);
```

## Font stack

- **Display/headings:** `'Rajdhani', 'Barlow Condensed', -apple-system, BlinkMacSystemFont, system-ui, sans-serif`
- **Body:** `'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif`

## Layout posture

- Medium grey canvas (`#888888`) with white elevated sections for a clean industrial feel.
- Light-mid hero gradient (lighter than the page background) with near-black text for readability.
- Copper borders on cards and buttons; gold used sparingly for highlights, hover states, and accent elements.
- Subtle card shadows (`box-shadow: 0 2px 8px`) reinforce elevation on the grey background.
- Tabular numerics with `font-variant-numeric: tabular-nums` for stats and data.
- Tight letter-spacing on uppercase labels (`0.08em`).
- Responsive breakpoints: 1080px, 860px, 620px, 560px.
