# Design System: Cafe Ellie
**Project ID:** (to be assigned after Stitch project creation)

## 1. Visual Theme & Atmosphere
Airy, editorial, and deeply intentional. Cafe Ellie embodies the Apple-school of design philosophy: restraint is luxury. Each screen breathes — abundant white space frames a single, powerful message. The aesthetic is modern specialty cafe meets art gallery. Nothing is ornamental; everything earns its place. The mood oscillates between serene confidence and warm emotional resonance, anchored by the unexpected energy of lime green.

## 2. Color Palette & Roles
- **Pure Canvas White (#FFFFFF)** — Primary background. The dominant surface on every page. Lets content float.
- **Off-White Linen (#F9F9F7)** — Secondary background for subtle section variation without contrast disruption.
- **Absolute Black (#0A0A0A)** — Primary text and headlines. Maximum contrast, editorial weight.
- **Mid-tone Ash (#6B6B6B)** — Body copy, captions, secondary labels. Softer presence, readable.
- **Electric Lime (#C8F135)** — The singular accent. Reserved exclusively for CTAs (buttons), interactive hover states, and single-word emphasis in headlines. Never used decoratively or in backgrounds.
- **Photographic Dark Overlay (#00000066)** — Semi-transparent layer over hero images when text reads over photography.

## 3. Typography Rules
- **Hero Headlines:** Ultra-large, 80–100pt+. Thin-to-regular weight (300–400). English and Korean mixed naturally. Letter-spacing slightly loosened (+0.02em). Line-height tight (0.95–1.1). The headline IS the design.
- **Sub-headlines / Labels:** Small, 12–14pt. Light weight (300). All-caps with generous letter-spacing (+0.15em) for English labels. Korean in regular weight.
- **Body Copy:** 16–18pt. Regular weight (400). Line-height comfortable (1.6). Used sparingly — white space does the talking.
- **Font character:** System sans-serif stack: `-apple-system, BlinkMacSystemFont, "SF Pro Display", "Pretendard", "Apple SD Gothic Neo", sans-serif`. Clean, neutral, globally legible.

## 4. Component Stylings
- **Primary CTA Buttons:** Pill-shaped (border-radius: 9999px). Background: Electric Lime (#C8F135). Text: Absolute Black (#0A0A0A). Padding: 14px 32px. On hover: slight scale transform (1.03) with box-shadow in lime. No border.
- **Ghost/Secondary Buttons:** Transparent background. 1px border in Absolute Black. Text: Absolute Black. On hover: border turns Electric Lime, text turns Electric Lime.
- **Navigation Bar:** Absolute positioned over hero, transparent. Logo left-aligned. Nav links right-aligned. Small uppercase tracking. On scroll: transitions to frosted white (backdrop-filter blur).
- **Cards (Menu Items):** Sharp, squared-off edges (border-radius: 0 or 4px). White background. No shadow — border separation or whitespace alone. Image top, text bottom. Minimal.
- **Forms (Reservation):** Flat, borderless inputs with only a bottom border line (1px, #0A0A0A). No boxes. Clean and open. On focus: bottom border turns Electric Lime.
- **Image containers:** Full-bleed, no borders, no rounded corners. Photography treated as primary design element.

## 5. Layout Principles
- **One message per viewport.** Each scroll section tells exactly one story.
- **Generous vertical rhythm.** Section padding minimum 120px top/bottom. Let screens breathe.
- **Text anchored to bottom-left or center.** Hero text often floats over full-screen images with ample room above.
- **Grid:** 12-column underlying grid. Content typically spans 8–10 columns, centered or offset-left.
- **Asymmetric tension:** Occasional large type offset to one side, image fills the other — creates visual dynamism without decoration.
- **Mobile-first responsive:** On smaller screens, hero text scales down proportionally but never below 48pt for headlines.

## 6. Design System Notes for Stitch Generation
Use this block verbatim in Stitch prompts:

> Apple-inspired minimal web design. Background: pure white (#FFFFFF). Text: near-black (#0A0A0A). Accent only: Electric Lime (#C8F135) on CTA buttons and key hover states. Full-screen hero photography with overlaid ultra-large bold typography (80–100pt, mixed Korean/English). Extreme whitespace — one message per screen section. Smooth scroll fade-in animations on text. Parallax on hero images. Navigation transparent over hero, frosted on scroll. Pill-shaped lime CTA buttons. Flat form inputs with lime focus underline. No decorative elements — typography and photography carry all visual weight. Modern Korean specialty cafe aesthetic.
