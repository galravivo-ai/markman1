# מרקמן טומשין ושות' — אתר

אתר סטטי. אפשר להעלות כמו שהוא ל-GitHub Pages.

## עמודים
- index.html — עמוד הבית
- will.html — צוואה
- power-of-attorney.html — ייפוי כוח מתמשך
- bundle.html — צוואה + ייפוי כוח (מומלץ)
- questionnaire.html — שאלון התאמה
- upsell.html — מסך סיום השאלון
- contact.html — צור קשר

## העלאה ל-GitHub Pages
1. מעלים את כל תוכן התיקייה (כולל support.js, image-slot.js, .nojekyll ותיקיית assets) לשורש הריפו.
2. Settings → Pages → Deploy from branch → main / root.

## תמונות
המקומות לתמונות (image-slot) מציגים מסגרת ריקה. כדי להכניס תמונה קבועה, מחליפים את התג
`<image-slot id="...">` בתג `<img src="assets/שם-הקובץ.jpg" style="width:100%;height:100%;object-fit:cover">`.
