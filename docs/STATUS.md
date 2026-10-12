# מצב — ספריית PDF+OCR (עודכן 2026-10-12)

## נעשה (נדחף ל-main)
* 4.0.1: חזרת "פתיחת קובץ" (fs.pickUserFile): מסך פתיחה, דף ראשי, הגדרות, Ctrl+O.
* מזהה חדש com.chadbedera.pdfocrlibrary — תוסף נפרד מ„צופה PDF+OCR“ 3.2.0 (com.chadbedera.pdfviewer), שנשאר בחנות כי חסרות כאן יכולות: גרירה והדבקה, תמונות/TIFF, DOCX, EPUB, הדפסה.
* css הועבר לטוקנים — ולידציית העיצוב עוברת (0 הערות).
* workflow: נוסף reports-consent: 'true'.

## פרסום (עודכן)
* נוסף screenshots/main.png והקלט screenshots ב-publish.yml. תוסף חדש ממתין לאישור מנהל החנות אחרי הפרסום הראשון.

## היה חסר (נפתר ב-01:00)
* הפרסום הראשון נכשל: נדרש לפחות צילום מסך דרך הקלט screenshots של Otzaria/otzaria-plugin-validator@v1 ב-.github/workflows/publish.yml. יש לבדוק בתיעוד הפעולה את פורמט הקלט, להוסיף צילום (למשל מסך "טעינת תיקייה") ל-docs/screenshots/, לעדכן את ה-workflow ולדחוף ל-main.
* אחרי הצלחה ייווצר GitHub Release v4.0.1 עם קובץ ה-.otzplugin.

## מאגר נפרד (2026-10-12)
* ספריית PDF+OCR (com.chadbedera.pdfocrlibrary) עברה למאגר משלה: e0548433917-gif/pdf-ocr-library (ענף main), כדי שדף הגרסאות שלה יהיה נפרד מ„צופה PDF+OCR“.
* הצופה (com.chadbedera.pdfviewer) ממשיך במאגר e0548433917-gif/pdf-viewer, ענף viewer-3.3.3.
* הפרסום לחנות דורש את הסודות OTZARIA_USER ו-OTZARIA_PASSWORD במאגר החדש.
