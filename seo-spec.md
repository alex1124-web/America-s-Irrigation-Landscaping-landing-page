# SEO Spec — Local Landscaping Landing Page
Budget tier: $250 | Date: 2026-06-10

---

## 1. Title Tag
```
Landscaping Services in [City] | Free Estimates
```
(48 chars — stays under 60)

---

## 2. Meta Description
```
Professional landscaping in [City]. Lawn care, yard cleanup & landscape design. Call today for a free estimate. Locally owned & operated.
```
(138 chars — stays under 155)

---

## 3. H1
```
Landscaping Services in [City] — Locally Owned, Free Estimates
```

---

## 4. LocalBusiness Schema (JSON-LD)
```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "LandscapeService",
  "name": "BUSINESS_NAME",
  "telephone": "PHONE",
  "url": "https://www.DOMAIN.com",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "ADDRESS",
    "addressLocality": "CITY",
    "addressRegion": "STATE",
    "postalCode": "ZIP",
    "addressCountry": "US"
  },
  "areaServed": {
    "@type": "City",
    "name": "CITY"
  },
  "priceRange": "$$",
  "description": "Professional landscaping services in CITY including lawn care, yard cleanup, and landscape design."
}
</script>
```

---

## 5. Open Graph Tags
```html
<meta property="og:title" content="Landscaping Services in [City] | Free Estimates" />
<meta property="og:description" content="Professional landscaping in [City]. Lawn care, yard cleanup & landscape design. Locally owned. Call for a free estimate." />
<meta property="og:type" content="website" />
```

---

## 6. 5 Target Keywords
1. landscaping services [city]
2. lawn care [city]
3. local landscaper near me
4. yard cleanup [city]
5. landscape design [city]

---

## 7. One On-Page Tip
Embed a real Google Maps iframe showing your service area and include your full NAP (Name, Address, Phone) in plain HTML text — not an image — so Google can parse and trust your location signals.
