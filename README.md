# Chinese Auction Management System - Backend API (.NET)

זהו צד השרת של המערכת לניהול "מכירה סינית". השרת מספק את ה-API והלוגיקה העסקית הנדרשת לניהול המכירה, המשתמשים ותהליך ההגרלה. הפרויקט בנוי בטכנולוגיית .NET עם דגש על ארכיטקטורה מסודרת וביצועים.

## 🔗 קישורים רלוונטיים
* **צד לקוח (Frontend):** https://github.com/hadasa619/ChineseRaffleNg

## 🛠 טכנולוגיות (Tech Stack)
* **Framework:** .NET (C#)
* **API Style:** ASP.NET Core Web API
* **Database:** Microsoft SQL Server (MSSQL)
* **ORM:** Entity Framework Core
* **Authentication:** JWT (JSON Web Tokens)

## 🚀 תכונות מרכזיות (Key Features)
* **ניהול משתמשים:** מערכת אימות (Authentication) והרשאות (Authorization) מבוססת JWT.
* **ניהול מסד נתונים:** שימוש ב-SQL Server לניהול קשרי גומלין מורכבים בין משתמשים, כרטיסים ופרסים.
* **Business Logic:** מימוש אלגוריתם הגרלה אקראי בצד השרת המבטיח הגינות ושקיפות.
* **RESTful API:** חשיפת נקודות קצה (Endpoints) מנוהלות היטב עבור צד הלקוח.
* **Migrations:** ניהול גרסאות מסד הנתונים באמצעות Entity Framework.

## 📂 מבנה הפרויקט (Project Structure)
* `Controllers/` - ניהול הבקשות והתגובות (HTTP Requests).
* `Models/` - הגדרת הישויות והטבלאות של מסד הנתונים.
* `Data/ / Context/` - הגדרת ה-DbContext והתקשרות מול ה-SQL.
* `DTOs/` - אובייקטים להעברת נתונים בין השרת ללקוח בצורה מאובטחת.
* `Services/` (אם קיים) - הפרדת הלוגיקה העסקית מהקונטרולרים.

## ⚙️ הרצה מקומית
1. שכפל את המאגר:
   ```bash
   git clone https://github.com/hadasa619/ChineseRaffleApi
