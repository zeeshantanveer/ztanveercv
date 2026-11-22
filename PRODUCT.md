# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML, CSS and JavaScript with Three.js (WebGL) and GSAP loaded from a CDN. No build step. Hosted on GitHub Pages from the `main` branch of `zeeshantanveer/ztanveercv`; the portfolio lives in `portfolio/` and is served at https://zeeshantanveer.github.io/ztanveercv/portfolio/.

## Users

Hiring managers and technical leads at CodeEnlight (Lahore), reviewing Zeeshan Tanveer's application for a Full-Stack Developer role. They open the portfolio from the CV link, usually on a laptop, sometimes on a phone, and decide within minutes whether he can "hit the ground running" on client work in Laravel, Vue/React, WordPress, Shopify and Magento.

## Product Purpose

A personal portfolio that qualifies Zeeshan for the CodeEnlight Full-Stack Developer role (CV: `output/pdf/Zeeshan Tanveer - Full-Stack Developer (Laravel, React, CMS).pdf`, source `cv_fullstack_codeenlight.html`). Success: the reviewer sees real, live, relevant work across the stack and platforms the job names, believes the front-end quality claims because the portfolio itself demonstrates them, and contacts him or downloads the CV.

## Positioning

Seven years of production work that spans the exact mix the job lists: PHP/Laravel back ends, React front ends, and live products on WordPress/WooCommerce, Shopify and Magento, tied together by one real system (FreightDesk Online) that imports orders from those platforms and talks to 30+ carrier APIs, plus real-time and AI chat products in production.

## Operating Context

Read alongside the CV during screening. The job ad stresses: standards-compliant HTML5/CSS3/ES6, responsive techniques, PHP frameworks (Laravel), progressive JS frameworks (Vue, React), CMS (WordPress), Figma/Sketch, REST/GraphQL, Git, interest in emerging tech (AR, VR), onsite SEO and content hierarchy, web accessibility, browser QA, JavaScript performance, WebSockets and Local Storage, mentoring and deep code review, triaging production issues with support.

## Capabilities and Constraints

- Static hosting only; no server code. External links go to live products.
- Must stay accessible (keyboard, screen readers, reduced motion) and fast on phones; heavy effects must degrade gracefully.
- Copy must not use em dashes or en dashes.
- Not claimed and must not be added: Vue, Quasar, LESS, Handlebars, Photoshop, Keycloak, Jenkins, AR/VR project work.

## Brand Commitments

- Name: Zeeshan Tanveer. Portrait: `4182d1ef-129e-41c8-a145-03324dbda418.png` (repo root).
- User explicitly rejects: dark neon "developer" cliche, template or AI-generated look, gimmicks that make projects or facts hard to read. User asked for an interactive, 3D, motion-rich experience.

## Evidence on Hand

Confirmed facts (from the CVs and user answers in this repo):
- FreightDesk Online (freightdesk.online): Laravel/Node.js back ends, React (and Angular) front ends, MySQL/PostgreSQL; 30+ LTL carrier and 6+ parcel APIs (REST and SOAP); imports orders from 7+ e-commerce platforms including Shopify, WooCommerce and Magento (Magento integration built by Zeeshan); 20+ Redis queue jobs; Stripe payments and webhooks; 30,000+ shipments a month; dashboard queries cut from 4 to 5 s to under 500 ms; live rate quotes cut from about 12 s to about 3 s.
- Eniture WordPress/WooCommerce shipping plugins on wordpress.org (PHP, jQuery, hooks, settings, checkout).
- FreightDesk Shopify App (apps.shopify.com/freightdesk-online-1): Admin GraphQL and REST, webhooks, OAuth, App Bridge, Billing, theme app extensions. Haleria also published on the Shopify App Store.
- Haleria (haleria.com): AI support platform; web chat with WebSockets and local storage; conversations stored in MongoDB; 50,000+ conversations a month; merchant support time cut by 60%; webhook race condition fixed with idempotency keys.
- Eniture.com AI chatbot: production, live on eniture.com, recently launched.
- HousePilot (housepilot.de): property platform, Germany (GDPR). Role details not confirmed.
- Experience: AlignPX Technologies, Software Engineer (Full-Stack, Team Lead), March 2019 to present, 5-member Agile team, delivery time cut 25%. Topdot Software House, Software Engineer, August 2018 to March 2019, 4+ apps, 2,000+ daily users, performance +20%, bug resolution time cut 35%. BS Computer Science, Virtual University of Pakistan, 2014 to 2018.
- Contact: z.tanvir22@gmail.com, +92 312 0576200, github.com/zeeshantanveer, linkedin.com/in/zeeshan-tanveer.
- No screenshots of the products are stored in the repo. No testimonials, client logos or press exist; none may be invented.

## Product Principles

- The work is the proof: every claim links to something live or is a stated measured result.
- Demonstrate the front-end qualities the job asks for (accessibility, performance, responsive, SEO) in the portfolio itself.
- Relevance first: Laravel, React, WordPress/WooCommerce, Shopify and Magento lead; AI work supports.
- Motion and 3D serve understanding of the systems, never hide facts.

## Accessibility & Inclusion

WCAG 2.2 AA intent: keyboard operable, visible focus, sufficient contrast, meaningful alternatives for any canvas content, and a full experience with `prefers-reduced-motion` and without WebGL.
