# Handoff — Smile Design Dental Clinics (عيادة تصميم البسمة لطب الأسنان)
Niche: dentist
Primary language: Arabic
Old site: https://smiledesign.sa/ (live, but slow/no-HTTPS flagged in scan — dated Elementor/WordPress build, stats default to 0 and rely on JS, 2 of 9 doctors show a generic stock silhouette instead of a real photo, before/after gallery photos carry baked-in contact-info text strips, no trust signal above the fold despite a strong real rating)
New demo (local): demos-smiledesign/index.html
GitHub repo: https://github.com/Aymean/smiledesign-demo (public)
Intended live URL: https://smiledesign.zaylogear.com/
Real WhatsApp: +966555202438
Real phone: 011 273 4448 / 011 462 4272 (+966112734448)
Real email: Info@smiledesign.sa
Socials: Instagram https://www.instagram.com/smiledesign_riyadh/ (5,466 followers) | TikTok https://www.tiktok.com/@smiledesign_riyadh | Snapchat https://www.snapchat.com/add/riyadhsmile | X https://x.com/riyadhsmile | Facebook https://www.facebook.com/Riyadhsmiles/
Key real facts used:
- 4.7★ rating with 200+ Google reviews — cross-verified across 3 independent sources (outreach CSV: 4.7/206, zavis.ai Google-sourced listing: 4.7/193, findglocal.com: 4.4/227) before trusting it, per the CSV-reliability caution in CLAUDE.md
- Clinic since 2009, real stats from their own site: 6,000+ happy clients, 15+ years of expertise, 75+ dental services
- 9 real named doctors/consultants with real specialties (Dr. Ihsan Al Qeshtaini, Dr. Hanadi Alyami, Dr. Bashar Al Khouja, Dr. Ammar Abu Al-Shaar, Dr. Marwa Al Kaed, Najoud Abdullah Abu Humaid, Dr. Noha Al Sharidah, Dr. Issam Al Baradie, Essam Jomor) — 7 have real photos sourced from the clinic's own site, 2 (Najoud, Essam) had no real photo on the source site either (generic stock silhouette used there), so they get a clean initials avatar instead of a fake photo
- Real address: Musa Ibn Nusair St, As Sulimaniyah, Riyadh 12241 (2nd floor, opposite Al Jazeera Hypermarket)
- Real tech: Diagnodent laser cavity detection, Digital X-Ray + Digital Smile Design (DSD), laughing-gas sedation
- 8 real before/after patient case photo pairs (cropped from their own Instagram-template composites; contact-info text strip and mislabeled "Befor" typo removed, small corner clinic-logo watermark kept)
- 6 real reviews used on each language side: genuinely different real review sets pulled directly from the clinic's own AR homepage and EN homepage (not translated by me), each attributed to the real doctor named in the source review

New sections added vs old site:
- Trust badge (4.7★ / 200+ reviews) placed directly in the hero, above the fold — invisible on the old site
- Animated stat counters now default to their real final value in raw HTML (old site defaults to "0" and waits on JS)
- Individually named, staggered editorial doctor list with real specialty titles (old site's team section works the same way but this rebuild fixes the 2 missing photos with a clean initials treatment instead of a stock-silhouette placeholder)
- Before/after gallery cleaned up: consistent crop, no baked-in phone-number/social-handle text, no typo, tap-to-reveal interaction
- Dedicated FAQ section (booking, kids, sedation, Invisalign, exact location) with FAQPage schema
- Real WhatsApp-prefilled booking form (name, phone, service, preferred day → opens wa.me with the message ready to send) instead of a generic contact form
- Persistent mobile bottom CTA bar (Call / WhatsApp / Book) + desktop floating WhatsApp bubble
- Self-hosted IBM Plex Sans Arabic / IBM Plex Sans, bilingual AR-RTL default with full EN toggle (old site's language split is a separate URL path, not a same-page toggle)
