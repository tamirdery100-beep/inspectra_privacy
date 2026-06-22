# Inspectra Legal Site

עמוד אינטרנט סטטי המכיל את מדיניות הפרטיות ותנאי השימוש של אפליקציית Inspectra.

## הקבצים

- `index.html` — העמוד עצמו, מכיל את כל התוכן והעיצוב inline.
- `README.md` — קובץ הוראות זה.

## העלאה ל-GitHub

1. צור repository חדש ב-GitHub (לדוגמה: `inspectra-legal`).
2. בטרמינל בתיקייה הזו:

   ```bash
   git init
   git add .
   git commit -m "Initial commit: Inspectra legal documents"
   git branch -M main
   git remote add origin https://github.com/USERNAME/inspectra-legal.git
   git push -u origin main
   ```

   החלף `USERNAME` בשם המשתמש שלך ב-GitHub.

## פריסה ב-Vercel

1. הירשם / התחבר ל-[vercel.com](https://vercel.com) עם חשבון GitHub שלך.
2. לחץ על **"Add New... → Project"**.
3. בחר את ה-repository `inspectra-legal`.
4. אל תשנה כלום בהגדרות — Vercel יזהה אוטומטית שזה אתר סטטי.
5. לחץ **Deploy**.

תוך כדקה תקבל URL כמו:
`https://inspectra-legal.vercel.app`

זה הקישור שתשים ב-App Store / Google Play כ-Privacy Policy URL.

## עדכון תוכן בעתיד

כשתרצה לעדכן את התוכן:

1. ערוך את `index.html`.
2. עדכן את התאריך והגרסה למעלה.
3. ב-Git:

   ```bash
   git add .
   git commit -m "Update legal docs to version X.Y"
   git push
   ```

4. Vercel יעדכן את האתר אוטומטית תוך כמה שניות.
