# תכלת וארגמן — אתר חנות

אתר חנות מקוונת לכיפות ואביזרים יהודיים בעבודת יד.

## פיתוח ב-Astro + פרסום ב-Vercel

### התקנה ופיתוח מקומי
```bash
npm install
npm run dev
```

### פרסום ב-Vercel (3 שלבים):
1. העלה את התיקייה ל-GitHub (חדש repo)
2. כנסי ל-[vercel.com](https://vercel.com) → New Project
3. חבר ל-GitHub repo → Deploy (Vercel מזהה Astro אוטומטית)

### מבנה הפרויקט
```
src/
  pages/
    index.astro      ← דף הבית
    simulator.astro  ← מדמה הכיפה
  layouts/
    Layout.astro     ← תבנית בסיס
  components/
    Header.astro
    Footer.astro
public/
  logo.svg           ← הלוגו שלך
```
