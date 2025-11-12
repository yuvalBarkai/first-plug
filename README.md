GIT

לצירוף פרויקט ל-git  יש לפתוח את git bash בספריית הפרויקט ולרשום את הפקודה הבאה:
git init
בדיקת גירסה:
git –version
הכנסת שם משתמש ודוא"ל:
git config --global user.name "<username>"
git config --global user.email "<email>"
שמירת גירסה (כל הקבצים):
git add .
git commit –m "<message>"
רשימת גירסאות:
git log
תיוג גירסה:
git tag <tagname>
מעבר בין גירסאות:
בעזרת tag
git checkout <tag-name>	
בעזרת מספר הגירסה (מספיקות ארבע ספרות ראשונות)
git checkout <commit-id>		
מעבר לגירסה האחרונה בענף:
git checkout master

העלאה ל- github:
יש לפתוח חשבון ב- github. 
יש לפתוח repository עבור הפרויקט.
קישור הפרויקט ל- repository:
git remote add <push-name> <rep-address>
git remote add TheApp https://repo/address
TheApp הוא שם שאנחנו ממציאים לצורך ההעלאה.

העלאת הפרויקט:
git push <push-name> <branch-name>
git push TheApp master
בפעם הראשונה שמבצעים העלאה ממחשב מסוים תידרשו להכניס את שם המשתמש והסיסמה שלכם ב- github. הפרטים האלה נשמרים על המחשב, ובפעמים הבאות אין צורך בזיהוי.
