<div dir="rtl" align="right">

# 🌊 Azure Coast - Team Project 🏖️

أهلاً بيكم يا شباب في ريبو مشروعنا **"Azure Coast"** 💙
المشروع عبارة عن موقع لحجز الشاليهات والمنتجعات في الساحل الشمالي.

الملف ده هو **"الخريطة"** بتاعتنا. كل واحد فينا مسؤول عن ملفات معينة، فمحدش يعدل على شغل التاني عشان منبوظش الدنيا 😅.

---

## 📂 هيكل المشروع (Project Structure)

المشروع متقسم لجزئين: 
1. **Frontend** (شغل الـ HTML, CSS, JS).
2. **Backend** (شغل الـ PHP والـ MySQL).

</div>

```text
Azure-Coast/
│
├── frontend/               ← (الواجهة بتاعت المستخدم)
│   ├── index.html
│   ├── about.html
│   ├── chalets.html
│   ├── chalet-details.html
│   ├── booking.html
│   ├── login.html
│   ├── register.html
│   ├── my-bookings.html
│   │
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   ├── main.js
│   │   ├── auth.js
│   │   ├── chalets.js
│   │   ├── chalet-details.js
│   │   ├── booking.js
│   │   └── my-bookings.js
│   │
│   └── images/
│
├── backend/                ← (الخادم وقاعدة البيانات)
│   ├── config/
│   │   └── db.php
│   ├── auth/
│   │   ├── login_action.php
│   │   ├── register_action.php
│   │   └── logout_action.php
│   ├── chalets/
│   │   ├── get_chalets.php
│   │   └── get_chalet_details.php
│   └── bookings/
│       ├── create_booking.php
│       └── get_my_bookings.php
│
└── database.sql

<div dir="rtl" align="right">
🤝 دلوقتي تقسيم المشروع (شغل الإكسيل 😎)
<table style="width:100%; border-collapse: collapse; text-align: right; border: 2px solid #007BFF;"> <thead> <tr style="background-color: #007BFF; color: white;"> <th style="padding: 12px; border: 1px solid #ddd;">العضو</th> <th style="padding: 12px; border: 1px solid #ddd;">بيعمل إيه؟</th> <th style="padding: 12px; border: 1px solid #ddd;">ملفات الـ Frontend (HTML/JS)</th> <th style="padding: 12px; border: 1px solid #ddd;">ملفات الـ Backend (PHP)</th> </tr> </thead> <tbody> <tr style="background-color: #f9f9f9;"> <td style="padding: 10px; border: 1px solid #ddd;"><b>عضو 1</b></td> <td style="padding: 10px; border: 1px solid #ddd;">اللوجين والإعدادات</td> <td style="padding: 10px; border: 1px solid #ddd;">login.html, register.html, js/auth.js</td> <td style="padding: 10px; border: 1px solid #ddd;">config/db.php, auth/login_action.php, auth/register_action.php, auth/logout_action.php</td> </tr> <tr> <td style="padding: 10px; border: 1px solid #ddd;"><b>عضو 2</b></td> <td style="padding: 10px; border: 1px solid #ddd;">الصفحة الرئيسية</td> <td style="padding: 10px; border: 1px solid #ddd;">index.html, js/main.js (الهيدر والفوتر)</td> <td style="padding: 10px; border: 1px solid #ddd;">(مفيش شغل باك إند)</td> </tr> <tr style="background-color: #f9f9f9;"> <td style="padding: 10px; border: 1px solid #ddd;"><b>عضو 3</b></td> <td style="padding: 10px; border: 1px solid #ddd;">صفحة About</td> <td style="padding: 10px; border: 1px solid #ddd;">about.html</td> <td style="padding: 10px; border: 1px solid #ddd;">(مفيش شغل باك إند)</td> </tr> <tr> <td style="padding: 10px; border: 1px solid #ddd;"><b>عضو 4</b></td> <td style="padding: 10px; border: 1px solid #ddd;">صفحة الشاليهات</td> <td style="padding: 10px; border: 1px solid #ddd;">chalets.html, js/chalets.js</td> <td style="padding: 10px; border: 1px solid #ddd;">chalets/get_chalets.php</td> </tr> <tr style="background-color: #f9f9f9;"> <td style="padding: 10px; border: 1px solid #ddd;"><b>عضو 5</b></td> <td style="padding: 10px; border: 1px solid #ddd;">تفاصيل الشاليه</td> <td style="padding: 10px; border: 1px solid #ddd;">chalet-details.html, js/chalet-details.js</td> <td style="padding: 10px; border: 1px solid #ddd;">chalets/get_chalet_details.php</td> </tr> <tr> <td style="padding: 10px; border: 1px solid #ddd;"><b>عضو 6</b></td> <td style="padding: 10px; border: 1px solid #ddd;">صفحة الحجز</td> <td style="padding: 10px; border: 1px solid #ddd;">booking.html, js/booking.js</td> <td style="padding: 10px; border: 1px solid #ddd;">bookings/create_booking.php</td> </tr> <tr style="background-color: #f9f9f9;"> <td style="padding: 10px; border: 1px solid #ddd;"><b>عضو 7</b></td> <td style="padding: 10px; border: 1px solid #ddd;">حجوزاتي</td> <td style="padding: 10px; border: 1px solid #ddd;">my-bookings.html, js/my-bookings.js</td> <td style="padding: 10px; border: 1px solid #ddd;">bookings/get_my_bookings.php</td> </tr> </tbody> </table>

يا جماعة، الخريطة قدامكم، كل واحد يختار رقمه ويبدأ شغل. أي حد يقف معاه حاجة يكلمني. بالتوفيق 💪🔥
</div> ```
