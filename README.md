# 📱 Glassmorphism Login App - Flutter

تطبيق نظام تسجيل دخول حديث وأنيق مبني باستخدام إطار العمل Flutter. يتميز التطبيق بتصميم عصري يعتمد على الألوان الداكنة المتدرجة وتأثيرات الزجاج الشفاف (Glassmorphism).

---

## 📸 Screenshots | صور التطبيق

| Login Screen | Home Dashboard |
|---|---|
| ![Login Screen](./screenshots/login.png) | ![Home Dashboard](./screenshots/home.png) |

---

## ✨ المميزات (Features)
* 🎨 **تصميم عصري:** خلفية متدرجة جذابة مع حقول إدخال شبه شفافة.
* 🧠 **كود نظيف:** فصل منطق التحكم (LoginController) عن واجهة المستخدم.
* 🔐 **نظام مصادقة:** التحقق من صحة الإيميل وكلمة المرور برمجياً.
* 🛡️ **تنبيهات فورية:** رسائل ترحيب عند النجاح ورسائل خطأ عند إدخال بيانات غير صحيحة.
* 🚪 **تسجيل خروج:** إمكانية العودة لشاشة الدخول بسهولة من الـ Dashboard.

---

## 📂 هيكلية المشروع (Project Structure)

* **`login_controller.dart`**: المسؤول عن إدارة البيانات والتحقق من صحة المدخلات.
* **`login_screen.dart`**: واجهة تسجيل الدخول التي تحتوي على التصميم الزجاجي.
* **`home_screen.dart`**: لوحة التحكم التي تظهر بعد تسجيل الدخول بنجاح.

---

## 🛠️ بيانات التجربة (Mock Credentials)
للاختبار، يمكنك استخدام البيانات التالية المسجلة مسبقاً في الكود:
* **Email:** `HELMI@gmail.com`
* **Password:** `111111111`

---

## 🚀 طريقة التشغيل (How to Run)
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/logine_app.git](https://github.com/your-username/logine_app.git)