# Booking-First Landing Page

This workspace contains a single static landing page in `index.html`.

## What it does

- Puts the booking calendar first
- Keeps a secondary form for name, email, and phone capture
- Is built to work with GoHighLevel / LeadConnector embeds

## What to change

Open [`index.html`](/Users/adamamick/Documents/How to Peptide/index.html) and update:

- `CALENDAR_EMBED_URL`
- `FORM_EMBED_URL`
- brand name
- headline and body copy
- compliance/disclaimer language for your business

## Example embed URLs

Calendar:

```text
https://api.leadconnectorhq.com/widget/bookings/your-calendar-slug
```

Form:

```text
https://api.leadconnectorhq.com/widget/form/your-form-id
```

## Publish options

- Upload to Netlify as a static site
- Drop into another static host
- Rebuild the same layout inside a GoHighLevel funnel if you prefer native hosting
