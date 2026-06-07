<div align="center">

# 🤖 پروژه‌ی هوش مصنوعی — یادگیری ماشین و علم داده

یک مخزن آموزشی جامع و عملی که کل مسیر **علم داده** و **یادگیری ماشین** را پوشش می‌دهد — از مبانی NumPy تا شبکه‌های عصبی کانولوشنی و پروژه‌های واقعی.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)](https://keras.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](#-لایسنس)
[![Stars](https://img.shields.io/github/stars/TahaT80/AI?style=social)](https://github.com/TahaT80/AI/stargazers)
[![Forks](https://img.shields.io/github/forks/TahaT80/AI?style=social)](https://github.com/TahaT80/AI/network/members)

> *«هدف این مخزن، ارائه‌ی یک مسیر یادگیری ساختاریافته و end-to-end به کسانی‌ست که می‌خواهند از طریق مثال‌های عملی و قابل بازتولید، بر علم داده و یادگیری ماشین مسلط شوند.»*

</div>

---

> 🌐 **نسخه‌ی انگلیسی این فایل در [`README.md`](./README.md) موجود است.**

---

## 📑 فهرست مطالب
- [✨ معرفی](#-معرفی)
- [🎯 ویژگی‌ها](#-ویژگی‌ها)
- [🗂️ ساختار مخزن](#-ساختار-مخزن)
- [📚 نقشه‌ی راه آموزشی](#-نقشه‌ی-راه-آموزشی)
- [💻 تکنولوژی‌های استفاده‌شده](#-تکنولوژیهای-استفادهشده)
- [📊 دیتاست‌ها](#-دیتاستها)
- [⚙️ نصب و راه‌اندازی](#-نصب-و-راهاندازی)
- [🚀 اجرا](#-اجرا)
- [🤝 مشارکت](#-مشارکت)
- [📜 لایسنس](#-لایسنس)
- [📬 ارتباط با من](#-ارتباط-با-من)
- [⭐ حمایت از پروژه](#-حمایت-از-پروژه)
- [🙏 تشکر و قدردانی](#-تشکر-و-قدردانی)

---

## ✨ معرفی

این مخزن یک **مسیر آموزشی کامل** برای هوش مصنوعی، علم داده و یادگیری ماشین است. هر بخش مستقل است، به صورت پلکانی روی بخش قبلی ساخته می‌شود و پر از نوت‌بوک‌های Jupyter کامنت‌گذاری‌شده، دیتاست‌های واقعی و مینی‌پروژه‌های end-to-end است.

چه یک مبتدی باشید که تازه با آرایه‌های NumPy آشنا می‌شوید، چه یک پزوهشگر پیشرفته که می‌خواهید روی تصاویر CAPTCHA شبکه‌ی عصبی کانولوشنی آموزش دهید — برای هر سطحی نوت‌بوکی در اینجا وجود دارد.

---

## 🎯 ویژگی‌ها

- ✅ **نوت‌بوک‌های گام‌به‌گام Jupyter** — با کامنت‌های فارسی و انگلیسی، مناسب برای مبتدی‌ها.
- ✅ **دیتاست‌های واقعی** — Boston Housing، Iris، Diabetes، آب‌وهوا، قیمت رمزارز و...
- ✅ **پایپ‌لاین end-to-end** — پیش‌پردازش → مدل‌سازی → ارزیابی → دیپلوی (Dash).
- ✅ **ML کلاسیک + Deep Learning** — scikit-learn در کنار TensorFlow/Keras.
- ✅ **آمار به صورت اصولی** — آزمون‌های توصیفی و استنباطی (t-test، z-test، chi²، ANOVA، A/B testing، تست‌های نرمالیته).
- ✅ **بیش از ۱۵ مینی‌پروژه** — شامل استریم زنده‌ی قیمت ارز دیجیتال (نوبیتکس)، پیش‌بینی هوا، و تشخیص CAPTCHA.
- ✅ **ویژوالیزیشن تعاملی** — Matplotlib، Seaborn، Plotly و یک اپ وب Dash.

---

## 🗂️ ساختار مخزن

```
AI/
├── part0_datascience/        # مقدمه‌ای بر علم داده
├── part1_numpy/              # مبانی NumPy
├── part2_pandas/             # Pandas و داده‌کاوی
├── part3_EDA/                # تحلیل اکتشافی داده
│   ├── part1_Statistics/     # آمار توصیفی و استنباطی
│   └── part2_Visualization/  # Matplotlib، Plotly، Dash
├── part4_Machine Learning/   # هسته‌ی یادگیری ماشین
│   ├── 1_Process/            # پیش‌پردازش، توابع هزینه، رگولاریزیشن، ارزیابی
│   ├── 2_Supervision/        # الگوریتم‌های یادگیری نظارت‌شده
│   ├── 3_Unsupervised/       # الگوریتم‌های یادگیری نظارت‌نشده
│   └── 4_Noron/              # شبکه‌های عصبی (پرسپترون، CNN)
├── part7_project/            # پروژه‌های واقعی
└── README.md
```

---

## 📚 نقشه‌ی راه آموزشی

### 🟢 0️⃣ `part0_datascience` — مقدمه
- علم داده چیست؟ فرآیند کار، نقش‌ها و ابزارها.

### 🟢 1️⃣ `part1_numpy` — محاسبات عددی
- آرایه‌ها، Broadcasting، ایندکس‌گذاری، Slicing، عملیات برداری.
- مبانی جبر خطی، اعداد تصادفی، آمار.

### 🟢 2️⃣ `part2_pandas` — دستکاری داده
- مبانی `Series` و `DataFrame`.
- خواندن/نوشتن CSV، Excel، JSON.
- Merge، Join، Pivot، GroupBy و کار با داده‌های زمانی (Time Series).

### 🟡 3️⃣ `part3_EDA` — تحلیل اکتشافی داده
#### 📈 آمار
- **توصیفی:** گشتاورها، همبستگی، مقایسه‌ی توزیع‌ها.
- **استنباطی:** A/B Testing، T-Test، Z-Test، Mann-Whitney U Test، Chi-Square، تست‌های نرمالیته، ANOVA.

#### 🎨 ویژوالیزیشن
- **Matplotlib و Seaborn:** نمودارهای ایستا برای EDA.
- **Plotly:** نمودارهای تعاملی.
- **Dash:** ساخت اپ وب تحلیلی (`dash_full_app.py`).

### 🟠 4️⃣ `part4_Machine Learning` — هسته‌ی ML
#### 🔧 `1_Process` — پایپ‌لاین ML
- پیش‌پردازش و مهندسی ویژگی (Feature Engineering).
- توابع هزینه، شهود گرادیان کاهشی.
- رگرسیون چندجمله‌ای، **Ridge** و **Lasso**.
- گزارش طبقه‌بندی (Precision، Recall، F1).
- Cross-Validation و **GridSearchCV**.

#### 👨‍🏫 `2_Supervision` — یادگیری نظارت‌شده
| الگوریتم | نوت‌بوک |
|----------|---------|
| رگرسیون خطی | `2_1` → `2_4` |
| رگرسیون لجستیک | `3_1` → `3_3` |
| K-Nearest Neighbors | `4_1`، `4_2` (Imputation) |
| درخت تصمیم | `5_2` |
| Random Forest | `5_1`، `5_3` |
| ماشین بردار پشتیبان (SVM) | `6_1` |
| شبکه‌ی عصبی مصنوعی (ANN) | `7_1` |
| Naive Bayes | `8_1` |

#### 🔍 `3_Unsupervised` — یادگیری نظارت‌نشده
- **K-Means** (به همراه روش Elbow).
- **PCA** — کاهش بُعد.

#### 🧠 `4_Noron` — شبکه‌های عصبی و Deep Learning
- **Perceptron** — پیاده‌سازی از صفر و با Keras، مدل‌های ذخیره‌شده `.h5` / `.keras`.
- **شبکه‌های عصبی کانولوشنی (CNN)** — تشخیص CAPTCHA با دیتاست سفارشی، Encoder و مدل‌های آموزش‌دیده.

### 🔴 5️⃣ `part7_project` — پروژه‌های واقعی

| # | پروژه | حوزه |
|---|-------|------|
| 1 | بازبینی فرآیند Data Science | پایپ‌لاین E2E |
| 2 | پروژه‌ی اکتشافی | تحلیل |
| 3 | پروژه‌ی مدل‌سازی | ML |
| 4 | **استریم زنده‌ی قیمت ارز دیجیتال نوبیتکس** (`project_4_nobitex.ipynb`) | مالی / Streaming |
| 5 | **پیش‌بینی آب و هوا** (`weather.csv`، `weather.ipynb`) | سری زمانی |
| 6 | **طبقه‌بندی دیابت** | سلامت |
| 7 | **پیش‌بینی قیمت** (`prices.csv`) | رگرسیون |
| 8, 8.5 | مقایسه‌ی مدل‌ها | ML |
| 9 | مدل‌سازی پیشرفته | ML |
| 10 | پروژه‌ی Capstone | ML |
| 11, 12 | پروژه‌های عمیق | ML |
| 13 | **پروژه‌ی تصویر (CNN)** (`8865148.jpg`، `model_13.keras`) | بینایی کامپیوتر |
| 14 | **پروژه‌ی چند مدلی** (۴ نوت‌بوک، `model_0..3.h5`) | Deep Learning |
| 15 | **پروژه‌ی نهایی Capstone** (`project_15.ipynb`) | پایپ‌لاین کامل |

---

## 💻 تکنولوژی‌های استفاده‌شده

| دسته | ابزارها |
|------|---------|
| **زبان** | Python 3.8+ |
| **هسته** | NumPy, Pandas |
| **ویژوالیزیشن** | Matplotlib, Seaborn, Plotly, Dash |
| **ML کلاسیک** | scikit-learn |
| **Deep Learning** | TensorFlow, Keras |
| **آمار** | SciPy |
| **محیط** | Jupyter / VS Code |

---

## 📊 دیتاست‌ها

این مخزن با دیتاست‌های نمونه‌ی متنوعی عرضه می‌شود:

- 📺 `Advertising.csv` — رگرسیون هزینه‌ی تبلیغات در برابر فروش
- 🏠 `BostonHousing.csv` — پیش‌بینی قیمت خانه
- 🏥 `breastcancer_training.csv` — طبقه‌بندی سرطان
- 🩺 `diabetes.csv` — پیش‌بینی دیابت (در چندین پروژه استفاده شده)
- 🌸 `Iris.csv` — طبقه‌بندی چندکلاسه‌ی کلاسیک
- 💼 `Social_Network_Ads.csv` — طبقه‌بندی رفتار کاربران
- 🏘️ `property data.csv` — پیش‌پردازش داده‌های املاک
- ⚽ `soccer.csv` — تحلیل ورزشی
- 🌦️ `weather.csv` — پیش‌بینی سری زمانی
- 💰 `prices.csv` — داده‌های مالی

---

## ⚙️ نصب و راه‌اندازی

### 1️⃣ پیش‌نیازها
- **Python 3.8+** — [دانلود](https://www.python.org/downloads/)
- **Git** — [دانلود](https://git-scm.com/)
- (اختیاری) **VS Code** با افزونه‌ی *Jupyter*.

### 2️⃣ کلون کردن مخزن
```bash
git clone https://github.com/TahaT80/AI.git
cd AI
```

### 3️⃣ ساخت محیط مجازی (Virtual Environment)

**ویندوز (PowerShell):**
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

**لینوکس / مک:**
```bash
python -m venv venv
source venv/bin/activate
```

### 4️⃣ نصب وابستگی‌ها
```bash
pip install --upgrade pip
pip install numpy pandas matplotlib seaborn scikit-learn scipy plotly dash tensorflow jupyter
```

> 💡 **نکته:** اگر فقط به بخش ML کلاسیک نیاز دارید، می‌توانید TensorFlow را نصب نکنید:
> `pip install numpy pandas matplotlib seaborn scikit-learn scipy plotly dash jupyter`

---

## 🚀 اجرا

### گزینه‌ی ۱ — Jupyter Notebook
```bash
jupyter notebook
```
سپس به هر پوشه (`part1_numpy`، `part2_pandas` و...) بروید و نوت‌بوک‌ها را باز کنید.

### گزینه‌ی ۲ — VS Code
پوشه‌ی پروژه را در VS Code باز کنید و هر فایل `.ipynb` را اجرا کنید. در صورت نیاز، کرنل `venv` را انتخاب کنید.

### گزینه‌ی ۳ — اجرای اپ Dash
```bash
cd "part3_EDA/part2_Visualization/part2_matplotlib"
python dash_full_app.py
```

### گزینه‌ی ۴ — استریم زنده‌ی قیمت ارز دیجیتال
```bash
jupyter notebook part7_project/project_4_nobitex.ipynb
# همه‌ی سلول‌ها را اجرا کنید — قیمت لحظه‌ای USDT/IRT از نوبیتکس دریافت می‌شود
```

---

## 🤝 مشارکت

از مشارکت شما **استقبال می‌کنیم** — چه رفع باگ، چه نوت‌بوک جدید، توضیحات بهتر یا دیتاست تازه.

1. 🍴 مخزن را **Fork** کنید.
2. 🌿 یک شاخه‌ی جدید بسازید: `git checkout -b feature/amazing-notebook`
3. ✅ تغییرات را اعمال کنید و **آن‌ها را end-to-end تست** کنید.
4. 📝 **PEP 8** را رعایت کنید و برای توضیح کدها کامنت/Markdown اضافه کنید.
5. 💬 Commit کنید: `git commit -m "Add K-Means elbow-method notebook"`
6. 📤 Push کنید: `git push origin feature/amazing-notebook`
7. 🔁 یک **Pull Request** باز کنید و توضیح دهید چه چیزی اضافه کرده‌اید.

---

## 📜 لایسنس

این پروژه تحت **لایسنس MIT** منتشر شده است — برای جزئیات فایل `LICENSE` را ببینید.  
استفاده، تغییر و توزیع مجدد کد آزاد است، به شرط آن‌که کپی‌رایت اصلی حفظ شود.

> اگر از این پروژه Fork می‌گیرید یا بخش قابل‌توجهی از آن را استفاده می‌کنید، یک اعتبار یا لینک به این مخزن، بسیار قابل‌قدردانی است. 💙

---

## 📬 ارتباط با من

**Taha Tandashtiaran** (طاها)
- 📧 ایمیل: [1380.tadas@gmail.com](mailto:1380.tadas@gmail.com)
- 🐙 گیت‌هاب: [@TahaT80](https://github.com/TahaT80)

برای **سؤالات، پیشنهادات، همکاری یا گزارش باگ** خوش‌حال می‌شوم پیام بدهید.

---

## ⭐ حمایت از پروژه

اگر این مخزن به یادگیری شما کمک کرد، لطفاً با یکی از این کارها از آن حمایت کنید:

- ⭐ **Star** دادن به مخزن
- 🍴 **Fork** کردن
- 🐦 به اشتراک‌گذاری با دوستان
- 🐛 باز کردن **Issue** برای باگ یا پیشنهاد بهبود

حمایت شما باعث زنده ماندن پروژه و انگیزه‌ی توسعه‌ی بیشتر می‌شود! 🚀

---

## 🙏 تشکر و قدردانی

- از جامعه‌های **scikit-learn**، **TensorFlow**، **Pandas** و **NumPy** برای ابزارهای متن‌باز فوق‌العاده.
- از تیم **Plotly و Dash** برای لذت‌بخش کردن ویژوالیزیشن داده.
- از همه‌ی **مشارکت‌کنندگان** و یادگیرندگانی که از این محتوا استفاده می‌کنند، بهبودش می‌دهند و به اشتراک می‌گذارند.
- این مخزن، ادای احترامی به روح متن‌باز است. 💙

---

<div align="center">
ساخته شده با ❤️ و مقدار زیادی ☕ توسط <a href="https://github.com/TahaT80">TahaT80</a>
</div>
