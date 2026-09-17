# מרקמן טומשין ושות' — אתר וויירפריים

אתר סטטי, ללא תלויות ובלי שלב בנייה. אפשר להעלות כמו שהוא ל-GitHub Pages.

## קבצים

| קובץ | מסך |
| --- | --- |
| `index.html` | עמוד ראשי |
| `power-of-attorney.html` | ייפוי כוח מתמשך |
| `will.html` | צוואה |
| `bundle.html` | צוואה + ייפוי כוח (חבילה, מומלץ) |
| `questionnaire.html` | שאלון (7 שלבים, JS) |
| `upsell.html` | מסך אפסייל |
| `contact.html` | צור קשר |
| `assets/logo.jpg` | לוגו |

## העלאה ל-GitHub Pages

```bash
git init
git add .
git commit -m "wireframe site"
git branch -M main
git remote add origin https://github.com/USER/REPO.git
git push -u origin main
```

אחר כך ב-GitHub: Settings → Pages → Source: `main` / root.

## הערות

- טופס "צור קשר" והשאלון מציגים אישור בצד הלקוח בלבד — אין שרת. צריך לחבר אותם למערכת שליחה (Formspree, Netlify Forms, API משלכם).
- הקופסאות האפורות הן מקום לתמונות. הפונט הוא Heebo מ-Google Fonts.
- הכתובת, הטלפון והמייל ב-`contact.html` הם דוגמה — יש להחליף בפרטים האמיתיים.
