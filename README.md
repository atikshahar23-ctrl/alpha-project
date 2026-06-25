# Heavy Guard

דף נחיתה בינלאומי למצלמות, GPS ומערכות אבטחה לציי משאיות וציוד כבד.
Landing page for fleet & heavy-equipment cameras, GPS and security systems.

הלקוח בונה תצורת מצלמות למשאית שלו בסימולטור התלת-ממד ושולח אותה ישירות בוואטסאפ להצעת מחיר.

## מבנה / Structure

- `index.html` — האתר (single-page, RTL עברית + מתג אנגלית)
- `assets/` — לוגואים (PNG + WebP), אייקונים, ותמונת שיתוף (OG)
- `site.webmanifest` — מניפסט PWA

## טכנולוגיה

- HTML/CSS/JS ללא תלות בבנייה (static)
- Babylon.js לסימולטור התלת-ממד (נטען lazy בעת גלילה לסימולטור)
- WhatsApp deep-links להמרת לידים

## הגדרות לעדכון לפני עלייה לאוויר

- **דומיין**: החלף את `https://heavyguard.co.il/` בקובץ `index.html` (תגי canonical / OG / JSON-LD) ובמניפסט בדומיין האמיתי — נדרש כדי שתצוגת השיתוף בוואטסאפ/פייסבוק תעבוד.
- **וואטסאפ**: המספר מוגדר ל-`972547719070` (קבוע `WA` ב-`index.html`).
