.. EN-Revision: none
.. _introduction.installation:

התקנה
=====

ראו את :ref:`נספח דרישות המערכת <requirements>` לרשימה מלאה של כל
האלמנטים הדרושים לשימוש ב Zend Framework.

התקנת המערכת של Zend Framework הינה קלה ומהירה. לאחר שהורדתם וחלצתם את
הקבצים של ה framework , כדי לכם להוסיף את תיקית הספריה של Zend /library
לתיקיה הראשית של האפליקציה שהנכם מתכנתים. כמו כן רצוי להעתיק את
כל התוכן של הספריה אל מקום נוסף במחשב/תיקית שיתוף שיהיה ניתן
לגשת אליה בקלות יותר.

   - `הורידו את הגרסא היציבה האחרונה של המערכת.`_ הגרסא זמינה בשני
     סוגי פורמטים *.zip* ו *.tar.gz*.

   - `הורד את הגרסא 'הלילית' האחרונה`_ לאלו מכם שרוצים לנסות
     ולהשתתף בתהליך הבדיקות של המערכת, ניתן להוריד את גרסאת
     הפיתוח האחרונה ישירות מה SVN של המערכת. גרסאות הפיתוח מגיעות
     עם הדוקומנטציה של המערכת באנגלית בלבד או בכל השפות. אם גם אתה
     רוצה להשתתף בפיתוח המערכת, תצטרך לשקלו שימוש ב subversion (SVN)
     לניהול קבצים.

   - שימוש ב `Subversion (SVN)`_ בתור תוכנה לניהול הקבצים. Zend Framework שהינה
     מערכת קוד פתוח, ולכן כל הקבצים אשר המתכנתים עובדים עליהם
     פתוחים לקהל הרחב. בעזרת שימוש בתוכנה לניהול הקבצים כגון
     Subversion (SVN) ניתן לגשת ישירות לקוד מקור של המערכת, כמובן שלא
     יהיה ניתן לשנות את הקוד מקור בשרת של המערכת. ניתן לשקול את
     האפשרות של קבלת הקבצים ישירות מהשרת של Zend אל האפליקציה שלכם
     בשרת או במחשב. כמו כן במידה ותרצו לתת בחזרה ל Zend תוכלו לעשות
     זאת על ידי שליחת פנייה באימייל לאחראי הצוותים לקבלת אפשרות
     עריכה בשרת ותוכלו גם אתם לקחת חלק בפיתוח.

     `ייצא`_ של כל המערכת הינו דבר שימושי במידה והכנם מעוניינים
     להשיג גרסא מסויימת של המערכת ללא כל תיקיות וקבצי ה *.svn* אשר
     משמשות למערכת ניהול הקבצים בלבד.

     `הורידו גרסא עדכנית`_ ישירות מהשרת במידה ותרצו להשתתף בתהליך
     הפיתוח של המערכת, הגרסא האחרונה שהנה הגרסא הנוכחית והעדכנית
     מאפשרת `קבלת העדכונים האחרונים שנעשו`_ ושינויים ניתן להוסיף
     למערכת המקורית שנמצאת בשרתים של Zend על ידי שימוש בפקודות
     `כתיבה`_.

     שימוש בהגדרות `חיצוניות`_ הינו דבר שימושי ויעיל למתכנתים
     שכבר משתמשים במערכת ניהול קבצים מסוג SVN כדי לנהל את גרסאות
     המערכת של Zend באפליקציות שלהם.

     קישור ישיר למאגר הקבצים של המערכת:
     `http://framework.zend.com/svn/framework/standard/trunk`_



ברגע שיש לכם עותק של המערכת של Zend Framework, האפליקציה שלכם תצטרך
לדעת לגשת לתיקיה של המערכת של Zend ולגשת לכל המחלקות שלה. `ישנם
כמה דברים לבצע זאת`_, ההגדרה של `include_path`_ בהגדרות ה PHP בשרתם שלכם
צריכה להכיל את הנתיב לתיקיה של Zend היכן שכל הספריות והמחלקות שלה
נמצאות.

Zend מספקת `מדריך מהיר`_ לשימוש במערכת כדי שתוכלו להתחיל להשתמש בה
בקלות וביעילות. זוהי דרך נהדרת להתחיל ללמוד אודות מערכת Zend
Framework עם דגש ודוגמאות מהעולם האמיתי.

מאחר וכל המחלקות ב Zend לא בהכרח דורשות את המצאותן של מחלקות
אחרות כדי שכל המערכת תפעלנה כגורם אחד, תוכל להשתמש רק בחלק
מהמחלקות והספריות שהמערכת מכילה ועל ידי כך לעשות שימוש רק בחלק
מהמחלקות באפליקציות שלכם. הפרק הבא מכיל מאגר נתונים מורחב לגבי
כל ספריה/מחלקה שנמצאת במערכת ה Zend Framework.



.. _`הורידו את הגרסא היציבה האחרונה של המערכת.`: http://framework.zend.com/download/latest
.. _`הורד את הגרסא 'הלילית' האחרונה`: http://framework.zend.com/download/snapshot
.. _`Subversion (SVN)`: http://subversion.tigris.org
.. _`ייצא`: http://svnbook.red-bean.com/nightly/en/svn.ref.svn.c.export.html
.. _`הורידו גרסא עדכנית`: http://svnbook.red-bean.com/nightly/en/svn.ref.svn.c.checkout.html
.. _`קבלת העדכונים האחרונים שנעשו`: http://svnbook.red-bean.com/nightly/en/svn.ref.svn.c.update.html
.. _`כתיבה`: http://svnbook.red-bean.com/nightly/en/svn.ref.svn.c.commit.html
.. _`חיצוניות`: http://svnbook.red-bean.com/nightly/en/svn.advanced.externals.html
.. _`http://framework.zend.com/svn/framework/standard/trunk`: http://framework.zend.com/svn/framework/standard/trunk
.. _`ישנם כמה דברים לבצע זאת`: http://www.php.net/manual/en/configuration.changes.php
.. _`include_path`: http://www.php.net/manual/en/ini.core.php#ini.include-path
.. _`מדריך מהיר`: http://framework.zend.com/docs/quickstart
