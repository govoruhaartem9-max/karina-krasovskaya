# KRASOVSKAYA PMU BROWS — Design system

## Direction
Quiet, elegant beauty studio identity. Keep the layouts editorial and spacious, with warm ivory surfaces, deep espresso sections and restrained bronze accents. Photography is the primary proof of the work and the studio.

## Color tokens
- Ink: #201b16
- Dark surface: #17130f
- Muted text: #776b5d
- Bronze: #aa8054
- Light bronze: #d4b387
- Cream: #f6f2ec
- Paper: #fffdfa
- Divider: #e8dfd3

## Typography
- Display and section headings: Playfair Display, regular weight.
- Navigation, labels, body text and controls: DM Sans.
- Use generous heading line-height and letter spacing only for small uppercase labels and navigation.

## Layout
- Centered content wrapper, maximum width 1160px.
- Main sections use generous vertical spacing and fine warm dividers.
- Use CSS grid with minmax(0, 1fr) for card and photo columns so long labels cannot force horizontal overflow.
- Keep the two studio photos together beneath “Власний кабінет”; retain portrait orientation and crop with object-fit: cover.
- Services and prices reduce from three columns to two and then one as the viewport narrows.

## Interaction and accessibility
- Keyboard focus is visible with a bronze outline.
- Respect prefers-reduced-motion.
- Use clear labels and descriptive alt text for photos.
- On mobile, form controls use 16px text to avoid automatic zoom and fixed controls respect safe-area insets.
