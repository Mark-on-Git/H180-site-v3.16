# HANGOVR 180 — Brand Site

**Live URL:** Deployed on Vercel  
**Version:** 3.12  
**Last updated:** April 4, 2026

## Overview

Static marketing site for HANGOVR 180, a pre-alcohol supplement brand based in Austin, TX.

## Tech Stack

- Static HTML/CSS (no framework, no build tools)
- Font: Montserrat (Google Fonts)
- Hosting: Vercel (auto-deploys from this repo)

## Structure

```
/
├── index.html          Home
├── doa180.html         Do A 180
├── whos-in.html        Who's In
├── inside.html         Inside
├── find-us.html        Find Us
├── stock-up.html       Stock Up
├── vercel.json         Vercel deployment config
└── images/             All site images (24 files)
```

## Brand Colors

| Name   | Hex       |
|--------|-----------|
| Yellow | `#FFD800` |
| Black  | `#303633` |
| Red    | `#C7084F` |
| White  | `#FFFFFF` |

## Deployment

Push to main branch. Vercel auto-deploys.

## Notes

- Each HTML page contains all its own CSS inline (no shared stylesheet)
- Only JavaScript on the site is the mobile menu toggle and the reviews carousel on doa180.html
- Email signup forms are placeholder only (`onsubmit="event.preventDefault();"`)
- Cart link points to stock-up.html (headless Shopify integration pending)
