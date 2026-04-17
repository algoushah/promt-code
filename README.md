# ✦ ProMT — by Ayoub

> **منصة شخصية لتحويل الأفكار إلى كود فرونت إند احترافي باستخدام الذكاء الاصطناعي**

![ProMT Banner](https://ik.imagekit.io/imgayoub/LOGO/ayoubpw.png?updatedAt=1774899292962)

---

## 🚀 ما هو ProMT؟

**ProMT** هي منصة ويب شخصية تتيح لك كتابة فكرة بسيطة بالعربية أو الإنجليزية، وتحصل فوراً على كود HTML/CSS/JavaScript كامل واحترافي جاهز للنشر — مدعوم بأكثر من **20 نموذج ذكاء اصطناعي** عبر [OpenRouter](https://openrouter.ai).

---

## ✨ المميزات

- 🧠 **20+ نموذج AI** — Claude، GPT-4o، Gemini، Llama، DeepSeek وغيرها
- 🆓 **13 نموذج مجاني** — بدون أي تكلفة مع مفتاح OpenRouter
- ⚡ **Auto Free Router** — يختار أفضل نموذج مجاني تلقائياً
- 🌊 **Streaming** — الكود يظهر حرفاً بحرف أثناء التوليد
- 👁️ **معاينة فورية** — افتح الكود في تاب جديد بزرارة واحدة
- 📋 **نسخ سريع** — انسخ الكود بضغطة واحدة
- 📱 **Mobile First** — تصميم متجاوب يعمل على كل الأجهزة
- 🌙 **Dark Theme** — واجهة داكنة بالكامل مريحة للعين
- 🕐 **ساعة حية** — توقيت فيينا في الهيدر
- ✈️ **تكامل تيليجرام** — أرسل النتائج مباشرة لبوت تيليجرام
- 💾 **حفظ محلي** — المفاتيح محفوظة في localStorage

---

## 🤖 النماذج المدعومة

### 💰 نماذج مدفوعة
| النموذج | الشركة |
|---|---|
| Claude Sonnet 4.5 | Anthropic |
| Claude Opus 4 | Anthropic |
| GPT-4o | OpenAI |
| GPT-4o mini | OpenAI |
| Gemini 2.0 Flash | Google |
| DeepSeek V3 | DeepSeek |
| Mistral Large | Mistral |

### 🆓 نماذج مجانية (بدون تكلفة)
| النموذج | Context | مميزات |
|---|---|---|
| ⚡ Auto Free Router | 200K | يختار تلقائياً |
| Qwen3 Coder 480B | 262K | أفضل للكود |
| Gemma 4 31B | 262K | Vision + Tools |
| NVIDIA Nemotron 120B | 262K | Tools |
| GPT OSS 120B | 131K | Tools |
| GPT OSS 20B | 131K | Tools |
| Llama 3.3 70B | 66K | General |
| GLM 4.5 Air | 131K | Tools |
| Gemma 3 27B | 131K | Vision |
| Trinity Large | 131K | Tools |
| Nemotron Nano 12B | 128K | Vision + Tools |
| MiniMax M2.5 | 197K | Tools |
| Hermes 3 405B | 131K | General |

> ⚠️ النماذج المجانية لها حد **200 طلب/يوم** و**20 طلب/دقيقة**

---

## ⚙️ الإعداد والتشغيل

### 1️⃣ احصل على مفتاح OpenRouter
```
https://openrouter.ai/keys
```
> لا يحتاج بطاقة ائتمانية للنماذج المجانية ✅

### 2️⃣ شغّل الملف
```bash
# بدون سيرفر — افتح مباشرة في المتصفح
open prompt-enhancer.html

# أو عبر سيرفر محلي
npx serve .
python3 -m http.server 8080
```

### 3️⃣ أدخل المفتاح
افتح الموقع ← ستظهر نافذة الإعداد تلقائياً ← أدخل مفتاح OpenRouter ← احفظ

---

## ✈️ ربط تيليجرام

أرسل نتائج الكود مباشرة لحساب تيليجرام أو قناة أو مجموعة.

### الإعداد:

**1. أنشئ بوتاً جديداً:**
```
افتح @BotFather على تيليجرام
أرسل: /newbot
اتبع الخطوات واحفظ التوكن
```

**2. احصل على Chat ID:**
```
افتح البوت وأرسل له أي رسالة
ثم افتح في المتصفح:
https://api.telegram.org/botTOKEN/getUpdates
```
ابحث عن `"chat":{"id": 123456789}` — هذا هو Chat ID

**3. أدخل البيانات في ProMT:**
- اضغط أيقونة ✈️ في الهيدر
- أدخل Bot Token و Chat ID
- اضغط "اختبار الاتصال"

**4. الإرسال التلقائي (اختياري):**
فعّل خيار "إرسال تلقائي بعد كل توليد" وكل نتيجة ستُرسل لتيليجرام فوراً 🚀

---

## 🛠️ التقنيات المستخدمة

| التقنية | الاستخدام |
|---|---|
| `HTML5` | هيكل الصفحة |
| `CSS3` + Variables | تصميم متغير ومتجاوب |
| `Vanilla JS` | منطق التطبيق |
| `OpenRouter API` | الوصول لنماذج AI |
| `Telegram Bot API` | إرسال النتائج |
| `Fetch Streaming` | عرض الكود لحظياً |
| `localStorage` | حفظ المفاتيح محلياً |
| `Google Fonts` | Noto Kufi Arabic + Syne + IBM Plex Mono |
| `ImageKit` | استضافة اللوغو |

---

## ⌨️ اختصارات لوحة المفاتيح

| الاختصار | الوظيفة |
|---|---|
| `Ctrl + Enter` | توليد الكود |
| `Escape` | إغلاق النافذة |

---

## 🗂️ هيكل المشروع

```
ProMT/
│
├── 📄 prompt-enhancer.html    # الملف الرئيسي (all-in-one)
├── 📝 README.md               # هذا الملف
└── 📦 (لا اعتماديات خارجية)
```

> المشروع ملف HTML واحد فقط — لا npm، لا build، لا framework 🎯

---

## 🔒 الخصوصية والأمان

- 🔑 المفاتيح محفوظة **محلياً فقط** في متصفحك (`localStorage`)
- 🚫 لا يوجد سيرفر خلفي — كل شيء يعمل من المتصفح مباشرة
- 📡 الطلبات ترسل مباشرة لـ OpenRouter API

---

## 🌐 النشر

### GitHub Pages
```bash
git init
git add .
git commit -m "🚀 init ProMT"
git branch -M main
git remote add origin https://github.com/USERNAME/promt.git
git push -u origin main
# فعّل GitHub Pages من Settings → Pages → main branch
```

### Vercel
```bash
npx vercel --prod
```

### Cloudflare Pages
```bash
# ارفع الملف مباشرة من Dashboard
# أو اربط GitHub repo
```

---

## 📸 لقطات الشاشة

> الواجهة الرئيسية — تصميم داكن مع ساعة فيينا وشعار ProMT

---

## 📄 الترخيص

هذا المشروع شخصي خاص بـ **Ayoub** — [ayoub.pw](https://ayoub.pw)

---

<div align="center">

**صُنع بـ ❤️ في فيينا 🇦🇹**

[![ayoub.pw](https://img.shields.io/badge/ayoub.pw-000000?style=for-the-badge&logo=google-chrome&logoColor=00e5ff)](https://ayoub.pw)
[![OpenRouter](https://img.shields.io/badge/OpenRouter-6366f1?style=for-the-badge&logo=openai&logoColor=white)](https://openrouter.ai)
[![Telegram](https://img.shields.io/badge/Telegram_Bot-2AABEE?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/BotFather)

</div>
