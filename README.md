# Mahmoud Elshahatt — Programming Teaching Landing Page

A modern, single-file, bilingual (Arabic RTL / English LTR) landing page for selling programming
teaching services in Egypt: kids (Scratch + Python), adults (Kotlin + Android), and secondary-school tutoring.

صفحة هبوط حديثة من ملف واحد، ثنائية اللغة (عربي / إنجليزي) لبيع خدمات تعليم البرمجة في مصر.

---

## Files / الملفات

- `index.html` — the website layout, styles and scripts.
- `content.js` — **all the site content** (courses, prices, reviews, gallery, FAQ, texts, phone numbers).
- `admin.html` — the dashboard for editing `content.js` from the browser.
- `instructor.png` — your profile photo. If missing, the page falls back to your initials.
- `gallery/` — student work screenshots.

Fonts, icons, the Vodafone & InstaPay logos and the favicon are built into `index.html`.
Only Google Fonts is loaded from the internet.

---

## Dashboard / لوحة التحكم

Open `https://mahmoud-elshahatt.github.io/code-with-mahmoud/admin.html` (works on a phone too).

1. Create a GitHub **fine-grained token** once: GitHub → Settings → Developer settings →
   Fine-grained tokens → *Only select repositories* → this repo → *Contents: Read and write*.
2. Paste the token into the dashboard and press **Connect**. It is stored only in that browser.
3. Edit courses, prices, reviews, gallery, FAQ, texts or contact numbers.
4. **Preview** shows your unsaved changes on the real page. **Save & publish** commits `content.js`
   to GitHub; the live site updates in a minute or two (visitors may see the old version for up to 10 minutes).

Every field has an Arabic and an English box; if English is left empty the Arabic text is shown.

---

## Features / المميزات

- **Bilingual toggle** (🌐): switches the whole page between Arabic (RTL) and English (LTR).
- **Dark / Light theme** (🌙 / ☀️): remembers your choice and respects your system setting.
- **Course/pricing cards** with WhatsApp "Enroll Now" buttons that open a pre-filled message
  naming the chosen course.
- **Student projects** and a work gallery with a lightbox.
- **Animated** hero, scroll-reveal sections, animated counters, hover effects.
- **Payment section** with Vodafone Cash & InstaPay logos and one-tap **copy** buttons for the number.
- Mobile-first and fully responsive.

---

## Contact / التواصل

- WhatsApp: +20 109 372 9626 — https://wa.me/201093729626
- Email: mahmoudelshahatt1@gmail.com
- Location: Cairo, Egypt

**Payment:** Vodafone Cash & InstaPay — `01093729626`

---

© 2026 Mahmoud Elshahatt — Learn Programming. All rights reserved.
