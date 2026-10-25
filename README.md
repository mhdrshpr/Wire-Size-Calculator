# ⚡ محاسبه‌گر تابلو برق و سایزینگ کابل | Switchboard & Cable Sizing Calculator

[**فارسی (Persian)**](#-فارسی) • [**English**](#-english) • [**Français**](#-français) • [**العربية**](#-العربية)

---

## 🇮🇷 فارسی

### معرفی
محاسبه‌گر تابلو برق صنعتی یک وب‌اپلیکیشن کلاینت-ساید، سریع، آفلاین و بدون نیاز به نصب است که بر مبنای استاندارد بین‌المللی **IEC 60364** طراحی شده است. این نرم‌افزار امکان سایزینگ کابل‌های ورودی و خروجی، بررسی افت ولتاژ، بالانس هوشمند فازها، محاسبه فازوری جریان نول و انتخاب کلید حفاظتی را برای مهندسان برق و تابلوسازان فراهم می‌آورد.

### ویژگی‌های کلیدی
- **پشتیبانی از ۴ زبان:** فارسی، انگلیسی، فرانسوی و عربی با تشخیص خودکار جهت صفحه (RTL/LTR) و مودال انتخاب زبان در ابتدای ورود.
- **نمایش سایز کابل به صورت حداقل و پیشنهادی:** حداقل مقطع بر اساس جریان مجاز ($I_z$) و مقطع پیشنهادی با حاشیه اطمینان مهندسی برای مدیریت شوک استارت بارها و افت ولتاژ کمتر.
- **سایزینگ مجزای هر مصرف‌کننده:** محاسبه اختصاصی کابل مورد نیاز هر المان بر مبنای متراژ کابل اختصاصی آن.
- **حالت ساده و پیشرفته (Simple / Advanced):** امکان پنهان‌سازی پارامترهای پیشرفته (دما، روش نصب، ضرایب هم‌آرایی، کسینوس فی، راندمان، $k_s$ و $k_d$) برای تسریع کار با مقادیر امن استاندارد.
- **ردیف‌بندی در تابلو برق:** گروه‌بندی مصرف‌کننده‌ها بر اساس ردیف تابلو و تولید جدول تجمیعی توان (kW)، جریان (A) و طول کل کابل (متر).
- **بالانس خودکار فازها و جریان برداری نول:** الگوریتم بهینه‌سازی حریصانه برای کاهش عدم تعادل فازها و جمع برداری فازورهای جریان برای محاسبه نول.
- **انتخاب هوشمند کلید اصلی:** انتخاب رنج نامی کلیدهای مینیاتوری (MCB) و اتوماتیک (MCCB) تا رنج 630A و تیپ منحنی قطع (B، C، D).
- **گزارش چاپی و PDF مهندسی:** استایل اختصاصی پرینت در قطع A4 با جدول‌بندی دقیق و تاریخ روز.
- **پاک‌سازی سریع و تم دوگانه:** دکمه ریست سریع جدول و امکان انتخاب تم تاریک یا روشن با ذخیره در حافظه مرورگر.

### نحوه اجرا
1. کلون کردن مخزن:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
2. باز کردن مستقیم فایل `index.html` در مرورگر یا میزبانی با یک کلیک روی **GitHub Pages**.

---

## 🇬🇧 English

### Overview
The Industrial Switchboard & Cable Sizing Calculator is a lightweight, standalone, fully client-side PWA designed in compliance with the **IEC 60364** international standard. It assists electrical engineers, facility designers, and switchboard builders in calculating circuit currents, sizing main and outgoing conductors, checking voltage drops, balancing phase loads, and selecting circuit breakers.

### Key Features
- **4 Language Support:** Persian, English, French, and Arabic with full RTL/LTR bidirectional support and an initial language selection modal.
- **Minimum & Recommended Cable Sizing:** Computes the code-compliant minimum section ($I_z$) and a recommended section with an engineering safety margin for motor starting and voltage drop mitigation.
- **Per-Consumer Cable Sizing:** Dedicated cable calculation for each load based on individual cable lengths.
- **Simple / Advanced Mode Toggle:** Fast mode bypasses complex derating parameters (temperature, installation method, grouping, $\cos\varphi$, $\eta$, $k_s$, $k_d$) using safe standardized values.
- **Switchboard Row Classification:** Groups loads by board rows/feeders and aggregates total active power (kW), current (A), and total cable run length (m).
- **Phase Balancing & Vector Neutral Phasor Calculation:** Greedy optimization algorithm for minimum phase unbalance ($Unbalance\%$) and exact vector summation for neutral current.
- **Main Breaker Selection:** Standard rating selection for MCB and MCCB breakers up to 630A with curve tripping detection (Type B, C, D).
- **Engineering PDF & Print Layout:** Professional A4 printing stylesheet with clean tables, metadata, and local date.
- **Clear All & Dark/Light Themes:** One-click table reset and persistent theme toggling.

### How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
2. Open `index.html` directly in any web browser or deploy directly to **GitHub Pages**.

---

## 🇫🇷 Français

### Présentation
Le Calculateur de Tableau Électrique Industriel est une application web progressive (PWA) autonome, rapide et sans dépendance serveur, conçue selon la norme internationale **IEC 60364**. Elle permet aux ingénieurs électriciens et tableautiers d'évaluer les courants de charge, de dimensionner les câbles d'arrivée et de départs, de contrôler les chutes de tension, d'équilibrer les phases et de choisir le disjoncteur général approprié.

### Caractéristiques Principales
- **Support de 4 Langues :** Français, Anglais, Persan et Arabe avec prise en charge complète LTR/RTL et modale de sélection de langue à l'ouverture.
- **Dimensionnement de Câble (Minimal & Conseillé) :** Calcul de la section réglementaire minimale ($I_z$) et proposition d'une section supérieure avec marge de sécurité thermique et limitation de la chute de tension.
- **Section Individuelle par Récepteur :** Dimensionnement dédié pour chaque appareil selon sa longueur propre de câble.
- **Mode Simple et Mode Avancé :** Le mode simple masque les paramètres complexes (température, pose, groupement, $\cos\varphi$, $\eta$, $k_s$, $k_d$) pour une saisie rapide avec des valeurs standardisées.
- **Organisation par Rangée de Tableau :** Regroupement par rangée ou départ avec synthèse de puissance totale (kW), courant cumulé (A) et métrage total de câble (m).
- **Équilibrage de Phase et Calcul Vectoriel du Neutre :** Algorithme d'équilibrage minimisant le déséquilibre entre phases et somme vectorielle des courants de phase pour le calcul exact du neutre.
- **Sélection du Disjoncteur Général :** Choix automatique du calibre MCB ou MCCB jusqu'à 630A avec courbe de déclenchement (B, C, D) selon la proportion de moteurs.
- **Rapport d'Impression et PDF :** Mise en page A4 optimisée avec tableaux techniques contrastés et date du jour.
- **Effacement Rapide et Thèmes Clair/Sombre :** Bouton de réinitialisation sécurisé et mémorisation du thème d'affichage.

### Utilisation
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
2. Ouvrez `index.html` dans votre navigateur ou activez **GitHub Pages** dans les paramètres du dépôt.

---

## 🇸🇦 العربية

### نظرة عامة
حاسبة اللوحات الكهربائية الصناعية وتحديد مقاطع الكابلات هي تطبيق ويب مستقل وسريع يعمل بالكامل على متصفح المستخدم دون الحاجة إلى تثبيت أي برامج أو خوادم، وفقاً لمتطلبات المعيار الدولي **IEC 60364**. تتيح للمهندسين ومصممي التمديدات وفنيي تصنيع اللوحات حساب تيارات الدوائر، ومقاطع كابلات التغذية والأحمال، والتحقق من هبوط الجهد، وموازنة الأطوار الثلاثة، واختيار القواطع الوقائية.

### أبرز المميزات
- **دعم 4 لغات:** العربية، الفارسية، الإنجليزية، والفرنسية مع ضبط اتجاه النصوص (RTL/LTR) ونافذة منبثقة (Modal) لاختيار اللغة فور الدخول.
- **تحديد مقطع الكابل (الحد الأدنى والمقترح):** حساب المقطع الأدنى المسموح به حرارياً ($I_z$) مع تقديم مقطع مقترح أعلى بدرجة كهامش أمان هندسي لبدء حركة المحركات وتقليل هبوط الجهد.
- **مقطع كابل مخصص لكل مستهلك:** حساب مقطع الكابل الخاص بكل حمل على حدة اعتماداً على طول مساره المستقل.
- **الوضع المبسط والمتقدم (Simple / Advanced):** إمكانية إخفاء المعايير التفصيلية (الحرارة، طريقة التمديد، معامل التجميع، معامل القدرة، الكفاءة، معاملي التزامن والطلب) لتسريع الحسابات بقيم قياسية معتمدة.
- **تصنيف صفوف اللوحة الكهربائية:** تجميع الأحمال حسب الصف أو القاطع الفرعي وعرض جدول تراكمي للقدرة (kW)، التيار (A)، وإجمالي طول الكابلات (متر).
- **توازن الأطوار والجمع الاتجاهي لتيار الحيادي:** خوارزمية ذكية لتوزيع الأحمال أحادية وثنائية الطور للوصول لأقل نسبة عدم اتزان، وجمع طوري دقيق لتيار خط الحيادي (Neutral).
- **اختيار القاطع الوقائي الرئيسي:** تحديد السعة الاسمية القياسية لقواطع MCB و MCCB حتى 630A ونوع منحنى الفصل المغناطيسي (B و C و D).
- **تقرير طباعة وتصدير PDF:** تصميم مخصص للطباعة على ورق A4 بجداول هندسية واضحة وتاريخ التقرير.
- **مسح سريع وثيم داكن/فاتح:** زر لإعادة تعيين الجدول بضغطة واحدة، وحفظ خيارات المظهر واللغة محلياً.

### طريقة التشغيل
1. استنساخ المستودع:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
2. فتح ملف `index.html` مباشرة عبر أي متصفح، أو نشره عبر **GitHub Pages**.

---

## 📐 مبانی فرمول‌ها / Formulation Summary

1. **Current Equations:**
   - Single-Phase (230V): $I = \frac{P}{V_{ph} \cdot \cos\varphi \cdot \eta}$
   - Two-Phase (400V): $I = \frac{P}{V_{LL} \cdot \cos\varphi \cdot \eta}$
   - Balanced Three-Phase (400V): $I = \frac{P}{\sqrt{3} \cdot V_{LL} \cdot \cos\varphi \cdot \eta}$

2. **Voltage Drop:**
   $$\Delta U\% = \frac{b \cdot I \cdot L \cdot (R \cdot \cos\varphi + X \cdot \sin\varphi)}{V_{base}} \times 100$$
   *(b = 1 for 3-Phase, b = 2 for 1-Phase; Cu: $\rho = 0.0225\ \Omega\cdot\text{mm}^2/\text{m}$, Al: $\rho = 0.034\ \Omega\cdot\text{mm}^2/\text{m}$, $X = 0.08\ \Omega/\text{km}$)*

3. **Ampacity Condition:**
   $$I_z' = I_z \times (k_t \times k_m \times k_g) \ge I_n \ge I_B \quad \text{and} \quad \Delta U\% \le \Delta U_{allow}\%$$

---

## 👤 توسعه‌دهنده / Author

- **مهدیار شاهپری (Mahdyar Shahpari)**
- Email: [1shpr12@gmail.com](mailto:1shpr12@gmail.com)
- Telegram: [@mh2pr](https://t.me/mh2pr)
- Instagram: [@mhdr.shpr](https://instagram.com/mhdr.shpr)
- LinkedIn: [mhdrshpr](https://linkedin.com/in/mhdrshpr)
