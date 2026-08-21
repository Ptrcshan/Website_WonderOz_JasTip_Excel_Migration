WONDEROZ JASTIP — IMAGE ASSET GUIDE
=====================================
Updated after the Hero / Testimonials / Popup revision (this delivery).

1) HERO BANNER (Home page background photo)
   File   : hero-banner.png (2400x1200, 2:1 ratio)
   Used in: Home page hero, as a full-bleed CSS background (background-size: cover)
   To update: replace with a new photo at roughly the same 2400x1200 (2:1) ratio.
   Keep the main subject centered/right — the left ~50% should stay reasonably calm,
   since the headline text sits there. A white readability wash is added
   automatically via CSS, but a very busy left edge will still be harder to read.

2) CUSTOMER TESTIMONIALS (4 individual images, cropped from your original strip)
   Files  : testimonial-01.jpg, testimonial-02.jpg, testimonial-03.jpg, testimonial-04.jpg
   Used in: Home page "What Our Customers Say" — shown as a 2x2 grid, click to enlarge
   These were cropped from your original 10974x2742 "design-testimoni.png" strip
   (one wide image containing all 4 panels) and resized to 1300px each so the chat
   text inside stays sharp and readable. The original strip file is no longer
   bundled here since the site doesn't use it anymore (you already have the
   master file on your own computer).
   To add a 5th+ testimonial: crop a new square-ish image, save as testimonial-05.jpg,
   and copy one more <img class="testimonial-quad-img"> line in index.html.

3) PROMO POPUP IMAGES (4:5 aspect ratio, shown full — never cropped/stretched)
   Files  : promo-88.jpg (8.8 Shopping Festival), promo-17-agustus.jpg (Independence Day)
   Used in: Home page popup (index.html, #mascotPopup), 2-slide slider with arrows/dots
   Originally supplied as PNG, converted here to JPG (quality 90) to cut load
   time by ~85% with no visible quality difference. Swap either file any time to
   update the active promos — keep the same 4:5 ratio (e.g. 2160x2700) so nothing
   gets cropped or stretched; the popup uses object-fit: contain.

4) MASCOT (small icon use) — still a placeholder circle, not yet replaced.
   File: mascot-wonderoz.png

5) PACKING GUIDELINE ILLUSTRATIONS
   Currently simple inline SVG icons (drawn directly in how-it-works.html — no
   separate files) for each of the 7 packing guideline rows. To use real photos
   instead, add files such as assets/images/packing-01.jpg ... packing-07.jpg,
   then replace the relevant <div class="packing-illustration"><svg>...</svg></div>
   block in how-it-works.html with:
     <div class="packing-illustration"><img src="assets/images/packing-01.jpg" alt="..."></div>

6) FAVICON (browser tab icon)
   The site currently uses /logo.png as the favicon.
   If you want the koala mascot as the favicon instead, add a new file:
   File to add: favicon-mascot.png (square, 512x512px recommended)
   Then open every .html file and change this line in <head>:
     <link rel="icon" href="logo.png">
   to:
     <link rel="icon" href="assets/images/favicon-mascot.png">

STILL NEEDED FROM YOU:
   - Replace mascot-wonderoz.png with the real mascot icon file (see #4)
   - Real packing guideline example photos (optional, currently using SVG
     illustrations) — see #5
   - Email/contact address for News community submissions
   - Moderation/review process for News submissions before publishing

ALREADY DONE IN THIS REVISION:
   - Hero background is now the full-bleed hero-banner.png photo, content
     left-aligned, route animation width-matched to the badge pill, and the
     headline text now swaps "Australia & Indonesia" / "Indonesia & Australia"
     in sync with the plane's flight direction
   - Testimonials switched from one blurry wide strip to 4 sharp individual
     images in a 2x2 grid (click to enlarge)
   - Promo popup fixed to always stay fully centered and within the viewport
     (no more top/bottom clipping), images shown uncropped/unstretched
   - The dot-line-plane-dot route animation now also appears at the top of
     Our Service, How It Works, Shipping Rates, News, and Ship Now
   - Sydney drop points: Panda Asia Market Kogarah & Sydney, each with a
     direct Google Maps link (shipping-rates.html)
   - Floating sticky WhatsApp button on every page - wa.me/6287722284847
     with pre-filled message "Hi WonderOz JasTip."
   - Personal Shopper / Logistics & Cargo shown as 2 side-by-side columns
     (our-service.html)
   - "How It Works" is its own page (how-it-works.html)
   - Packing Guidelines shown as a vertical list with an illustration per item
