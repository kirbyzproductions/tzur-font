<div dir="rtl">

# צור-פונט

סטודיו חינמי ליצירת פונטים עבריים, שרץ כולו בדפדפן. בוחרים סגנון, מכוונים, מזיזים אותיות ומורידים פונט אמיתי שאפשר להתקין.

**[לפתוח את צור-פונט ←](https://kirbyzproductions.github.io/tzur-font/)**

## מה יש בפנים

- **25 סגנונות מוכנים:** דיו, כספית, לבה, מסטיק, גרפיטי, ארקייד, זהב רטוב, קומיקס, ניאון, סטנסיל, שרטוט ועוד.
- **4 מנועי צורה:** נוזלי, מונו-ליין, פיקסלים וסטנסיל. לכל אחד סליידרים משלו.
- **11 אפקטים שנערמים אחד על השני:** תלת-ממד, צל ארוך, מדבקה, קו מתאר, גרדיאנט, ברק, זוהר, קווקו, סקיצה, ניאון ולכלוך.
- **עורך אותיות:** גוררים את נקודות השלד של כל אות, משנים עובי, מוסיפים קווים.
- **הזזת אותיות ביד** בתצוגה, בגרירה או בחצים.
- **סט אותיות:** עברית כולל אותיות סופיות, ספרות, אותיות לטיניות גדולות, ניקוד בסיסי ופיסוק.
- **ייצוא:** פונט OTF, תמונת PNG (גם עם רקע שקוף), SVG, לוח אותיות וקובץ פרויקט.
- שומרים סגנונות בשם, ויש כפתור "תפתיע אותי".

## פרטיות

אין שרת ואין הרשמה. העבודה נשמרת רק בדפדפן שלך. כדי להעביר אותה למכשיר אחר משתמשים ב"שמירת פרויקט" וב"טעינת פרויקט".

## הפונטים שלך שייכים לך

פונטים ותמונות שיוצרים בצור-פונט שייכים למי שיצר אותם. מותר להשתמש בהם לכל מטרה, גם מסחרית, בלי חובת קרדיט.

## הרצה מקומית

זה קובץ HTML אחד. מורידים את `index.html` ופותחים אותו בדפדפן, או מריצים שרת קטן:

```bash
python3 -m http.server
```

הספריות [opentype.js](https://github.com/opentypejs/opentype.js) ו-[JSZip](https://github.com/Stuk/jszip) נטענות מ-CDN.

## איך זה עובד

כל אות מוגדרת כשלד של קווים, ולכל נקודה בקו יש עובי. המנוע מחשב סביב השלד שדה מרחק (SDF), מחליק ומתיך את החיבורים בין הקווים, ומחלץ ממנו קווי מתאר בשיטת marching squares. אותם קווי מתאר משמשים גם לתצוגה וגם לקובץ ה-OTF.

## תרומה

מוזמנים לפתוח issue או pull request: אותיות שצריך לשפר, סגנונות חדשים, באגים.

## השראה

הרעיון נולד בעקבות Liquid.Font של Mark Do. הקוד כאן נכתב מאפס.

## רישיון

הקוד ברישיון [MIT](LICENSE). רשימת הרכיבים החיצוניים והרישיונות שלהם נמצאת ב-[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

</div>

---

## Tzur-Font (English)

A free, in-browser studio for designing Hebrew fonts. Pick one of 25 styles, tune shape and effects, edit letter skeletons, drag letters by hand, and export an installable OTF font, PNG or SVG. No server and no sign-up: your work stays in your browser.

Fonts and images you make with the tool are yours to use for any purpose, including commercial work. The source code is MIT licensed.

**[Open Tzur-Font →](https://kirbyzproductions.github.io/tzur-font/)**
