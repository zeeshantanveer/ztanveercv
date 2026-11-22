---
name: Zeeshan Tanveer Portfolio
description: A developer portfolio built to the product-site standard; the product is the shipped systems.
colors:
  canvas-white: "#ffffff"
  cool-grey: "#f6f8fb"
  ink-navy: "#0b1b33"
  ink-navy-hover: "#1a2d4f"
  body-slate: "#42526b"
  muted-slate: "#5b687d"
  hairline: "#e3e8ef"
  hairline-strong: "#d3dae4"
  accent-violet: "#5a48f5"
  accent-violet-ink: "#3f2fd6"
  field-peach: "#ffb37a"
  field-coral: "#ff5c87"
  field-violet: "#8f6bff"
  field-teal: "#40cce0"
  data-violet: "#7c5cff"
  data-teal: "#12b5c9"
  bar-before: "#b7c1d0"
  bar-track: "#e6eaf1"
  shopify-green: "#2e9e4f"
  woo-purple: "#7f54b3"
  magento-orange: "#e2552d"
typography:
  display:
    fontFamily: "Geist, system-ui, sans-serif"
    fontSize: "clamp(38px, 4.6vw, 62px)"
    fontWeight: 650
    lineHeight: 1.08
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Geist, system-ui, sans-serif"
    fontSize: "clamp(32px, 3.6vw, 48px)"
    fontWeight: 650
    lineHeight: 1.08
    letterSpacing: "-0.03em"
  title:
    fontFamily: "Geist, system-ui, sans-serif"
    fontSize: "23px"
    fontWeight: 650
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  lede:
    fontFamily: "Geist, system-ui, sans-serif"
    fontSize: "19px"
    fontWeight: 500
    lineHeight: 1.55
  body:
    fontFamily: "Geist, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Geist, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 500
    lineHeight: 1.35
  figure:
    fontFamily: "Geist Mono, ui-monospace, monospace"
    fontSize: "22px"
    fontWeight: 500
    letterSpacing: "-0.02em"
    fontFeature: "tnum"
rounded:
  sm: "8px"
  md: "10px"
  bubble: "14px"
  inset: "16px"
  panel: "18px"
  tile: "20px"
  feature: "22px"
  pill: "999px"
spacing:
  gutter: "28px"
  gutter-phone: "16px"
  grid-gap: "20px"
  tile-pad: "30px"
  tile-pad-phone: "22px"
  feature-pad: "44px"
  section: "96px"
  section-phone: "68px"
components:
  button-primary:
    backgroundColor: "{colors.ink-navy}"
    textColor: "{colors.canvas-white}"
    rounded: "{rounded.pill}"
    padding: "11px 18px"
  button-primary-hover:
    backgroundColor: "{colors.ink-navy-hover}"
  button-ghost:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.ink-navy}"
    rounded: "{rounded.pill}"
    padding: "11px 18px"
  button-ghost-hover:
    backgroundColor: "{colors.cool-grey}"
  button-small:
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  chip:
    backgroundColor: "{colors.cool-grey}"
    textColor: "{colors.body-slate}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "3px 10px"
  nav-link:
    textColor: "{colors.body-slate}"
    rounded: "{rounded.sm}"
    padding: "8px 12px"
  nav-link-hover:
    backgroundColor: "{colors.cool-grey}"
    textColor: "{colors.ink-navy}"
  tile:
    backgroundColor: "{colors.canvas-white}"
    rounded: "{rounded.tile}"
    padding: "{spacing.tile-pad}"
  feature-card:
    backgroundColor: "{colors.canvas-white}"
    rounded: "{rounded.feature}"
    padding: "{spacing.feature-pad}"
  contact-card:
    backgroundColor: "{colors.canvas-white}"
    rounded: "{rounded.feature}"
    padding: "48px"
  diagram-panel:
    backgroundColor: "{colors.canvas-white}"
    rounded: "{rounded.panel}"
  perf-inset:
    backgroundColor: "{colors.cool-grey}"
    rounded: "{rounded.inset}"
    padding: "24px"
---

# Design System: Zeeshan Tanveer Portfolio

## Overview

**Creative North Star: "The Product Page for Shipped Systems"**

This is the category standard executed at product-site craft. The page reads like a Stripe, Linear or Vercel product page, except the product is the work: live platforms, carrier integrations, storefront apps and chatbots. Conventions are taken straight (hero, featured case study, project grid, experience, stack, contact) and the quality is carried by execution: white and cool-grey grounds, deep navy ink, crisp hairlines, soft neutral shadows, one live gradient field and diagrams drawn in code.

The world has exactly one loud material: a skewed WebGL gradient band in peach, coral, violet and teal. It sits behind the hero and behind the closing contact card and nowhere else. Everything between those two bands is quiet: white cards on a cool-grey section, navy headings, slate body copy, violet used sparingly for links, checks and focus. Imagery is code-led: inline SVG system diagrams and small illustrative UI sketches, each labelled as illustration, never raster screenshots or generated pictures.

Geist and Geist Mono are a deliberate choice, tied directly to the Vercel quality bar the user picked. The detector flags Geist as an overused font; that warning was weighed and accepted here because the reference category is the point, and the face is used with tight tracking, balanced wrapping and a strict mono rule rather than as a default. The dark neon developer look and the plain template resume are both rejected.

**Key Characteristics:**
- Light, airy grounds: white sections alternating with cool-grey sections bounded by hairlines.
- One gradient material, on a skewed band, at the top and the bottom of the page only.
- Geist for everything at weight 650 with -0.03em tracking on headings; Geist Mono only for figures, dates and prices.
- Soft, cool, neutral shadows under white cards; 1px hairline borders everywhere else.
- Live diagrams and illustrative UI in place of screenshots, always labelled.
- Motion that confirms rather than performs: content visible by default, gentle nudges, pointer tilt on fine pointers only.

## Colors

A cool, near-monochrome navy and slate system on white, lit by one warm-to-cool gradient field and a single violet accent.

### Primary
- **Ink Navy** (ink-navy): all headings, primary button fill, user chat bubbles, brand mark tile, strong labels inside cards and diagrams. Hover on the primary button lifts to **Ink Navy Hover** (ink-navy-hover).
- **Signal Violet** (accent-violet): focus ring (3px outline), check icons in the case study, experience list markers. Its ink-dark sibling **Deep Signal Violet** (accent-violet-ink) carries text: text links, the performance figures, contact link hover.

### Secondary
- **Gradient Field** (field-peach, field-coral, field-violet, field-teal): the four stops of the WebGL shader and its static CSS fallback (`linear-gradient(115deg, #ffb37a, #ff6f91 35%, #8f6bff 65%, #3fd0e0)`). Used only inside the skewed bands.
- **Data Gradient** (data-violet to data-teal): the "after" performance bars and their legend key, a 90deg left-to-right gradient. Teal also colours one lane of moving packets in the order-flow diagram.

### Tertiary
- **Platform dots** (shopify-green, woo-purple, magento-orange): small identifying dots and packets for Shopify, WooCommerce and Magento in the diagrams; Shopify green also draws the storefront app-block outline and selected rate radio; Woo purple fills the "on" toggle in the WordPress sketch; Magento orange is the packet riding the Magento sync wire. These are identity marks, never fills for large areas.

### Neutral
- **Canvas White** (canvas-white): page ground, cards, tiles, diagram nodes, nav background (solid, never translucent).
- **Cool Grey** (cool-grey): alternate section ground (Work, Stack), illustration tints inside tiles, chip fill, performance inset, nav link hover.
- **Body Slate** (body-slate): running text and secondary diagram labels.
- **Muted Slate** (muted-slate): captions, dates, legends, stat descriptions, footer.
- **Hairline** (hairline): every 1px border, row divider and section edge. **Strong Hairline** (hairline-strong) for ghost button borders, diagram wires and hover borders.
- **Bar Track and Before** (bar-track, bar-before): the grey rail and the "before" fill of the performance bars.

### Named Rules
**The One Field Rule.** The gradient is a material, not a decoration. It appears only on the skewed band behind the hero and behind the contact card. Never use it as a card fill, text fill or section background elsewhere.

**The Quiet Middle Rule.** Between the two bands, colour is carried by navy, slate and hairlines. Violet appears only as links, checks, markers and focus; platform colours appear only as small dots, outlines and packets.

**The Identity Dot Rule.** Shopify, WooCommerce and Magento are always marked by their own colour (shopify-green, woo-purple, magento-orange) and nothing else is.

## Typography

**Display Font:** Geist (with system-ui, sans-serif), self-hosted variable woff2, weights 100 to 900
**Body Font:** Geist
**Label/Mono Font:** Geist Mono (with ui-monospace, monospace), tabular figures

**Character:** One neo-grotesque family, tight and confident in headings, calm in body; the mono face is a precision instrument reserved for numbers.

### Hierarchy
- **Display** (650, clamp(38px, 4.6vw, 62px), 1.08, -0.03em): the hero headline only. 34px at phone width.
- **Headline** (650, clamp(32px, 3.6vw, 48px), 1.08, -0.03em): section titles; the contact card title runs slightly larger, clamp(32px, 3.8vw, 50px).
- **Title** (650, 23px, -0.02em): tile titles; experience role titles at 22px; the featured case study title steps up to clamp(28px, 2.6vw, 36px).
- **Lede** (500, 19px, 1.55, ink-navy, max 40ch): the hero sub-line. Section intros sit at 18.5px in body slate.
- **Body** (400, 17px, 1.6): running copy; card copy at 15.5px; nav links at 15px weight 500.
- **Label** (500, 13px): chips, captions, legends, contact labels; diagram node labels 12 to 13px at 500 to 600.
- **Figure** (Geist Mono 500, 22px, -0.02em, tabular): stat values, dates in the experience list (14px), prices and rate amounts in sketches (12.5 to 15px), the shipment counter.

### Named Rules
**The Balanced Heading Rule.** Every h1, h2 and h3 is Geist 650 at -0.03em (tiles and roles -0.02em), line height 1.08, with `text-wrap: balance`. No heading is uppercase or tracked open.

**The Mono Is For Numbers Rule.** Geist Mono appears only on figures, dates, prices and counters. Never on headings, labels, buttons or body copy.

## Layout

A single centred column, max width 1180px, with 28px side gutters (16px at 760px and below). Sections run 96px top and bottom (68px at 760px and below) and alternate white and cool-grey, the grey ones bounded by hairlines top and bottom. Section heads cap at 680px with 48px below.

- **Hero:** two columns (1.02fr / 1fr, 56px gap): copy on the gradient at left, the tilting diagram panel at right. Padding 72px top, 120px bottom. Collapses to one column at 1000px.
- **Featured case study:** one wide card, two columns (1fr / 1.05fr, 48px gap): narrative, chips and checks at left; performance inset and stat row at right. One column at 1000px.
- **Bento:** a 6-column grid with 20px gaps. Shopify spans 4, Haleria 2; WordPress and Magento 3 each; the Eniture tile spans all 6 as a horizontal row. Every tile spans 6 at 1000px.
- **Experience:** a hairline-ruled list with a 220px date column and a 32px gap; stacks at 760px.
- **Stack:** two columns of definition rows (170px term column), one column at 1000px, stacked term over description at 760px.
- **Contact:** a white card (max 760px) floating on the lower band; its contact list is two columns, one at 760px.

**Breakpoints:** 1000px (grids collapse), 760px (phone layout, menu, tighter gutters, flat panel), 600px (vertical order-flow diagram, stacked bar labels).

## Elevation & Depth

A hybrid: surfaces are flat and separated by hairlines by default, and a short ladder of soft, cool, neutral shadows lifts the three kinds of white object that sit on a ground. Shadows are tinted with the navy-slate hue (rgba(20, 30, 45, a)), never pure black, never coloured, never hard-edged. Depth in the hero also comes from real 3D perspective on the diagram panel.

### Shadow Vocabulary
- **Rest** (`0 1px 2px rgba(20,30,45,.06), 0 2px 6px rgba(20,30,45,.05)`): bento tiles at rest.
- **Raised** (`0 2px 4px rgba(20,30,45,.05), 0 18px 40px -12px rgba(20,30,45,.18)`): the featured case study card, tiles on hover, the phone menu sheet.
- **Floating** (`0 4px 10px rgba(20,30,45,.06), 0 40px 80px -24px rgba(20,30,45,.26)`): objects that sit on the gradient: the hero diagram panel and the contact card.
- **Button** (`0 1px 2px rgba(20,30,45,.18), 0 4px 10px -4px rgba(20,30,45,.28)`): primary button only.

### Named Rules
**The Float On The Field Rule.** Only objects resting on the gradient band take the Floating shadow. Cards on white or grey grounds use Rest or Raised.

**The Soft Shadow Rule.** Every shadow is a diffuse, negative-spread, navy-tinted blur. No hard offset shadows, no glows, no coloured shadows.

## Shapes

Generously but not cartoonishly rounded, scaling with the object: 8px for nav links and the brand mark, 10px for inner nodes, sketch blocks and setting rows, 14px for chat bubbles (with a 4px tail corner on the speaker side), 16px for the performance inset and the diagram core, 18px for the hero panel, 20px for bento tiles, 22px for the feature and contact cards. Buttons, chips, live badges, toggles and bars are full pills (999px). Diagram nodes inside SVG use rx 10 to 16 to match.

The one hard silhouette is the skewed band: the hero band is clipped to `polygon(0 0, 100% 0, 100% 46%, 60% 100%, 0 100%)`, a diagonal that drops from the right edge to 60% across the bottom, so the gradient reaches into the Work section at the left; the contact band is clipped to `polygon(0 18%, 100% 0, 100% 100%, 0 100%)`, rising from left to right. At 760px and below the hero band becomes a fixed 570px tall shape clipped to `polygon(0 0, 100% 0, 100% 90%, 0 100%)`.

Illustrations bleed to the tile edge: the illustration block takes negative margins equal to the tile padding, keeps the tile's top corners (20px 20px 0 0), and sits on a cool-grey tint with a hairline beneath.

## Components

### Buttons
Confident, compact pills.
- **Shape:** full pill (999px), 11px by 18px, Geist 600 15px, 8px gap to a 16px stroke icon.
- **Primary:** ink-navy fill, white text, Button shadow. Hover lifts 1px, darkens to ink-navy-hover and slides the arrow 3px right.
- **Ghost:** white (92% on the gradient) with a strong hairline border and navy text. Hover warms the border to #b9c3d2 and the fill to cool grey.
- **Small:** 9px by 14px at 14px; used for the nav Download CV, whose label hides at 760px leaving the icon.
- **Focus:** global 3px accent-violet outline, 3px offset.
- **Text link:** Deep Signal Violet, 600, with a diagonal arrow that nudges 2px up-right on hover.

### Chips
- **Style:** cool-grey fill, 1px hairline, body-slate 13px 500, pill, 3px by 10px. Lists of stack terms only.
- **Placement:** in the featured case study they sit directly under the description; in tiles they sit below the copy, above the link.

### Cards / Containers
- **Feature card:** white, 22px corners, hairline border, Raised shadow, 44px padding (32px at 1000px, 22px at 760px).
- **Bento tile:** white, 20px corners, hairline border, Rest shadow, 30px padding (22px at 760px), 14px internal gap, link pinned to the bottom. Hover raises to Raised with a strong hairline; on fine pointers it leans up to 2deg toward the pointer.
- **Performance inset:** cool-grey, 16px corners, 24px padding, no border, no shadow.
- **Stat rows:** a hairline above, cells divided by vertical hairlines, Geist Mono figure over a muted 13.5px description. Never boxed.

### Navigation
- **Style:** sticky, solid white, 68px tall. Brand: a 30px ink-navy rounded tile holding a white mark, name in Geist 650. Links: 15px 500 body slate, 8px by 12px, 8px corners; hover goes ink with a cool-grey fill. A hairline and a near-invisible shadow appear once the page scrolls past 8px.
- **Mobile (760px):** links collapse into a 40px bordered menu button that opens a full-width white sheet below the bar, with a hairline and Raised shadow; tapping a link closes it.

### Gradient Band (signature)
A raw WebGL fragment shader (no library) paints two layers of 3D value noise blending the four field colours, drifting slowly and shifting a little with the pointer. It renders at reduced resolution (devicePixelRatio capped at 1.25, times 0.6) and lets CSS scale it soft; it pauses when off screen or the tab is hidden. The CSS linear gradient beneath is the fallback when WebGL is missing. With reduced motion it draws a single still frame.

### Hero Diagram Panel (signature)
A white figure (18px corners, Floating shadow, translucent white edge) in a 1400px perspective stage, resting at rotateX 6deg, rotateY -10deg. On fine pointers it tilts to follow the pointer and eases back over 0.6s on leave. A header row carries the title and a green pill "Live diagram" badge; a hairline footer carries the "Illustration of the real architecture" caption and a mono counter. Flat (no tilt) at 760px and below.

### Order-Flow Diagram (signature)
Inline SVG: platform nodes (white, hairline, rx 11, identity dot) wire into a violet-tinted FreightDesk core (gradient #f6f4ff to #eefbfd, stroke #d6d0fb) containing four stack nodes, which wire out to carrier nodes. Wires are 1.6px strong-hairline curves. Packets (4.5px circles in platform colours, then violet or teal on the outbound side) are spawned on one clock, ride the paths and fade at both ends. At 600px a vertical version replaces it: three platforms across the top, a 2 by 2 core, two carriers across the bottom. Reduced motion freezes packets mid-path.

### Performance Bars
Pairs of 10px pill bars on a bar-track rail: "before" in bar-before at full width, "after" in the violet-to-teal data gradient at its measured share. A navy label sits left and a Deep Signal Violet mono range sits right (stacked at 600px). A small legend follows.

### Bento Illustrations
Each tile with a picture opens on a bleeding cool-grey illustration block captioned at bottom right with a small white label ("Illustration" or "Demo conversation"). Contents are code-drawn UI: a storefront with a hand-drawn SVG shelving unit and a Shopify app block of shipping rates; a WordPress settings list with pill toggles; a Magento to FreightDesk sync wire with a riding dot.

### Chat Demo
Bubbles at 14px corners, 14px text, max 88% width: the visitor's in ink-navy with white text, aligned right with a 4px bottom-right corner; the bot's white with a hairline, aligned left with a 4px bottom-left corner. They play in one by one (1.1s apart) when the tile is 40% visible. A two-cell mono stat row follows.

### Experience List and Stack Rows
Experience: hairline-ruled rows, mono date and muted organisation at left, 22px role title and a violet-marked bullet list at right. Stack: definition rows with a hairline above, navy 600 term and slate description, both 15.5px.

### Contact Card
A white card on the rising contact band: 22px corners, Floating shadow, 48px padding (28px by 22px at phone). Headline, line, primary and ghost buttons, then a hairline-topped two-column list of muted labels over navy 600 links that turn violet and underline on hover.

### Motion
- **Easing:** one curve everywhere, `cubic-bezier(.16, 1, .3, 1)`; GSAP uses expo.out to match.
- **Reveals:** content is visible by default. With JS, sections below the fold start nudged (22px down, 60% opacity) and settle over 0.9s when they arrive. Nothing ever starts invisible.
- **Bars:** "before" bars grow from zero (0.9s), then "after" bars (1.4s, 0.5s delay), once, at 40% visibility.
- **Ambient:** the flow packets, the Magento wire dot (2.4s loop) and a WordPress toggle that flips every 2.6s.
- **Reduced motion:** all CSS animation and transition is disabled, the panel sits flat, packets freeze, the chat shows complete, bars show final widths, the gradient is a still frame.

## Do's and Don'ts

### Do:
- **Do** keep grounds white (canvas-white) and cool grey (cool-grey), separated by 1px hairlines (hairline).
- **Do** set every heading in Geist 650 at -0.03em with balanced wrapping, in ink-navy.
- **Do** confine the gradient to the skewed bands behind the hero and the closing contact card, and float white objects on it with the Floating shadow.
- **Do** draw imagery as inline SVG or code-built UI and label it ("Illustration", "Demo conversation", "Illustration of the real architecture").
- **Do** use Geist Mono with tabular figures for every number that measures something: stats, dates, prices, counters.
- **Do** mark Shopify, WooCommerce and Magento with their identity colours as small dots, outlines and packets.
- **Do** start every animated element in its visible state and give reduced motion a complete, still version.
- **Do** use the pill ink-navy primary and the white ghost as the only button pair.

### Don't:
- **Don't** go dark: no dark neon developer theme, no terminal green, no black grounds.
- **Don't** fall back to a plain template resume layout without the product-page craft.
- **Don't** use the gradient as a card fill, text fill or anywhere outside the two bands.
- **Don't** use hard offset shadows, glows or coloured shadows; shadows are soft and navy-tinted.
- **Don't** set headings, labels or buttons in Geist Mono.
- **Don't** add kickers or eyebrow labels above headings.
- **Don't** use raster screenshots or generated images in place of diagrams; never present an illustration as a real screenshot.
- **Don't** make the nav translucent or blurred; it is solid white.
