clinic-project/
│
├── dashboard.py        # الواجهة الرئيسية للنظام
├── xray.py             # قسم الأشعة
├── dentel.py           # قسم المواعيد والعلاج
├── implant.py          # قسم الزرعات
├── press.py            # قسم الحشوات
├── create_database.py  # إنشاء قاعدة البيانات
├── clinic.db           # ملف قاعدة البيانات
├── images/             # الصور المستخدمة في الواجهة
└── README.md           # وصف المشروع


🗄️ قاعدة البيانات

يتم إنشاء قاعدة البيانات تلقائياً باستخدام ملف:

create_database.py

وتحتوي على الجداول التالية:

xrays

dental

implant

press

▶️ طريقة تشغيل المشروع
1️⃣ تثبيت المتطلبات

افتح Terminal واكتب:

pip install PyQt5
pip install Pillow
2️⃣ إنشاء قاعدة البيانات
python create_database.py
3️⃣ تشغيل النظام
python dashboard.py
👨‍💻 أعضاء الفريق

خالد عثمان

محمد حجازي

علي الخطيب

حسين الحسن

برهان باكير
