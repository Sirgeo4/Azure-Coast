# 🌊 Azure Coast | الساحل الأزرق 🏖️

<div align="center">

# 🌊 AZURE COAST

### Your Perfect Summer Destination

**منصة لحجز الشاليهات والمنتجعات في الساحل الشمالي**

اكتشف وجهتك المثالية، استعرض أفضل الشاليهات، واحجز إجازتك بكل سهولة!

<br>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

<br>

**🎓 University Team Project | 💙 Azure Coast Development Team**

</div>

---

<div dir="rtl" align="right">

## 🌴 عن المشروع | About The Project

**Azure Coast** هو مشروع ويب يهدف إلى توفير منصة سهلة الاستخدام لحجز الشاليهات والمنتجعات في الساحل الشمالي.

يتيح الموقع للمستخدمين استعراض الشاليهات المتاحة، مشاهدة تفاصيل كل شاليه، إنشاء حساب، تسجيل الدخول، وإدارة حجوزاتهم من خلال واجهة بسيطة ومنظمة.

### ✨ Project Goals

- 🏡 عرض الشاليهات والمنتجعات المتاحة.
- 🔍 استعراض تفاصيل كل شاليه.
- 👤 إنشاء حساب وتسجيل الدخول.
- 📅 إمكانية إجراء الحجوزات.
- 📋 متابعة الحجوزات الشخصية.
- 💻 توفير تجربة استخدام سهلة ومنظمة.

---

## 🛠️ Technologies Used

| Technology | Usage |
|:---:|---|
| HTML5 | بناء صفحات الموقع |
| CSS3 | تصميم وتنسيق الواجهات |
| JavaScript | التفاعل مع المستخدم |
| PHP | معالجة البيانات والطلبات |
| MySQL | تخزين وإدارة البيانات |

---

## 📂 Project Structure

المشروع مقسوم إلى جزئين أساسيين:

- **Frontend:** مسؤول عن واجهة المستخدم والتفاعل معها.
- **Backend:** مسؤول عن معالجة الطلبات والتعامل مع قاعدة البيانات.

</div>

```text
Azure-Coast/
│
├── "***  frontend    ***"/
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
├──" *****       backend     *****"/
│   ├── config/
│   │   └── db.php
│   │
│   ├── auth/
│   │   ├── login_action.php
│   │   ├── register_action.php
│   │   └── logout_action.php
│   │
│   ├── chalets/
│   │   ├── get_chalets.php
│   │   └── get_chalet_details.php
│   │
│   └── bookings/
│       ├── create_booking.php
│       └── get_my_bookings.php
│
└── database.sql
```

<div dir="rtl" align="right">

---

## 🤝 Team Members & Responsibilities

كل عضو مسؤول عن مجموعة ملفات محددة، وده بيساعدنا ننظم الشغل ونتجنب التعارض أثناء التطوير.

### 👨‍💻 توزيع المهام

</div>

| Member | Responsibility | Frontend Files | Backend Files |
|:---:|---|---|---|
| **Member 1** | 🔐 Authentication & Configuration | `login.html`<br>`register.html`<br>`js/auth.js` | `config/db.php`<br>`auth/login_action.php`<br>`auth/register_action.php`<br>`auth/logout_action.php` |
| **Member 2** | 🏠 Home Page | `index.html`<br>`js/main.js` (Header & Footer) | — |
| **Member 3** | ℹ️ About Page | `about.html` | — |
| **Member 4** | 🏡 Chalets Listing | `chalets.html`<br>`js/chalets.js` | `chalets/get_chalets.php` |
| **Member 5** | 🔎 Chalet Details | `chalet-details.html`<br>`js/chalet-details.js` | `chalets/get_chalet_details.php` |
| **Member 6** | 📅 Booking System | `booking.html`<br>`js/booking.js` | `bookings/create_booking.php` |
| **Member 7** | 📋 My Bookings | `my-bookings.html`<br>`js/my-bookings.js` | `bookings/get_my_bookings.php` |

<div dir="rtl" align="right">

---

## ⚠️ Team Collaboration Rules

علشان نضمن إن الشغل يمشي بشكل منظم، كل أعضاء الفريق ملتزمين بالقواعد التالية:

1. **File Ownership:** كل عضو مسؤول عن الملفات المحددة ليه في جدول توزيع المهام.
2. **No Unauthorized Changes:** ممنوع تعديل ملفات عضو تاني بدون الرجوع ليه والاتفاق معاه.
3. **Git Workflow:** كل عضو يشتغل على الـ Branch الخاص بيه قبل دمج التعديلات في المشروع.
4. **Communication:** أي تعديل محتاج يؤثر على ملفات عضو آخر لازم يتم الاتفاق عليه مسبقاً.
5. **Code Organization:** لازم نحافظ على تنظيم الملفات وطريقة كتابة الكود في المشروع.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Move to the Project Directory

```bash
cd Azure-Coast
```

### 3. Setup the Database

- افتح phpMyAdmin.
- أنشئ قاعدة البيانات المطلوبة.
- استورد ملف `database.sql`.

### 4. Configure Database Connection

قم بتعديل إعدادات الاتصال بقاعدة البيانات داخل:

```text
backend/config/db.php
```

### 5. Run the Project

شغّل المشروع باستخدام بيئة محلية تدعم PHP وMySQL مثل XAMPP، ثم افتح واجهة المشروع من المتصفح.

---

## 💙 Our Team

**Built with teamwork, passion, and a shared vision.**

</div>

<div align="center">

### 🌊 Azure Coast

*Making your summer reservations easier.*

**Enjoy the coast. Enjoy the moment. 🏖️**

</div>
