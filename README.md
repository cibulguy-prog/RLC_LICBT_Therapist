# רוית לביא ציבולסקי — אתר הקליניקה

אתר סטטי (HTML בלבד, בלי תהליך build). כל קובץ עומד בפני עצמו ואפשר לפתוח אותו ישירות בדפדפן.

## מבנה הקבצים
| קובץ | עמוד |
|---|---|
| index.html | בית |
| about.html | נעים להכיר |
| services.html | תחומי טיפול |
| blog.html | מאמרים |
| article-1.html | מאמר: איך נראה הפנאי שלי |
| article-2.html | מאמר: חרדות תחושה ומחשבה |
| testimonials.html | מילים מהלב |
| contact.html | יצירת קשר |
| images/ | תמונות האתר |
| CNAME | הדומיין המותאם (לעריכה לפי הדומיין שנרכש) |

## תמונות
יש להעלות תמונת פרופיל בשם `images/ravit.jpg`. שאר הדפים לא דורשים תמונות.

## העלאה ל-GitHub Pages
1. להעלות את תוכן התיקייה הזו לשורש הריפו (branch `main`).
2. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `/ (root)`.
3. האתר יעלה בכתובת `https://<username>.github.io/<repo>/`.

## חיבור דומיין מותאם
1. לרכוש דומיין (Namecheap / GoDaddy / Google Domains וכו').
2. לערוך את הקובץ `CNAME` ולהכניס בו את הדומיין (למשל `ravit-licbt.co.il`) בשורה אחת.
3. אצל ספק הדומיין להגדיר:
   - רשומות `A` לשורש הדומיין: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - רשומת `CNAME` ל-`www`: `<username>.github.io`
4. ב-GitHub: Settings → Pages → Custom domain → להזין את הדומיין ולסמן `Enforce HTTPS`.
