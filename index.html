<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>מעקב קטיף – תיעוד מערכת וזרימת תהליך</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        :root {
            --primary: #002366; /* Royal Blue */
            --accent:  #D4AF37; /* Gold */
            --light:   #F9F9F9;
            --dark:    #222;
            --muted:   #6b7280;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            background: var(--light);
            color: var(--dark);
            line-height: 1.7;
        }

        header {
            background: var(--primary);
            color: #fff;
            padding: 24px 16px;
            border-bottom: 4px solid var(--accent);
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 1.9rem;
        }

        header p {
            margin: 6px 0 0;
            font-size: 1rem;
            opacity: 0.9;
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 24px 16px 40px;
        }

        /* Navigation */
        .nav {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 24px;
        }

        .nav a {
            text-decoration: none;
            font-size: 0.9rem;
            padding: 8px 14px;
            border-radius: 999px;
            border: 1px solid rgba(0,0,0,0.08);
            background: #fff;
            color: var(--dark);
            transition: background 0.15s, transform 0.15s, box-shadow 0.15s;
        }

        .nav a:hover {
            background: #f3f4ff;
            transform: translateY(-1px);
            box-shadow: 0 2px 4px rgba(0,0,0,0.06);
        }

        h2 {
            margin-top: 32px;
            margin-bottom: 6px;
            font-size: 1.35rem;
        }

        h3 {
            margin-top: 18px;
            margin-bottom: 4px;
            font-size: 1.05rem;
        }

        p {
            margin: 4px 0 10px;
        }

        .tagline {
            font-size: 0.95rem;
            color: var(--muted);
        }

        .pill {
            display: inline-block;
            padding: 2px 8px;
            border-radius: 999px;
            font-size: 0.75rem;
            background: #e5e7eb;
            color: #111827;
            margin-inline-start: 6px;
        }

        /* Sections & details */
        section {
            background: #fff;
            border-radius: 12px;
            padding: 18px 16px 20px;
            margin-bottom: 16px;
            box-shadow: 0 1px 4px rgba(0,0,0,0.04);
            border: 1px solid rgba(15,23,42,0.04);
        }

        details {
            border-radius: 10px;
            margin-top: 8px;
            border: 1px solid rgba(148,163,184,0.5);
            background: #f9fafb;
        }

        details[open] {
            background: #f3f4ff;
        }

        summary {
            cursor: pointer;
            padding: 8px 12px;
            font-size: 0.9rem;
            font-weight: 600;
            list-style: none;
        }

        summary::-webkit-details-marker {
            display: none;
        }

        summary::before {
            content: "▸";
            display: inline-block;
            margin-left: 6px;
            font-size: 0.8rem;
            transition: transform 0.15s;
        }

        details[open] summary::before {
            transform: rotate(90deg);
        }

        details .details-body {
            padding: 8px 12px 12px;
            border-top: 1px solid rgba(148,163,184,0.5);
            font-size: 0.9rem;
        }

        ul, ol {
            padding-right: 1.1rem;
            margin: 6px 0 10px;
        }

        code {
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace;
            font-size: 0.84rem;
            background: #efeffa;
            padding: 1px 4px;
            border-radius: 4px;
        }

        .badge {
            display: inline-block;
            font-size: 0.78rem;
            border-radius: 999px;
            padding: 1px 8px;
            margin-inline-start: 4px;
            background: rgba(37,99,235,0.08);
            color: #1d4ed8;
        }

        .platform-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit,minmax(180px,1fr));
            gap: 10px;
            margin-top: 8px;
        }

        .platform {
            border-radius: 10px;
            padding: 10px 12px;
            background: #f9fafb;
            border: 1px solid rgba(148,163,184,0.5);
            font-size: 0.9rem;
        }

        .label {
            font-size: 0.8rem;
            font-weight: 600;
            color: var(--muted);
            text-transform: uppercase;
            letter-spacing: 0.03em;
        }

        .link-btn {
            display: inline-block;
            margin-top: 8px;
            padding: 6px 12px;
            border-radius: 999px;
            border: 1px solid var(--primary);
            color: var(--primary);
            text-decoration: none;
            font-size: 0.85rem;
        }

        .link-btn:hover {
            background: #eff2ff;
        }

        .callout {
            border-radius: 10px;
            padding: 10px 12px;
            background: #fff7ed;
            border: 1px solid #fed7aa;
            font-size: 0.9rem;
            margin-top: 10px;
        }

        footer {
            text-align: center;
            padding: 18px 10px 30px;
            font-size: 0.8rem;
            color: var(--muted);
        }
    </style>
</head>
<body>

<header>
    <h1>הפטל של עופר – מערכת מעקב קטיף</h1>
    <p>תיעוד מלא של הזרימה, המודולים והאוטומציות</p>
</header>

<div class="container">

    <!-- Navigation -->
    <nav class="nav">
        <a href="#overview">מבט על</a>
        <a href="#flow">זרימת נתונים</a>
        <a href="#fillout">טופס Fillout</a>
        <a href="#sheets">Google Sheets</a>
        <a href="#scripts">אוטומציות (Apps Script)</a>
        <a href="#triggers">טריגרים</a>
        <a href="#maintenance">תחזוקה ושינויים</a>
    </nav>

    <!-- Overview -->
    <section id="overview">
        <h2>1. מבט על המערכת</h2>
        <p class="tagline">
            המערכת מחברת בין טופס מקוון, גיליון נתונים ואוטומציות כדי להפיק תמונת מצב יומית ושבועית על קטיף הפטל בכל החממות.
        </p>

        <div class="platform-grid">
            <div class="platform">
                <div class="label">קליטה</div>
                <strong>טופס Fillout</strong>
                <div>עובדי השטח ממלאים טופס קצר בסיום קטיף מחממה.</div>
                <a class="link-btn" href="https://forms.fillout.com/t/qpzG7RH3sFus" target="_blank">פתיחת הטופס</a>
            </div>
            <div class="platform">
                <div class="label">אחסון & חישוב</div>
                <strong>Google Sheets</strong>
                <div>כמה גליונות: תשובות גולמיות, נתונים מפורקים לפי חממה/זן, ו-KPI יומיים ושבועיים.</div>
                <a class="link-btn" href="https://docs.google.com/spreadsheets/d/13BhYmx0mXBwclE061Bu5XL1rmGNVqvbVl-4P_R9tXnw/edit?usp=sharing" target="_blank">פתיחת הגיליון</a>
            </div>
            <div class="platform">
                <div class="label">לוגיקה עסקית</div>
                <strong>Google Apps Script</strong>
                <div>שתי אוטומציות עיקריות: עיבוד נתוני קטיף ובניית טבלת עבודה, ושליחת מייל יומי מסכם.</div>
            </div>
        </div>

        <details>
            <summary>פירוט מלא על ארכיטקטורת המערכת</summary>
            <div class="details-body">
                <ol>
                    <li><strong>איסוף נתונים:</strong> כל אירוע קטיף מדווח בטופס Fillout. הנתונים נשמרים תחילה בטבלת תשובות גולמית (Raw_Responses).</li>
                    <li><strong>עיבוד ראשוני:</strong> אוטומציה <code>rebuildHarvestData</code> קוראת את תשובות הטופס, מפרקת את השדות המורכבים (כמו טבלה בתוך תא אחד), ומייצרת טבלת שורות "שטוחה" ב-<code>Harvest_Data</code>.</li>
                    <li><strong>חישוב KPI:</strong> בחישובים וגיליונות נוסעים מעל <code>Harvest_Data</code> כדי להפיק מדדים ל-<code>Harvest_KPI</code> ו-<code>Greenhouse_Performance</code> (תפוקה לפי יום, חממה, זן, 7 ימים, 30 ימים וכו').</li>
                    <li><strong>תקשורת למנהלים:</strong> אוטומציה <code>sendDailyHarvestEmail</code> רצה פעם ביום, שולפת מה-KPI את סיכום היום והנתונים השבועיים, ושולחת מייל מסודר למנהלים.</li>
                </ol>
                <p>מנקודת מבט של משתמש קצה: יש רק שני דברים קבועים – למלא את הטופס אחרי קטיף, ולקרוא את המייל/דשבורד. כל השאר מתרחש מאחורי הקלעים.</p>
            </div>
        </details>
    </section>

    <!-- Data Flow -->
    <section id="flow">
        <h2>2. זרימת נתונים מקצה לקצה</h2>
        <p class="tagline">התרשים הטקסטואלי הבא מסכם את המסלול שעובר כל דיווח קטיף עד שהוא הופך למספר בדשבורד.</p>

        <details open>
            <summary>סיכום קצר של הזרימה</summary>
            <div class="details-body">
                <ol>
                    <li>עובד ממלא טופס קטיף בטלפון.</li>
                    <li>Fillout שולח את הנתונים לשורה חדשה בגיליון תשובות גולמי ב-Google Sheets.</li>
                    <li>סקריפט <code>rebuildHarvestData</code> מעבד את כל השורות ויוצר טבלה מפורטת לפי: תאריך × חממה × זן.</li>
                    <li>נוסחאות בגיליונות KPI מחשבות סך ק"ג, אחוז סוג ב', ק"ג למטר רץ ועוד.</li>
                    <li>סקריפט <code>sendDailyHarvestEmail</code> אוסף את הנתונים של היום + 7 ימים אחרונים ומייצר מייל סיכום.</li>
                </ol>
            </div>
        </details>

        <details>
            <summary>פירוט: מה נכנס ומה יוצא בכל שלב</summary>
            <div class="details-body">
                <h3>שלב 1 – טופס Fillout</h3>
                <ul>
                    <li><strong>קלט מהמשתמש:</strong> תאריך הקטיף, חממה, זן, כמות סוג א, כמות סוג ב, הערות חופשיות.</li>
                    <li><strong>פלט:</strong> רשומה חדשה עם כל הפרטים שנשמרת בטבלת תשובות (Raw_Responses) בגיליון גוגל.</li>
                </ul>
                <h3>שלב 2 – טבלת תשובות גולמית (Raw_Responses)</h3>
                <ul>
                    <li><strong>קלט:</strong> נתון גולמי מהטופס, כולל שדה טקסט אחד שמכיל "רישום קטיף לפי חממה וזן" בפורמט של שורות.</li>
                    <li><strong>פלט:</strong> מאגר נתונים בסיסי שממנו הסקריפט קורא ומפרק לכל חממה/זן.</li>
                </ul>
                <h3>שלב 3 – עיבוד והשטחה (Harvest_Data)</h3>
                <ul>
                    <li><strong>קלט:</strong> כל שורות Raw_Responses + טבלת הגדרות <code>Config_Greenhouses</code> (מידע על מטר רץ, דונמים, זנים וכו').</li>
                    <li><strong>לוגיקה:</strong> הסקריפט עובר על כל שורה, מפרק את הטבלה שבתוך התא לכמה שורות, ממיר כמויות לטיפוס מספרי, ומוסיף מידע עזר (SubmissionID, LineIndex).</li>
                    <li><strong>פלט:</strong> טבלה בה כל שורה מייצגת קומבינציה ייחודית של:
                        <br>תאריך קטיף × חממה × זן × סוג (א/ב) עם הערות רלוונטיות.</li>
                </ul>
                <h3>שלב 4 – חישוב KPI (Harvest_KPI, Greenhouse_Performance)</h3>
                <ul>
                    <li><strong>קלט:</strong> טבלת Harvest_Data + Config_Greenhouses.</li>
                    <li><strong>לוגיקה:</strong> נוסחאות <code>SUMIFS</code>, <code>FILTER</code>, <code>AVERAGE</code> ו-<code>IFERROR</code> מחשבות:
                        <ul>
                            <li>סך ק"ג סוג א / כולל לכל חממה וזן ביום.</li>
                            <li>אחוז סוג ב' מתוך הכולל.</li>
                            <li>ק"ג למטר רץ בחממה.</li>
                            <li>סכום 7 ימים אחרונים וממוצע 30 יום.</li>
                        </ul>
                    </li>
                    <li><strong>פלט:</strong> שתי טבלאות KPI – אחת ברמת חממה+זן, ואחת שמרכזת נתונים לפי חממה לצורך דשבורד וגרפים.</li>
                </ul>
                <h3>שלב 5 – מייל יומי למנהלים</h3>
                <ul>
                    <li><strong>קלט:</strong> נתונים מעודכנים מ-Harvest_KPI ו-Greenhouse_Performance עבור תאריך היום.</li>
                    <li><strong>לוגיקה:</strong> חישוב סיכום לכל החווה + פירוט לכל חממה והשוואה לממוצע שבועי.</li>
                    <li><strong>פלט:</strong> הודעת מייל יומית עם סיכום קטיף והדגשת חממות מעל/מתחת לממוצע.</li>
                </ul>
            </div>
        </details>
    </section>

    <!-- Fillout -->
    <section id="fillout">
        <h2>3. טופס Fillout – נקודת הכניסה למערכת</h2>
        <p class="tagline">הטופס צריך להיות יציב ופשוט – כל שינוי בשדות דורש התאמה בסקריפט ובגיליון.</p>

        <details open>
            <summary>שדות חובה ומבנה מומלץ</summary>
            <div class="details-body">
                <ul>
                    <li><strong>תאריך הקטיף</strong> – אם אפשר, ברירת מחדל לתאריך היום.</li>
                    <li><strong>חממה</strong> – רשימה נפתחת עם 1–6 (או שמות חממות).</li>
                    <li><strong>זן</strong> – רשימה נפתחת של הזנים הפעילים.</li>
                    <li><strong>כמות סוג א (ק"ג)</strong> – שדה מספר.</li>
                    <li><strong>כמות סוג ב (ק"ג)</strong> – שדה מספר (אפשר 0).</li>
                    <li><strong>הערות ליום הקטיף</strong> – טקסט חופשי (מזג אוויר, מחלות, חוסרים וכו').</li>
                </ul>
                <p>הטופס הקיים יכול לכלול גם שדה מורכב של "רישום קטיף לפי חממה וזן" בטבלה – הסקריפט הנוכחי יודע לפרק אותו לשורות נפרדות.</p>
                <a class="link-btn" href="https://forms.fillout.com/t/qpzG7RH3sFus" target="_blank">פתיחת הטופס</a>
            </div>
        </details>

        <details>
            <summary>מה צריך לדעת אם מוסיפים או משנים שדות?</summary>
            <div class="details-body">
                <ul>
                    <li>כל שינוי בשם שדה או מבנה השדה בטופס משנה את כותרות העמודות ב-Raw_Responses.</li>
                    <li>האוטומציה <code>rebuildHarvestData</code> מאתרת עמודות לפי שמות כותרות. שינוי שם עמודה יחייב עדכון בקוד.</li>
                    <li>המלצה: לפני שינוי, לסמן צילום מסך של כותרות הגיליון ולהשוות אחרי השינוי.</li>
                </ul>
            </div>
        </details>
    </section>

    <!-- Sheets -->
    <section id="sheets">
        <h2>4. Google Sheets – מבנה הגיליונות</h2>

        <details open>
            <summary>סקירה של הגיליונות העיקריים</summary>
            <div class="details-body">
                <ul>
                    <li><strong>Raw_Responses</strong> <span class="badge">קריאה בלבד</span> – שורות גולמיות שמגיעות מהטופס.</li>
                    <li><strong>Harvest_Data</strong> <span class="badge">נבנה אוטומטית</span> – טבלה מפורקת ברמת חממה+זן+סוג.</li>
                    <li><strong>Config_Greenhouses</strong> <span class="badge">קונפיגורציה</span> – מידע סטטי לכל חממה (שם, מטר רץ שתול, דונם וכו').</li>
                    <li><strong>Harvest_KPI</strong> – KPI ברמת תאריך+חממה+זן (סך ק"ג, אחוזים, ק"ג למטר רץ).</li>
                    <li><strong>Greenhouse_Performance</strong> – סיכומים ברמת חממה (שבועי/חודשי, דירוג חממות, גרפים).</li>
                </ul>
                <p>העיקרון: לא לגעת ידנית ב-Raw_Responses וב-Harvest_Data. העבודה האנליטית והגרפים מתבצעים על Harvest_KPI ו-Greenhouse_Performance בלבד.</p>
            </div>
        </details>

        <details>
            <summary>שדות מפתח ב-Harvest_Data וב-Harvest_KPI</summary>
            <div class="details-body">
                <h3>Harvest_Data – שורה = "אירוע קטיף מפורק"</h3>
                <ul>
                    <li>תאריך הקטיף</li>
                    <li>חממה</li>
                    <li>זן</li>
                    <li>כמות סוג א (ק"ג)</li>
                    <li>כמות סוג ב (ק"ג)</li>
                    <li>הערות ליום הקטיף</li>
                    <li>SubmissionID + LineIndex – מזהים לחיבור חזרה לשורה בטופס המקורי במקרה הצורך</li>
                </ul>
                <h3>Harvest_KPI – שורה = "יום × חממה × זן"</h3>
                <ul>
                    <li>סך ק"ג סוג א ליום</li>
                    <li>סך ק"ג כולל ליום</li>
                    <li>% סוג ב' מסך הקטיף</li>
                    <li>ק"ג למטר רץ ליום</li>
                    <li>ממוצע 7 ימים / 30 ימים (בהתאם לנוסחאות שבחרת)</li>
                </ul>
            </div>
        </details>
    </section>

    <!-- Scripts -->
    <section id="scripts">
        <h2>5. האוטומציות ב-Apps Script</h2>
        <p class="tagline">פרויקט יחיד ב-Apps Script שמחובר לגיליון, ובתוכו שתי פונקציות עיקריות.</p>

        <details open>
            <summary>5.1 rebuildHarvestData – עיבוד ופירוק הנתונים</summary>
            <div class="details-body">
                <p><strong>מטרה:</strong> לקרוא את נתוני הטופס, לפרק שדה טבלה מורכב ולהכניס ל-Harvest_Data שורה לכל חממה × זן × סוג.</p>
                <ul>
                    <li>מאתר את עמודות המפתח לפי שמות כותרת (תאריך הקטיף, רישום קטיף וכו').</li>
                    <li>עובר על כל שורה ב-Raw_Responses, מדלג על שורות ריקות.</li>
                    <li>מפצל את שדה "רישום קטיף לפי חממה וזן" לכמה שורות, לפי הפרדת שורות וסימני פסיק.</li>
                    <li>ממיר כל כמות לפורמט מספרי באמצעות פונקציית עזר <code>toNumberSafe</code>.</li>
                    <li>מכניס ל-Harvest_Data:
                        <br>תאריך, חממה, זן, כמות סוג א, כמות סוג ב, הערות, SubmissionID, LineIndex.</li>
                    <li>לפני הכתיבה מנקה את התוכן הישן בגיליון Harvest_Data ומשאיר את שורת הכותרת.</li>
                </ul>
                <p>כל פעם שהפונקציה רצה – היא בונה את Harvest_Data מחדש בהתאם לכל התשובות שהצטברו עד היום.</p>
                <a class="link-btn" href="LINK_TO_REBUILDHARVESTDATA_CODE" target="_blank">
                    צפייה בקוד המלא של rebuildHarvestData
                </a>
                <div class="callout">
                    <strong>חשוב:</strong> שינוי שמות כותרות הגיליון או מבנה שדה הטבלה בטופס עלול לשבור את הפונקציה. לפני שינוי, לוודא שגם הקוד מתעדכן בהתאם.
                </div>
            </div>
        </details>

        <details>
            <summary>5.2 sendDailyHarvestEmail – מייל סיכום יומי</summary>
            <div class="details-body">
                <p><strong>מטרה:</strong> לשלוח פעם ביום סיכום קטיף ל-מנהלים, עם השוואה ל-7 ימים אחרונים.</p>
                <ul>
                    <li>קובע את <code>today</code> לפי אזור הזמן של הגיליון, וממיר לפורמט תאריך אחיד.</li>
                    <li>קורא את Harvest_KPI, ומסכם לכל חממה:
                        <ul>
                            <li>סך ק"ג היום (כולל פירוק לסוג א/ב).</li>
                            <li>סך כל הקטיף היום בכל החממות.</li>
                        </ul>
                    </li>
                    <li>אם אין אף קטיף ליום הזה – הפונקציה יוצאת ללא שליחת מייל.</li>
                    <li>קורא את Greenhouse_Performance כדי לקבל סך ק"ג ב-7 ימים אחרונים לכל חממה.</li>
                    <li>מחשב לכל חממה:
                        <br>ממוצע יומי בשבוע האחרון + אחוז מעל/מתחת לממוצע.</li>
                    <li>בונה טקסט מייל קריא (Subject + Body) ושולח לכתובות שהוגדרו בקוד.</li>
                </ul>
                <a class="link-btn" href="LINK_TO_SENDDAILYHARVESTEMAIL_CODE" target="_blank">
                    צפייה בקוד המלא של sendDailyHarvestEmail
                </a>
                <div class="callout">
                    ניתן להרחיב את הפונקציה כך שתשלח גם SMS / WhatsApp דרך שירות חיצוני (Twilio/Make), כל עוד שומרים על אותו עיקרון: לא שולחים אם לא היה קטיף באותו היום.
                </div>
            </div>
        </details>
    </section>

    <!-- Triggers -->
    <section id="triggers">
        <h2>6. טריגרים – מתי האוטומציות רצות</h2>

        <details open>
            <summary>סוגי הטריגרים המוגדרים במערכת</summary>
            <div class="details-body">
                <ul>
                    <li><strong>טריגר זמן יומי</strong> – מפעיל את <code>sendDailyHarvestEmail</code> פעם ביום, לדוגמה בין 20:00–21:00.</li>
                    <li><strong>הרצה ידנית / לפי הצורך</strong> – <code>rebuildHarvestData</code> רצה לפי דרישה (כפתור "הפעלה" ב-Apps Script או טריגר זמן תקופתי אם תרצה).</li>
                </ul>
                <p>אפשר להוסיף טריגר זמן נוסף ל-<code>rebuildHarvestData</code> פעם ביום, לפני שליחת המייל, כדי לוודא שהנתונים בוודאות מעודכנים.</p>
            </div>
        </details>

        <details>
            <summary>איך מוסיפים או משנים טריגר ב-Apps Script</summary>
            <div class="details-body">
                <ol>
                    <li>נכנסים לפרויקט Apps Script המחובר לגיליון.</li>
                    <li>בצד שמאל בוחרים <strong>"מפעילים"</strong> (Triggers).</li>
                    <li>לוחצים על <strong>"הוספת טריגר"</strong>.</li>
                    <li>בוחרים:
                        <ul>
                            <li>פונקציה להפעלה – למשל <code>sendDailyHarvestEmail</code>.</li>
                            <li>סוג טריגר – מופעל לפי זמן (Time-driven).</li>
                            <li>תדירות – יומי.</li>
                            <li>טווח שעה – למשל 20:00–21:00.</li>
                        </ul>
                    </li>
                    <li>מאשרים הרשאות בפעם הראשונה (גישה לגיליון + גישה לשליחת מייל).</li>
                </ol>
            </div>
        </details>
    </section>

    <!-- Maintenance -->
    <section id="maintenance">
        <h2>7. תחזוקה, הרחבות ותקלות נפוצות</h2>

        <details open>
            <summary>מה מותר ומה כדאי לא לגעת?</summary>
            <div class="details-body">
                <ul>
                    <li><strong>מותר:</strong> להוסיף גיליונות חדשים לניתוחים וגרפים, שמבוססים על Harvest_KPI ו-Greenhouse_Performance.</li>
                    <li><strong>מותר:</strong> להוסיף זנים חדשים / חממות חדשות דרך <code>Config_Greenhouses</code>, כל עוד נשמר הפורמט.</li>
                    <li><strong>לא מומלץ:</strong> לערוך ידנית נתונים ב-Raw_Responses או ב-Harvest_Data – עלול לשבור עקביות בין הטופס לאוטומציות.</li>
                    <li><strong>לא כדאי:</strong> לשנות שמות גליונות או כותרות עמודות בלי לעדכן גם את הקוד.</li>
                </ul>
            </div>
        </details>

        <details>
            <summary>פתרון תקלות בסיסי</summary>
            <div class="details-body">
                <ul>
                    <li>אם מתקבלת שגיאה בסגנון "לא נמצאה כותרת עמודה בשם ...":
                        <br>בדוק שהכותרת בגליון תואמת בדיוק לשם שמופיע בקוד (כולל רווחים).</li>
                    <li>אם Harvest_Data ריק:
                        <br>להריץ ידנית את <code>rebuildHarvestData</code> ולבדוק את יומן הביצוע (Execution log) לאיתור השורה הבעייתית.</li>
                    <li>אם לא מתקבל מייל:
                        <br>לבדוק ב-Apps Script תחת "מפעילים" אם הטריגר רץ, ואם יש שגיאה בפונקציה <code>sendDailyHarvestEmail</code>.</li>
                </ul>
            </div>
        </details>

        <details>
            <summary>איך לשכפל את המערכת לעסק נוסף</summary>
            <div class="details-body">
                <ol>
                    <li>שכפול גיליון גוגל + התאמת טבלת <code>Config_Greenhouses</code> לשמות החממות והשטחים החדשים.</li>
                    <li>יצירת עותק של פרויקט ה-Apps Script וחיבורו לגיליון החדש.</li>
                    <li>עדכון כתובות המייל בקוד <code>sendDailyHarvestEmail</code>.</li>
                    <li>יצירת טופס Fillout חדש שמכוון לגיליון העותק (או Google Form אם מחליטים לשנות כלי).</li>
                </ol>
                <p>הגישה המומלצת: להשאיר את הלוגיקה והמבנה זהים ככל האפשר, ולהחליף רק קונפיגורציה (חממות, שטחים, נמעני מייל).</p>
            </div>
        </details>
    </section>

</div>

<footer>
    תיעוד זה נועד לאפשר לכל מנהל טכני להבין, להרחיב ולתחזק את מערכת מעקב הקטיף של "הפטל של עופר".
</footer>

</body>
</html>
