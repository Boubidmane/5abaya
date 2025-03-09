# 5abaya
# برنامج إدارة مكاتب المحامين | Gestionnaire de Cabinet d'Avocats
##### _Développé par [@Boubidmane](https://github.com/Boubidmane)_

<div dir="rtl">

## 🎯 نظرة عامة | Aperçu

تطبيق تلجرام متخصص لإدارة مكاتب المحامين في المغرب، يوفر واجهة سهلة الاستخدام باللغتين العربية والفرنسية لإدارة القضايا والعملاء والمواعيد.

</div>

## 🌟 Fonctionnalités Principales | الميزات الرئيسية

<div dir="rtl">

### 📋 إدارة القضايا
- إنشاء وتعديل وعرض سجلات القضايا
- تتبع تفاصيل القضية ومراحلها
- إدارة الملفات والوثائق المرتبطة
- تسجيل الرسوم والمدفوعات

### 👥 إدارة العملاء
- قاعدة بيانات شاملة للعملاء
- ربط العملاء بقضاياهم
- تتبع سجل التعاملات
- إدارة المواعيد والاتصالات

### ⚖️ إدارة الجلسات
- جدولة جلسات المحكمة
- نظام تذكير متقدم
- تسجيل النتائج والقرارات
- متابعة التأجيلات

</div>

## 🛠 Technologies Utilisées | التقنيات المستخدمة

- Python 3.9+
- python-telegram-bot 20.7
- MongoDB 6.0+
- Motor (MongoDB async driver)
- python-dotenv
- APScheduler

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Boubidmane/law-office-bot.git

# Navigate to project directory
cd law-office-bot

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
```

## ⚙️ Configuration | الإعداد

<div dir="rtl">

### متطلبات النظام
- Python 3.9 أو أحدث
- MongoDB 6.0 أو أحدث
- بوت تلجرام مع توكن صالح

### إعداد ملف .env
```env
TELEGRAM_BOT_TOKEN=your_bot_token_here
MONGODB_URI=mongodb://localhost:27017/law_office_db
TIMEZONE=Africa/Casablanca
DEFAULT_LANGUAGE=ar
```

</div>

## 🚀 Démarrage | التشغيل

```bash
# Start the bot
python main.py
```

## 📚 Structure du Projet | هيكل المشروع

```
law-office-bot/
├── main.py
├── config/
│   ├── __init__.py
│   └── settings.py
├── database/
│   ├── __init__.py
│   ├── connection.py
│   └── models/
├── handlers/
│   ├── __init__.py
│   ├── cases.py
│   ├── clients.py
│   └── ...
├── utils/
│   ├── __init__.py
│   └── notifications.py
├── locales/
│   ├── ar/
│   └── fr/
└── tests/
```

## 🔒 Sécurité | الأمان

<div dir="rtl">

- تشفير البيانات الحساسة
- نظام صلاحيات متعدد المستويات
- توثيق جميع العمليات
- نسخ احتياطي تلقائي

</div>

## 📝 Documentation | التوثيق

<div dir="rtl">

- [دليل المستخدم](docs/user-guide-ar.md)
- [دليل المطور](docs/developer-guide-ar.md)
- [الأسئلة الشائعة](docs/faq-ar.md)

</div>

## 🤝 Contribution | المساهمة

<div dir="rtl">

نرحب بمساهماتكم! يرجى قراءة [دليل المساهمة](CONTRIBUTING.md) للتعرف على كيفية المشاركة في تطوير المشروع.

</div>

## 📄 Licence | الترخيص

MIT License - See [LICENSE](LICENSE) for details

---

<div dir="rtl">

تم التحديث: 2025-03-09

</div>