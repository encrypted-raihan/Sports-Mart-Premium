# Sports Mart Premium — Complete SEO Strategy
# Generated: June 2026
# Scope: Local SEO + Ecommerce SEO + AI Search Visibility

---

## PHASE 1 — SEO AUDIT FINDINGS

### Critical Issues (Fix Immediately)

1. **Missing canonical tags** — Every page needs `<link rel="canonical" href="...">` to prevent duplicate content.
2. **Missing meta robots** — Add `<meta name="robots" content="index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1">` on all public pages.
3. **No structured data on current pages** — LocalBusiness and Product schemas are absent.
4. **No sitemap** — Googlebot cannot discover pages efficiently.
5. **Missing manifest.json** — No PWA support.
6. **Unsecured og:image URL** — OG images need absolute HTTPS URLs.
7. **No hreflang** — Consider adding `hreflang="en-IN"` for English content targeting India.

### Medium Issues

8. **Title tag too short on homepage** — "Sports Mart Premium — Kottarakkara" should be expanded to include primary keyword.
9. **Meta description too generic** — Needs to include city, USP, and CTA.
10. **No internal linking structure** — Product cards don't link to individual product pages.
11. **Missing alt text** — Sport slide images (`::before` background images) have no descriptive alt text available to crawlers.
12. **Google Fonts blocking render** — `display=swap` is set which is good, but consider self-hosting.
13. **No breadcrumbs** — Breadcrumb navigation missing from product pages.
14. **Cart drawer uses localStorage** — This is fine for UX but ensure product pages have crawlable content.

### Low Priority

15. Products loaded via JS — product data in localStorage is not crawlable by Googlebot. Static HTML fallback or server-side rendering needed for product pages to rank individually.
16. No blog/content section — limits long-tail keyword capture.
17. CSS is fully inline — consider splitting critical CSS vs deferred CSS for LCP improvement.

---

## PHASE 2 — COMPLETE SEO <HEAD> SNIPPET

### Homepage head (replace existing):
```html
<!-- === SEO HEAD: Sports Mart Premium Homepage === -->
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<!-- Primary SEO -->
<title>Sports Mart Premium — Best Sports Shop in Kottarakkara, Kerala | Cricket, Football, Badminton</title>
<meta name="description" content="Kottarakkara's No.1 sports store since 2014. Buy cricket bats, football boots, badminton rackets, fitness gear and sportswear. Visit us at Pulamon Junction or order via WhatsApp: +91 89213 73326." />
<meta name="keywords" content="sports shop kottarakkara, cricket equipment kerala, football boots kollam, badminton racket kottarakkara, sports store kollam district, sportswear kerala" />
<meta name="robots" content="index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1" />
<link rel="canonical" href="https://sportsmartpremium.in/" />
<meta name="author" content="Sports Mart Premium" />
<meta name="geo.region" content="IN-KL" />
<meta name="geo.placename" content="Kottarakkara, Kerala, India" />
<meta name="geo.position" content="9.0037;76.7788" />
<meta name="ICBM" content="9.0037, 76.7788" />

<!-- Open Graph -->
<meta property="og:title" content="Sports Mart Premium — Kottarakkara's Best Sports Store" />
<meta property="og:description" content="10+ years of trust. Cricket, football, badminton, fitness, sportswear. Order via WhatsApp or visit us at Pulamon Junction, Kottarakkara." />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://sportsmartpremium.in/" />
<meta property="og:image" content="https://sportsmartpremium.in/images/og-home.jpg" />
<meta property="og:image:width" content="1200" />
<meta property="og:image:height" content="630" />
<meta property="og:image:alt" content="Sports Mart Premium store front, Kottarakkara Kerala" />
<meta property="og:site_name" content="Sports Mart Premium" />
<meta property="og:locale" content="en_IN" />

<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" content="Sports Mart Premium — Kottarakkara's Best Sports Store" />
<meta name="twitter:description" content="Cricket, football, badminton, fitness gear and sportswear. Order via WhatsApp." />
<meta name="twitter:image" content="https://sportsmartpremium.in/images/og-home.jpg" />

<!-- PWA -->
<link rel="manifest" href="/manifest.json" />
<meta name="theme-color" content="#D9C24F" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="default" />
<meta name="apple-mobile-web-app-title" content="Sports Mart" />

<!-- Icons -->
<link rel="icon" type="image/png" sizes="32x32" href="/icons/favicon-32x32.png" />
<link rel="icon" type="image/png" sizes="16x16" href="/icons/favicon-16x16.png" />
<link rel="apple-touch-icon" sizes="180x180" href="/icons/apple-touch-icon.png" />
<link rel="mask-icon" href="/icons/safari-pinned-tab.svg" color="#D9C24F" />
<meta name="msapplication-TileColor" content="#D9C24F" />
<meta name="msapplication-config" content="/browserconfig.xml" />

<!-- Preconnect -->
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
```

---

## PHASE 3 — KEYWORD RESEARCH

### Primary Keywords (High Priority)

| Keyword | Monthly Searches (est.) | Intent | Difficulty | Target Page |
|---|---|---|---|---|
| sports shop kottarakkara | 200–500 | Transactional | Low | Homepage |
| sports store kollam | 300–600 | Transactional | Low | Local landing |
| cricket bat kottarakkara | 100–300 | Transactional | Low | Cricket category |
| sports equipment kerala | 1K–3K | Transactional | Medium | Homepage |
| badminton racket kollam | 100–300 | Transactional | Low | Badminton category |
| football boots kerala | 300–700 | Transactional | Medium | Football category |
| sportswear kottarakkara | 100–200 | Transactional | Low | Sportswear category |

### Secondary Keywords (Medium Priority)

| Keyword | Intent | Difficulty | Target Page |
|---|---|---|---|
| best cricket bat under 1000 kerala | Transactional | Medium | Cricket category |
| badminton racket price kollam | Transactional | Low | Badminton category |
| football jersey kottarakkara | Transactional | Low | Sportswear category |
| fitness equipment home kerala | Transactional | Medium | Fitness category |
| swimming goggles kollam | Transactional | Low | Swimming category |
| chess set kottarakkara | Transactional | Very Low | Chess category |
| sports kit school kerala | Transactional | Low | Homepage / Cricket |

### Long-tail Keywords (High Conversion)

| Keyword | Intent | Page |
|---|---|---|
| buy cricket bat online kottarakkara | Transactional | Cricket category |
| whatsapp sports shop kollam | Transactional | Homepage |
| professional cricket bat kashmir willow kerala | Transactional | Cricket product |
| tournament badminton racket carbon kerala | Transactional | Badminton product |
| dri-fit jersey custom kottarakkara | Transactional | Sportswear |
| sports equipment delivery kerala | Transactional | Homepage |
| school cricket kit wholesale kollam | Transactional | Homepage |
| best football boots turf kerala | Transactional | Football category |
| resistance bands set price india | Transactional | Fitness category |

### Local Keywords (Geo-specific)

| Keyword | Priority |
|---|---|
| sports shop near me kottarakkara | High |
| sports equipment store pulamon junction | High |
| cricket shop kollam district | High |
| sports goods store anchal kerala | Medium |
| sports store punalur kerala | Medium |
| badminton shop karunagappally | Medium |
| sports mart premium kottarakkara | Brand |

### Informational Keywords (Blog targets)

| Keyword | Blog Title |
|---|---|
| how to choose cricket bat | How to Choose the Right Cricket Bat — A Kerala Player's Guide |
| best badminton racket for beginners | Best Badminton Rackets for Beginners in Kerala 2025 |
| cricket kit checklist india | Complete Cricket Kit Checklist for School Players in Kerala |
| how to improve fitness at home kerala | 10 Home Fitness Accessories You Need in Kerala |
| football training drills school | Football Drills and Equipment for School Teams in Kerala |

---

## PHASE 4 — LOCAL LANDING PAGE CONTENT

### 1. Sports Shop in Kottarakkara

**SEO Title:** Best Sports Shop in Kottarakkara | Sports Mart Premium — Est. 2014
**Meta Description:** Looking for a sports shop in Kottarakkara? Sports Mart Premium at Pulamon Junction stocks 500+ products — cricket, football, badminton, fitness and more. Visit us or order via WhatsApp: +91 89213 73326.
**H1:** Kottarakkara's No.1 Sports Shop Since 2014
**H2 Structure:**
- Why Sports Mart Premium is Kottarakkara's Most Trusted Sports Store
- Sports Equipment Available in Our Kottarakkara Store
- Cricket Equipment in Kottarakkara
- Football Equipment in Kottarakkara
- Badminton Equipment in Kottarakkara
- How to Order Sports Equipment in Kottarakkara
- Visit Us at Pulamon Junction, Kottarakkara
- What Our Customers Say About Sports Mart Premium
- Frequently Asked Questions — Sports Shop Kottarakkara

**Content outline (1500+ words):**

Sports Mart Premium has been Kottarakkara's most trusted sports equipment store since 2014. Located at Pulamon Junction, opposite the Private Bus Stand in the LIC Building, we serve athletes, school students, college teams, and sporting clubs across Kollam district.

Our store stocks over 500 products across 12 sports categories, making us the most comprehensive sports shop in Kottarakkara. Whether you're a cricket player looking for a professional bat, a football team in need of match jerseys, or a fitness enthusiast building a home gym, Sports Mart Premium has everything under one roof.

**Cricket Equipment in Kottarakkara:** [300 words covering bat types, pricing, kit components, school use]
**Football Equipment:** [250 words covering boots, balls, jerseys, team kits]
**Badminton:** [250 words covering racket selection, shuttles, beginner vs advanced]
**Fitness & Sportswear:** [200 words covering resistance training gear, dri-fit apparel]
**WhatsApp Ordering:** [150 words on the 3-step process]
**Location & Directions:** [150 words]
**Customer Reviews:** [200 words with quoted reviews]
**FAQ:** [300 words — 5 FAQs]

---

### 2. Sports Shop in Kollam

**SEO Title:** Sports Equipment Store in Kollam | Sports Mart Premium Kottarakkara — Delivery Available
**Meta Description:** Sports Mart Premium is Kollam's most trusted sports equipment and sportswear destination. Based in Kottarakkara, we serve all of Kollam district with 500+ products. WhatsApp: +91 89213 73326.
**H1:** Premium Sports Equipment and Sportswear for Kollam District
**H2 Structure:**
- Sports Mart Premium — Serving Kollam Since 2014
- Sports Equipment Delivered Across Kollam District
- Areas We Serve in Kollam District
- Complete Sports Range for Kollam Athletes
- Order Sports Equipment in Kollam via WhatsApp
- Visit Our Store 20 Minutes from Kollam City

**Note:** This page should mention all areas served: Kollam city, Punalur, Karunagappally, Anchal, Chavara, Ayoor, Paravur, Mynagappally.

---

### 3. Cricket Store in Kerala

**SEO Title:** Buy Cricket Equipment Online in Kerala | Sports Mart Premium Kottarakkara
**Meta Description:** Shop professional cricket bats, pads, helmets and full kits from Sports Mart Premium Kottarakkara. Delivery across Kerala. Kashmir willow bats from ₹999. WhatsApp: +91 89213 73326.
**H1:** Professional Cricket Equipment for Kerala Players
**Key H2s:**
- Cricket Bats for Every Level — From ₹999
- Complete Cricket Kit for School and Club Players
- Cricket Accessories — Balls, Gloves, Helmets, Pads
- WhatsApp Cricket Equipment Delivery Across Kerala
- Buying Guide: Choosing the Right Cricket Bat in Kerala

---

### 4. Football Equipment Store in Kerala

**SEO Title:** Football Equipment & Boots in Kerala | Sports Mart Premium Kottarakkara
**Meta Description:** Buy football boots, match balls, jerseys and full kits from Sports Mart Premium, Kottarakkara. Serving Kerala football teams since 2014. WhatsApp: +91 89213 73326.
**H1:** Premium Football Equipment for Kerala Players and Teams

---

### 5. Badminton Store in Kerala

**SEO Title:** Badminton Rackets & Equipment in Kerala | Sports Mart Premium Kottarakkara
**Meta Description:** Shop carbon and aluminium badminton rackets, shuttles and accessories at Sports Mart Premium. Kerala's best badminton equipment selection. WhatsApp: +91 89213 73326.
**H1:** Best Badminton Rackets and Equipment in Kerala

---

### 6. Sportswear Store in Kerala

**SEO Title:** Premium Sportswear & Sports Jerseys in Kerala | Sports Mart Premium
**Meta Description:** Dri-fit jerseys, tracksuits, shorts and sports apparel for all sports. Shop at Sports Mart Premium Kottarakkara or order across Kerala via WhatsApp. From ₹599.
**H1:** Premium Sportswear and Sports Jerseys for Every Athlete in Kerala

---

## PHASE 5 — ECOMMERCE SEO

### Product Page Title Formula
`{{Product Name}} | Buy {{Sport}} {{Category}} in Kottarakkara — Sports Mart Premium`

Example: `Professional Cricket Bat | Buy Cricket Equipment in Kottarakkara — Sports Mart Premium`

### Meta Description Formula
`Buy {{Product Name}} at Sports Mart Premium Kottarakkara. {{Feature 1}}, {{feature 2}}. In-store and delivery across Kerala. ₹{{price}}. WhatsApp: +91 89213 73326.`

### Internal Linking Structure for Product Pages
Each product page should link to:
1. The parent sport category page
2. 3–4 related products
3. Homepage
4. Local landing page (e.g. cricket equipment in Kottarakkara)
5. Blog post related to the sport

---

## PHASE 6 — BLOG CONTENT: 50 ARTICLE IDEAS

### Cricket (10 articles)
1. "How to Choose the Right Cricket Bat in Kerala" — KW: cricket bat buying guide kerala
2. "Kashmir Willow vs English Willow Cricket Bat — Which is Better for Kerala Players?" — KW: kashmir vs english willow
3. "Complete Cricket Kit Checklist for School Students in Kerala" — KW: cricket kit school india
4. "Best Cricket Bats Under ₹1000 in Kerala" — KW: cricket bat under 1000 india
5. "How to Care for Your Cricket Bat — 8 Tips for Kerala Climate"
6. "Cricket Pads Buying Guide for Beginners in Kerala"
7. "Top Cricket Accessories Every Player Needs in Kerala"
8. "How to Select Cricket Gloves — Guide for Kerala Players"
9. "Cricket Equipment for Monsoon Play in Kerala"
10. "Best Wicketkeeper Gloves in Kerala — Buying Guide 2025"

### Football (8 articles)
11. "How to Choose Football Boots for Turf and Grass in Kerala"
12. "Best Football Jerseys for Kerala School Teams"
13. "Football Equipment Checklist for School Tournaments in Kerala"
14. "What Size Football Should I Buy? Size Guide for Kerala Players"
15. "Football Fitness Training Accessories — A Kerala Coach's Guide"
16. "Best Football Boots Under ₹2000 in Kerala"
17. "How to Care for Your Football Boots"
18. "Goalkeeper Equipment Guide for Kerala Players"

### Badminton (8 articles)
19. "Best Badminton Rackets for Beginners in Kerala"
20. "Carbon vs Aluminium Badminton Racket — Which is Right for You?"
21. "Feather vs Nylon Shuttlecocks — What Kerala Players Should Know"
22. "How to Choose Badminton Shoes for Kerala Courts"
23. "Badminton Grip Tape — How and When to Replace It"
24. "Best Badminton Sets for Home Play in Kerala"
25. "Tournament Badminton Rackets — A Kerala Buyer's Guide"
26. "Badminton Racket Weight Guide — Light vs Heavy for Kerala Climate"

### Fitness (8 articles)
27. "Best Home Gym Equipment Under ₹5000 in Kerala"
28. "How to Build a Home Gym in Kerala — Starter Guide"
29. "Resistance Bands Workout for Kerala Athletes"
30. "Best Running Shoes for Kerala Roads and Climate"
31. "Yoga Mat Buying Guide for Kerala"
32. "Skipping Rope Benefits — Why Every Kerala Athlete Should Skip"
33. "Best Foam Rollers for Post-Match Recovery in Kerala"
34. "Fitness Accessories for Student Athletes in Kerala"

### Sportswear (5 articles)
35. "How to Choose Dri-Fit Sportswear for Kerala's Climate"
36. "Custom Sports Jerseys for Kerala School Teams"
37. "Best Tracksuits for Kerala Winter Sports"
38. "Sports Socks — Why They Matter for Kerala Athletes"
39. "School Sports Day Apparel Checklist for Kerala Students"

### Kerala Sports & Local (7 articles)
40. "Best Sports Shops in Kottarakkara — Complete Guide"
41. "Sports Equipment Shops in Kollam District — What You Need to Know"
42. "Where to Buy Cricket Equipment in Kollam"
43. "Top Sports Academies in Kollam and the Equipment They Use"
44. "School Sports in Kerala — Equipment Guide for Teachers"
45. "Supporting Kerala Sports — How Local Shops Are Empowering Athletes"
46. "Kottarakkara Sports Community — Clubs, Teams and Where to Buy Gear"

### Chess & Swimming (4 articles)
47. "Best Chess Sets in Kerala — A Buyer's Guide"
48. "How to Choose a Chess Set for School Competitions"
49. "Swimming Goggles Buying Guide for Kerala Swimmers"
50. "Essential Swimming Accessories for Kerala Pool and Open Water"

---

## PHASE 7 — INTERNAL LINKING STRATEGY

### Homepage Links To:
- /products.html (via "View Full Products" and "Explore Full Collection" CTAs)
- /cricket-equipment-kottarakkara.html
- /football-equipment-kerala.html
- /badminton-equipment-kollam.html
- /sportswear-kerala.html
- /sports-shop-kottarakkara.html (via footer or "About" section)

### Category Pages Link To:
- Homepage
- 4–6 individual product pages
- 2 related category pages
- 1 relevant blog post
- Local landing page

### Product Pages Link To:
- Parent category page
- 3 related products
- Homepage
- WhatsApp enquiry (always)
- Blog post for that sport

### Blog Posts Link To:
- Product page for recommended products
- Category page for the sport
- Homepage
- Other relevant blog posts (3–4 internal links per post)

---

## PHASE 8 — CORE WEB VITALS OPTIMIZATION

### Current Estimated Baseline (based on code review)
- LCP: ~3.2s (large hero background images loaded via CSS, render blocking fonts)
- CLS: ~0.08 (mostly stable, some hero animation risk)
- INP: ~180ms (acceptable, JS-heavy but not extreme)
- FCP: ~2.4s (Google Fonts blocking, inline CSS is good)

### Target After Optimization
- LCP: < 2.5s
- CLS: < 0.1
- INP: < 200ms
- FCP: < 1.8s

### Image Optimization Plan

**Current Issue:** Hero sports slides use Unsplash URLs loaded as CSS background images. These:
1. Cannot be preloaded with `<link rel="preload">`
2. Are not responsive
3. Are not served as WebP

**Fix:**
```html
<!-- Replace CSS background with img tag for above-fold images: -->
<img
  src="/images/cricket-hero.webp"
  srcset="/images/cricket-hero-400.webp 400w,
          /images/cricket-hero-800.webp 800w,
          /images/cricket-hero-1600.webp 1600w"
  sizes="(max-width: 768px) 92vw, 78vw"
  alt="Professional cricket equipment at Sports Mart Premium Kottarakkara"
  width="1600"
  height="560"
  fetchpriority="high"
  loading="eager"
/>

<!-- Preload in <head>: -->
<link rel="preload" as="image" href="/images/cricket-hero.webp"
      imagesrcset="/images/cricket-hero-400.webp 400w,
                   /images/cricket-hero-800.webp 800w,
                   /images/cricket-hero-1600.webp 1600w"
      imagesizes="78vw" />
```

**WebP Conversion Plan:**
- Convert all product images to WebP (80% quality)
- Keep JPEG fallback for older browsers via `<picture>` element
- Target: under 80KB per product card image
- Hero images: under 200KB at 1600px width

**Lazy Loading:**
```html
<!-- All below-fold images: -->
<img src="product.webp" loading="lazy" decoding="async" alt="..." width="400" height="400" />
```

### CSS Optimization

**Current state:** ~2000 lines of inline CSS in `<style>` — good for no render-blocking requests, but very large.

**Recommendations:**
1. Extract critical CSS (above-fold only): nav, hero, body background — ~400 lines
2. Defer non-critical CSS (product cards, drawer, footer) via:
   ```html
   <link rel="stylesheet" href="/css/deferred.css" media="print" onload="this.media='all'" />
   ```
3. Remove unused CSS: `.product-placeholder` likely unused if products are JS-rendered

### JavaScript Optimization

**Current state:** Single `<script>` block at bottom — good. Main concerns:
1. Carousel `requestAnimationFrame` loop runs continuously even when not visible — add visibility check
2. Cursor tracking is always active — use `passive: true` (already done, good)
3. Cart data loaded synchronously — fine

**Add `defer` to any external scripts:**
```html
<script defer src="/js/app.js"></script>
```

### Font Optimization

**Current:** Google Fonts loaded via `<link>` with `display=swap` — good. But adds DNS lookup time.

**Better:**
```html
<!-- Add preconnect before the Google Fonts link: -->
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<!-- Keep existing link tags -->
```
**Best:** Self-host fonts using `@font-face` with woff2 files for zero external DNS dependency.

### Performance Checklist
- [ ] Add `width` and `height` attributes to all `<img>` tags (prevents CLS)
- [ ] Preload hero image
- [ ] Convert all images to WebP
- [ ] Add `loading="lazy"` to all below-fold images
- [ ] Add `decoding="async"` to all images
- [ ] Add `<link rel="preload">` for primary font (Cormorant Garamond or Barlow Condensed)
- [ ] Add canonical tags to all pages
- [ ] Add schema markup to all pages
- [ ] Minify HTML (remove whitespace in production)
- [ ] Enable Gzip/Brotli compression on server
- [ ] Add Cache-Control headers for static assets (images: 1 year, CSS/JS: 1 month)

---

## PHASE 9 — 90-DAY SEO ROADMAP

### Days 1–30 (Quick Wins — Foundation)

**Week 1:**
- [ ] Add complete `<head>` SEO meta tags to homepage (see template above)
- [ ] Add LocalBusiness JSON-LD schema to homepage
- [ ] Add FAQ JSON-LD schema to homepage
- [ ] Deploy robots.txt and sitemap.xml
- [ ] Deploy llms.txt and llms-full.txt
- [ ] Submit sitemap to Google Search Console
- [ ] Claim/optimize Google Business Profile (GBP)

**Week 2:**
- [ ] Add product schema to products.html
- [ ] Add canonical tags to all pages
- [ ] Optimize homepage title and meta description
- [ ] Add alt text to all images
- [ ] Fix image `width` and `height` attributes to prevent CLS
- [ ] Add manifest.json and PWA meta tags

**Week 3:**
- [ ] Create "Sports Shop in Kottarakkara" local landing page
- [ ] Create cricket category page with 1500+ word content
- [ ] Create football category page
- [ ] Publish first 3 blog articles (cricket focus)
- [ ] Convert hero images to WebP and add preload

**Week 4:**
- [ ] Create badminton and fitness category pages
- [ ] Publish 3 more blog articles (football and badminton)
- [ ] Set up Google Analytics 4
- [ ] Configure Google Search Console
- [ ] Set up Search Console performance monitoring

**Expected impact in 30 days:**
- Google Business Profile impressions +40%
- Indexed pages: 5 → 15+
- Brand queries begin appearing in GSC

---

### Days 31–60 (Growth Phase)

**Week 5–6:**
- [ ] Create "Sports Shop in Kollam" local landing page
- [ ] Create sportswear and basketball category pages
- [ ] Publish 6 blog articles (mix of cricket, fitness, local)
- [ ] Build 5 local citations (JustDial, Sulekha, IndiaMART, Yelp India, Yellow Pages)
- [ ] Request Google reviews from customers (WhatsApp follow-up message)

**Week 7–8:**
- [ ] Create individual product pages for top 5 products (server-rendered HTML, not JS-only)
- [ ] Add breadcrumb navigation to all pages
- [ ] Implement internal linking strategy across all pages
- [ ] Publish 6 more blog articles
- [ ] Self-host Google Fonts for FCP improvement

**Expected impact in 60 days:**
- Rankings for "sports shop kottarakkara" — position 1–3
- Rankings for "cricket bat kottarakkara" — position 1–5
- Organic impressions: +200%
- WhatsApp enquiries from organic: +30%

---

### Days 61–90 (Authority Phase)

**Week 9–10:**
- [ ] Outreach to 3–5 Kerala sports blogs for backlinks
- [ ] Partner with local schools for link opportunities (supply agreements)
- [ ] Create "Kerala Cricket Guide" pillar content page (3000+ words)
- [ ] Publish 8 more blog articles
- [ ] Add product reviews/ratings system to pages

**Week 11–12:**
- [ ] Create swimming, chess category pages
- [ ] Build product schema on all 15 product pages
- [ ] Optimize Core Web Vitals — target all green in PageSpeed Insights
- [ ] Publish 6 blog articles
- [ ] Analyse GSC performance, double down on ranking keywords

**Expected impact at 90 days:**
- Rankings for 20+ target keywords
- Top 3 for: "sports shop kottarakkara", "cricket bat kottarakkara", "badminton racket kollam"
- Organic traffic: 500–1000 monthly sessions
- WhatsApp enquiries from organic: +60%
- Google Business Profile calls: +50%

---

## PHASE 10 — OG IMAGE & FAVICON SPECIFICATION

### OG Image (1200×630px)
- Background: Gold gradient (#D9C24F → #F6F0D6)
- Left side: "Sports Mart Premium" in Cormorant Garamond Bold, large
- Sub: "Kottarakkara, Kerala | Est. 2014"
- Right side: Sport emoji collage (🏏⚽🏸🏋♟️)
- Bottom: "+91 89213 73326 | sportsmartpremium.in"
- Dark accent bar at bottom: "#111111"
- File: og-home.jpg (under 300KB)
- Tool: Canva, Figma, or generate with sharp/node-canvas

### Favicon Package Required
```
/favicon.ico                    (32×32, ICO format)
/icons/favicon-16x16.png
/icons/favicon-32x32.png
/icons/apple-touch-icon.png     (180×180)
/icons/icon-192.png             (192×192, for PWA)
/icons/icon-512.png             (512×512, for PWA)
/icons/safari-pinned-tab.svg    (SVG monochrome)
/icons/mstile-150x150.png       (Windows tile)
```

Design direction: Bold "S" or "SM" monogram on gold (#D9C24F) background in deep dark ink (#111111). Simple, legible at 16px.

---

*End of Sports Mart Premium SEO Strategy Document*
*Total estimated organic traffic improvement at 90 days: 500–1000 monthly sessions*
*Expected rank #1 positions: "sports shop kottarakkara", "cricket bat kottarakkara", "sports store kollam"*
