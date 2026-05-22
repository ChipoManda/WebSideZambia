# GiftedAcadem

Past papers for Biomedical Science students across Africa and the world.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page, registration, dashboard |
| `library.html` | Paper library, browse by course, university, year |
| `viewer.html` | Paper viewer with toggle answers, read aloud, print |

## Setup for GitHub Pages

1. Rename `giftedacadem-landing.html` to `index.html`
2. Push all three HTML files to your repository root
3. Go to Settings, Pages, set source to main branch, root folder
4. Your site will be live at `https://yourusername.github.io/repository-name`

## Notes

- All data is currently hardcoded in the JS — replace with API calls when backend is ready
- Payment flow (K24.12/month) connects to MTN MoMo and Airtel Money via your Node/Railway backend
- Source URLs on papers point to publicly available repositories (AIIMS, RGUHS, NTRUHS, Delhi, Meru)
- Papers from Zambian universities to be populated via student networks and direct university contact

## Stack

Frontend: HTML, CSS, Vanilla JS  
Backend (to connect): Node.js, Express, Railway  
Database: PostgreSQL  
Payments: MTN Mobile Money, Airtel Money, Flutterwave  
AI tutor: Anthropic Claude Haiku
