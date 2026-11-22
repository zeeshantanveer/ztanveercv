---
name: Zeeshan Tanveer Portfolio
description: A full-stack portfolio drawn as a working transit network; the visitor rides the stack stop by stop.
colors:
  enamel-ground: "#eef1ee"
  enamel-white: "#fbfcfb"
  plate-navy: "#14253f"
  plate-navy-raised: "#22385c"
  timetable-ink: "#3e4f68"
  platform-rule: "#d3d9de"
  platform-tint: "#e6eaee"
  trunk-orange: "#f26b21"
  trunk-orange-ink: "#b4470c"
  on-orange: "#1a0d04"
  shopify-green: "#2e9e4f"
  woocommerce-purple: "#7a3e9d"
  magento-red: "#d6332b"
  wordpress-blue: "#1e5aa8"
  realtime-teal: "#0a8f96"
  spur-grey: "#8d96a0"
  ravi-blue: "#cfe2ec"
  ravi-ink: "#5f8aa0"
typography:
  display:
    fontFamily: "Overpass, system-ui, sans-serif"
    fontSize: "clamp(38px, 5.4vw, 70px)"
    fontWeight: 800
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Overpass, system-ui, sans-serif"
    fontSize: "clamp(24px, 2.6vw, 32px)"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-0.015em"
  title:
    fontFamily: "Overpass, system-ui, sans-serif"
    fontSize: "19px"
    fontWeight: 800
    lineHeight: 1.2
  body:
    fontFamily: "Overpass, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Overpass, system-ui, sans-serif"
    fontSize: "13.5px"
    fontWeight: 700
    lineHeight: 1.1
  figure:
    fontFamily: "Overpass Mono, ui-monospace, monospace"
    fontSize: "15px"
    fontWeight: 600
    fontFeature: "tnum"
  urdu:
    fontFamily: "Nastaliq Sign, serif"
    fontSize: "22px"
    fontWeight: 500
    lineHeight: 1.9
rounded:
  label: "4px"
  sign: "6px"
  pill: "999px"
  roundel: "50%"
spacing:
  chip-gap: "6px"
  row: "9px"
  stack: "14px"
  block: "18px"
  sign-inset: "22px"
  sign-inset-hero: "26px"
  sign-inset-phone: "16px"
components:
  button-primary:
    backgroundColor: "{colors.plate-navy}"
    textColor: "{colors.enamel-white}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "13px 20px 11px"
  button-primary-hover:
    backgroundColor: "{colors.trunk-orange}"
    textColor: "{colors.on-orange}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.plate-navy}"
    rounded: "{rounded.pill}"
    padding: "13px 20px 11px"
  button-ghost-hover:
    backgroundColor: "{colors.plate-navy}"
    textColor: "{colors.enamel-white}"
  chip-button:
    backgroundColor: "{colors.enamel-white}"
    textColor: "{colors.plate-navy}"
    rounded: "{rounded.pill}"
    padding: "8px 14px"
  sign:
    backgroundColor: "{colors.enamel-white}"
    textColor: "{colors.plate-navy}"
    rounded: "{rounded.sign}"
    width: "min(560px, 100%)"
  sign-head:
    backgroundColor: "{colors.plate-navy}"
    textColor: "{colors.enamel-white}"
    typography: "{typography.headline}"
    padding: "16px 22px 13px"
  hero-role-band:
    backgroundColor: "{colors.trunk-orange}"
    textColor: "{colors.on-orange}"
    padding: "9px 26px 7px"
  line-chip:
    backgroundColor: "transparent"
    textColor: "{colors.timetable-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "3px 10px 2px 4px"
  change-note:
    backgroundColor: "{colors.platform-tint}"
    textColor: "{colors.plate-navy}"
    rounded: "{rounded.label}"
    padding: "7px 10px 5px"
  map-key:
    backgroundColor: "{colors.enamel-white}"
    rounded: "{rounded.sign}"
    width: "286px"
  map-key-item-current:
    backgroundColor: "{colors.platform-tint}"
    textColor: "{colors.plate-navy}"
  map-label:
    backgroundColor: "{colors.enamel-white}"
    textColor: "{colors.plate-navy}"
    rounded: "{rounded.label}"
    padding: "4px 7px 3px"
  map-label-hub:
    backgroundColor: "{colors.plate-navy}"
    textColor: "{colors.enamel-white}"
---

# Design System: Zeeshan Tanveer Portfolio

## Overview

**Creative North Star: "The Orange Line System Map"**

The page is a printed metro system map that has been lifted into three dimensions. An enamel signage ground carries a pale Ravi river band; route lines in full transit colour run between white roundel stations; every piece of content is a deep navy platform sign bolted over the map. The stack is the network: storefront lines (Shopify green, WooCommerce purple, Magento red, WordPress blue) feed the FreightDesk interchange, the orange trunk runs out to the carrier hub and its grey spurs, and the teal real-time line runs to the chatbot terminus. Scrolling rides the camera from stop to stop.

The density is that of public signage: few words per plate, large confident lettering, measured figures set like a timetable, nothing ornamental that a transit authority would not print. Bilingual naming (English in Overpass, Urdu in Nastaliq beside it) places the network in Lahore without decoration. The map, the trains and the timetables are the imagery; there are no photographs or rasters.

The system refuses the developer-portfolio defaults it was chosen against: a name hero over a grid of project cards, and the dark neon look. Light enamel ground, navy plates and transit colour are the whole vocabulary.

**Key Characteristics:**
- Enamel ground, navy plates, full-saturation route colours used only as lines, bands, roundels and chips.
- One shared network dataset drives the 3D map, the drawn SVG fallback and the map key.
- Every content block is a platform sign: navy head, line-coloured band, enamel body.
- Measured results live in timetable tables set in Overpass Mono with tabular figures.
- Urdu station names in Nastaliq sit opposite every English sign title.
- Motion is one clock for trains and a scroll-scrubbed camera; content is always visible without it.

## Colors

A signage palette: two neutrals of enamel, one navy for every plate and all text, and six route colours that each belong to exactly one line of the network.

### Primary
- **Plate Navy** (#14253f): every sign head, the brand pill, primary buttons, hub labels, station roundel rims in 3D and SVG, body text, and the default bullet ring. It is also `--ink`; text and plates are the same navy.
- **Trunk Orange** (#f26b21): the FreightDesk trunk line, the hero role band, focus rings, text selection, primary button hover, and the default band of a route list or go-link when no line colour is set.

### Secondary (route colours; one per line)
- **Shopify Green** (#2e9e4f): the Shopify line and its stop. Also the "good service" pulse ring and the visited punch tick on the key.
- **WooCommerce Purple** (#7a3e9d): the WooCommerce line.
- **Magento Red** (#d6332b): the Magento line.
- **WordPress Blue** (#1e5aa8): the WordPress branch line, and the earliest segment of the service-history track.
- **Real-time Teal** (#0a8f96): the WebSockets and AI chat line (Haleria to Eniture).
- **Spur Grey** (#8d96a0): carrier spurs off the carrier hub, and the neutral track of the standards route list. Decorative line colour only, never text.

### Tertiary
- **Trunk Orange Ink** (#b4470c): orange when it must read as text on enamel: go-link hover and timeline dates.
- **On Orange** (#1a0d04): the near-black brown used for text set on Trunk Orange (hero role band, hovered primary button). White is never set on orange.

### Neutral
- **Enamel Ground** (#eef1ee): page background, header bar, 3D scene background, fog colour and ground plane, SVG label halo.
- **Enamel White** (#fbfcfb): sign bodies, map key, station roundel faces, train bodies, map label plates.
- **Plate Navy Raised** (#22385c): scrollbar thumb; the one lighter navy.
- **Timetable Ink** (#3e4f68): secondary text: sign paragraphs, timetable row heads, key items at rest, chip text, footer.
- **Platform Rule** (#d3d9de): 1.5px hairlines between timetable rows, under the header bar, around line chips, above the key footer.
- **Platform Tint** (#e6eaee): the "change here" note and the current stop in the key.
- **Ravi Blue** (#cfe2ec): the river band in 3D and SVG.
- **Ravi Ink** (#5f8aa0): the spaced italic RAVI river label only.

### Named Rules
**The One Line, One Colour Rule.** Each route colour names exactly one line of the network. A stop's `--c` is its line colour, and it colours that stop's head band, head roundel, built-list track, go-link underline and key swatch together. Never use a route colour for an unrelated accent.

**The Navy Plate Rule.** All text and all sign heads are Plate Navy on enamel, or white on navy. Route colours carry no body text; on orange the text is On Orange, never white.

**The Shared Network Rule.** Line colours exist twice: as CSS custom properties and as hex literals in the `NET` dataset that builds the 3D map, the SVG fallback and the key. Change both together or the map and the signs drift apart.

## Typography

**Display Font:** Overpass variable, 100 to 900 (with system-ui, sans-serif)
**Body Font:** Overpass (same family)
**Label/Mono Font:** Overpass Mono, 300 to 700 (with ui-monospace, monospace)
**Script Font:** Nastaliq Sign, a self-hosted Nastaliq subset at weight 500, for Urdu names only

**Character:** Overpass is a highway-signage face; at weight 800 with tight tracking it reads as a platform plate, and at 400 it is a plain, open reading face. Overpass Mono with tabular figures turns measured results into a timetable. Nastaliq gives every plate a second, local name.

### Hierarchy
- **Display** (800, clamp(38px, 5.4vw, 70px), line-height 0.98, tracking -0.03em): the name on the hero sign only.
- **Terminus headline** (800, clamp(30px, 4vw, 48px)): the terminus sign title, one step below display.
- **Headline** (800, clamp(24px, 2.6vw, 32px), line-height 1.05, tracking -0.015em): every sign head title, preceded by its line roundel.
- **Title** (800, 19px, line-height 1.2): service-history entries. Route-list item titles use 800 at 16.5px.
- **Body** (400, 17px, line-height 1.55; 16px on phones): sign paragraphs. The hero paragraph is 18px with a 52ch measure. Built-list items are 15.5px, notes 14px.
- **Label** (700, 13 to 14.5px): line chips (13.5px), map labels (13px, hubs 14px), key items (600, 14.5px), table captions (800, 13px, tracking 0.02em), chip buttons (700, 14px). Buttons are 800 at 16px. UI labels are never uppercase; only the map's river name is set in spaced capitals.
- **Figure** (Overpass Mono 600, 14 to 15px, tabular-nums): timetable values, right-aligned, and timeline dates.
- **Urdu** (Nastaliq Sign 500, line-height 1.9, right-to-left): 22px on sign heads at 90% opacity, clamp(24px, 2.6vw, 34px) on the hero, 15px on the key head.

### Named Rules
**The Timetable Rule.** Any measured number (counts, times, percentages) is set in Overpass Mono with tabular figures inside a timetable table: row head left in Overpass, value right in Mono. Narrative copy stays in Overpass.

**The Two Names Rule.** Every sign head and the key head pair the English title with its Urdu name in Nastaliq, marked `lang="ur"`. The Urdu sits opposite the title, never inline in body copy.

## Layout

The 3D map is a fixed full-viewport layer (z 0) with its CSS label layer above it (z 1). Content scrolls over it in `main` (z 10) as a column of stops; the header bar (z 40) and map key (z 30) are fixed.

- **Stops.** Each stop is at least 92svh tall, a flex row that centres its sign vertically, padded 110px top, 4vw sides, 80px bottom. Stops alternate left and right (`.right` pushes the sign to the right edge) so the camera can frame the station in the free half of the screen. Above 900px, right-hand stops reserve 340px on the right so signs never sit under the fixed key. The hero aligns its sign to the bottom with 9vh below.
- **Sign widths.** Standard signs are min(560px, 100%); the terminus is 720px; service history is 980px and bottom-aligned on desktop.
- **Inner rhythm.** Sign insets 22px (26px on the hero, 16px on phones). Vertical rhythm inside a body steps 6, 9, 14, 18px: chip gaps 6px, built-list rows 9px, paragraph spacing 14px, block spacing 18px.
- **Breakpoints.** 901px and up: fixed key at bottom right (22px inset, 286px wide). 900px and below: the key becomes a sheet opened by a "Stops" chip button in the header, inset 12px; the service-history track turns vertical. 640px and below: body 16px, header padding 10px 12px, chip button text hidden to icon only, contact list single column, the hero service line hidden.
- **Phone map windows.** On phones every stop except the hero drops its minimum height and gains 58svh of top padding, so each stop opens on a clear window of the map with the camera framing its station, and the sign then scrolls up over it. Signs centre horizontally and sit at the bottom.

## Elevation & Depth

Depth is literal: the map is a lit 3D scene, and the HTML layer reads as enamel plates mounted in front of it. The page uses soft, navy-tinted, downward shadows for the plates and a single directional sun for the map. Nothing else is shadowed; chips, buttons and the header are flat.

### Shadow Vocabulary
- **Platform plate** (`box-shadow: 0 2px 4px rgba(20, 37, 63, .08), 0 24px 48px -24px rgba(20, 37, 63, .45)`): every platform sign.
- **Key plate** (`box-shadow: 0 2px 4px rgba(20, 37, 63, .08), 0 18px 40px -20px rgba(20, 37, 63, .45)`): the map key, a slightly shorter drop.
- **Label tab** (`box-shadow: 0 1px 2px rgba(20, 37, 63, .18)`): station labels floating over the map.
- **Map ground shadow**: one directional sun from upper left casting soft PCF shadows onto a navy shadow layer at 13% opacity over the unlit enamel ground. Tubes, trains and roundels cast; shadows are switched off on phones.

### Named Rules
**The Navy Shadow Rule.** Every shadow is tinted Plate Navy (rgb 20, 37, 63), never neutral black, and falls straight down. No offset or hard-edged shadows.

## Shapes

Transit geometry: pills, circles and gently squared plates.

- **Plates** (6px radius): signs, the key, the skip link. Corners are only slightly softened, like pressed enamel.
- **Tabs** (4px radius): map labels, the change note, focus rings.
- **Pills** (999px): every button, chip button, line chip and the brand mark.
- **Roundels** (50%): the brand roundel (orange ring crossed by a bar), sign-head roundels (enamel face with a 5px ring in the line colour), station markers (enamel face with a navy ring), list stop dots, key swatch dots, chip dots.
- **Tracks** (rounded bars, 4 to 7px thick, radius half the thickness): built-list track, route-list track, service-history track, key swatches. In 3D, lines are tubes with 2-unit rounded corners at every bend, like a printed metro diagram.

## Components

### Buttons
Confident and pill-shaped, like the destination blinds on a train.
- **Shape:** full pill (999px), 2px Plate Navy border, Overpass 800 at 16px, padding 13px 20px 11px, an inline 17px stroke icon after the label.
- **Primary:** Plate Navy fill, white text. Hover fills Trunk Orange with On Orange text and an orange border.
- **Ghost:** transparent with navy text and border. Hover fills navy with white text.
- **Transitions:** background and colour 0.25s on the house ease-out; removed under reduced motion.
- **Chip button (header):** smaller pill (8px 14px, 700 at 14px) on Enamel White with a 2px navy border and a 16px icon; hover inverts to navy. On phones the label hides and the icon remains, with a screen-reader label kept.
- **Focus:** a 3px Trunk Orange outline at 3px offset on every focusable element.

### Chips
- **Line chip:** a pill with a 1.5px Platform Rule border, Timetable Ink text at 700 13.5px, and a 16px solid dot in the chip's own line colour on its left. A stop's chips can mix lines (WordPress blue beside WooCommerce purple) to show which lines meet there.

### Platform Sign (signature component)
The container for every piece of content.
- **Body:** Enamel White, 6px radius, platform-plate shadow, clipped corners.
- **Head:** Plate Navy with white Overpass 800 title, preceded by a 22px head roundel in the stop's line colour, and the Urdu name opposite at 90% opacity. When the stop has a line, a 6px band in that colour runs under the head.
- **Hero variant:** larger insets, display-size name, and a full-width Trunk Orange role band under the head with On Orange text.
- **Line chips** under the head, then the body.
- **Change note:** a Platform Tint tab in navy 700, "Change here for..." at interchanges.
- **Built list:** items hang on a 4px track in the line colour, each marked by a 10px enamel stop dot with a 3px navy ring.
- **Timetable:** full-width table, a 13px 800 caption, rows divided by 1.5px Platform Rule, row heads in Timetable Ink 600, values right-aligned in Overpass Mono 600.
- **Go-link:** navy 800 text with a 3px underline bar in the line colour and an up-right arrow icon; hover turns the text Trunk Orange Ink.

### Map Key (navigation)
A small navy-headed plate listing every stop. Each row is a three-column grid: a 6px line swatch with a navy-ringed stop dot centred on it, the stop name, and a green tick that punches in (fade and scale from 0.4) once the stop is visited. The current stop gets Platform Tint and navy 800 text; hover gets Enamel Ground. The footer counts visited stops, says the ride is saved on the device, and offers a Reset text button. Visited stops and the last stop are stored in local storage and offered back on the hero as a resume link.

### Route List
A vertical line for lists of practices: a 6px Spur Grey track with 14px enamel stops ringed 3.5px in navy, each item a navy 800 title over a Timetable Ink line.

### Service History Timeline
A horizontal track (vertical at 900px and below) 7px thick, painted in hard-stopped segments of WordPress Blue, WooCommerce Purple and Trunk Orange to mark eras, with 22px enamel stops ringed 4px in navy. Each entry: a Mono date in Trunk Orange Ink, a 19px 800 title, and supporting text.

### The 3D Network Map
- **Scene:** Enamel Ground background and ground plane with fog from 130 to 280 units; hemisphere light plus one shadow-casting sun; the Ravi as a flat pale blue ribbon below the network.
- **Lines:** tubes (radius 0.34; spurs 0.18) along metro paths with rounded bends, satin finish.
- **Stations:** enamel cylinders with a navy torus rim on top and a navy band at the base; hubs are larger (1.1 vs 0.8).
- **Trains:** white box bodies with end caps in the line colour, roughly one train per 9 units of line, all moving at one speed on one clock.
- **Labels:** CSS labels on enamel tabs above each station; hubs are navy tabs; line ends read "from Shopify stores" and similar in plain Timetable Ink; the river label is spaced italic RAVI.
- **Camera ride:** each stop has a pose that places its station in the free side of the screen, clear of its sign. Scroll position between two stops scrubs the camera between their poses with a hold at each end (the first and last 18% of the span are still, the middle eased with smoothstep), damped toward the target each frame. Wide stops (hero, service history, terminus) pull back to an overview. The opening frame glides down from a higher, further pose. A slight pointer parallax adds life on desktop.
- **Line dimming:** arriving at a stop fades every line not serving it to 16% opacity over 0.9s and stops it casting shadows; labels of stations and line ends off those lines hide.
- **Label hiding:** labels hide when they would clip the viewport edge (beyond 82% horizontally or 86% vertically from centre) or come within 6px of any sign, the key or the header. Overview stops show only hub, line-end and river labels. On phones only hub labels show, and at overview only FreightDesk.
- **Budget:** pixel ratio capped at 1.75 (1.5 on phones), shadows off on phones, rendering paused while the tab is hidden.

### Drawn Fallback Map
An SVG built from the same network data: the river band, grey spurs, coloured polylines, enamel station circles with navy rims, navy labels with an Enamel Ground halo placed clear of every line, and the RAVI label. It is the poster shown at once while 3D loads, crossfading out over 0.9s when the first frame renders, and it is the whole map when WebGL is unavailable or reduced motion is requested.

### Motion
- **House ease:** cubic-bezier(.16, 1, .3, 1) in CSS, expo.out in GSAP.
- **Sign arrival:** signs are visible by default. When a stop enters (top at 70% of the viewport, once), the sign eases from a 60px horizontal nudge toward its side (40px upward on phones) and 75% opacity over 1.1s; the head wipes in left to right by clip over 0.9s; chips, list items, table rows and timeline entries rise 14px from 70% opacity with a 0.05s stagger.
- **Reduced motion or no WebGL:** no 3D, no sign motion, no transitions on buttons, labels or the key punch; the drawn map stands still behind plain scrolling, and key tracking and ride memory still work.

## Do's and Don'ts

### Do:
- **Do** put every content block on a platform sign: navy head with roundel and Urdu name, line-coloured band, enamel body.
- **Do** colour a stop entirely from its one line colour (`--c`): band, head roundel, built-list track, go-link underline, key swatch.
- **Do** set measured results in a timetable table with Overpass Mono tabular figures, right-aligned.
- **Do** keep the network data single-sourced so the 3D map, the SVG fallback and the key always agree.
- **Do** frame each station in the free half of the screen and hide any map label a sign would cut through.
- **Do** keep content visible before any motion runs; motion only nudges signs from an already-readable state.
- **Do** give phones a 58svh map window above each stop's sign.
- **Do** tint every shadow Plate Navy and let it fall straight down.

### Don't:
- **Don't** build a name hero over a grid of project cards, or use a dark neon developer look.
- **Don't** use a route colour for anything other than its line, or set body text in a route colour.
- **Don't** set white text on Trunk Orange; use On Orange (#1a0d04).
- **Don't** use Spur Grey or Ravi Ink for readable content text; they are line and map-label colours.
- **Don't** set narrative copy in Overpass Mono, or uppercase UI labels; the spaced italic RAVI river name is the one cartographic exception.
- **Don't** use hard offset shadows, glyph icons or photographic imagery; icons are inline stroke SVGs.
- **Don't** let the 3D map be the only way to read a stop; every station is written out as text on its sign.
