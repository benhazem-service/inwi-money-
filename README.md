# نظام تسيير الفواتير وحسابات inwi (INWI MONEY)

تطبيق ويب متكامل لإدارة الفواتير، عمليات الدفع، متابعة رصيد الصندوق، حساب inwi، وحساب الأرباح مع مزامنة فورية عبر Firebase Firestore.

## 🚀 الاستضافة على GitHub Pages

التطبيق عبارة عن صفحة ويب ثابتة (Static Web App) جاهزة للعمل مباشرة على **GitHub Pages**:

1. أنشئ مستودعاً جديداً (New Repository) على حسابك في GitHub (مثلاً: `inwi-money`).
2. ارفع جميع الملفات (بما في ذلك `index.html`) إلى المستودع.
3. ادخل إلى إعدادات المستودع في GitHub:
   - اذهب إلى **Settings** > **Pages**
   - في قسم **Build and deployment**:
     - اختر **Source**: `Deploy from a branch`
     - اختر الفرع `main` (أو `master`) والمجلد `/ (root)`
     - اضغط **Save**
4. سيظهر لك رابط الموقع بعد دقائق قليلة بصيغة:
   `https://<your-username>.github.io/<repo-name>/`

---

## ⚠️ خطوة مهمة جداً لـ Firebase Authentication:
لكي يعمل تسجيل الدخول بنجاح على رابط GitHub Pages:
1. افتح منصة [Firebase Console](https://console.firebase.google.com/).
2. اختر المشروع: `inwi-money-29903`.
3. اذهب إلى **Authentication** > علامة التبويب **Settings** > **Authorized domains**.
4. اضغط على **Add domain** وأضف:
   - `<your-username>.github.io` (اسم المستخدم الخاص بك في GitHub).
5. اضغط **Save**.
