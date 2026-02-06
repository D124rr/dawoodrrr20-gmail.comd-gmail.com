
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8" />
    <title>تعليم صيانة الكمبيوتر - داود الشريحي</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <style>
        body {
            margin: 0;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
            background: #f5f5f5;
            color: #222;
        }
        header {
            background: #0f172a;
            color: #fff;
            padding: 15px 20px;
            position: sticky;
            top: 0;
            z-index: 10;
        }
        header .brand {
            font-size: 20px;
            font-weight: 700;
        }
        nav {
            margin-top: 10px;
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            font-size: 14px;
        }
        nav a {
            color: #e5e7eb;
            text-decoration: none;
            padding: 6px 10px;
            border-radius: 999px;
            border: 1px solid #1f2937;
        }
        nav a:hover {
            background: #1f2937;
        }
        .hero {
            padding: 40px 20px;
            text-align: center;
            background: linear-gradient(135deg, #0f172a, #1e293b);
            color: #fff;
        }
        .hero h1 {
            margin: 0 0 15px;
            font-size: 26px;
        }
        .hero p {
            margin: 0 0 20px;
            line-height: 1.7;
        }
        .hero .btn-primary {
            display: inline-block;
            padding: 10px 20px;
            background: #22c55e;
            color: #0f172a;
            text-decoration: none;
            border-radius: 999px;
            font-weight: 600;
        }
        .hero .btn-primary:hover {
            background: #16a34a;
        }
        .section {
            padding: 30px 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        .section h2 {
            margin-top: 0;
            margin-bottom: 15px;
            font-size: 22px;
            color: #0f172a;
        }
        .grid {
            display: grid;
            gap: 15px;
        }
        @media (min-width: 768px) {
            .grid-2 {
                grid-template-columns: repeat(2, minmax(0, 1fr));
            }
            .grid-3 {
                grid-template-columns: repeat(3, minmax(0, 1fr));
            }
        }
        .card {
            background: #fff;
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 2px 6px rgba(15, 23, 42, 0.08);
        }
        .card h3 {
            margin-top: 0;
            margin-bottom: 8px;
            font-size: 18px;
            color: #111827;
        }
        .card ul {
            margin: 0;
            padding-right: 18px;
            font-size: 14px;
            line-height: 1.8;
        }
        .card ul li {
            margin-bottom: 4px;
        }
        .contact-box {
            background: #0f172a;
            color: #e5e7eb;
            border-radius: 12px;
            padding: 20px;
        }
        .contact-box p {
            margin: 6px 0;
        }
        .contact-label {
            font-weight: 600;
            color: #a5b4fc;
        }
        footer {
            text-align: center;
            padding: 15px;
            font-size: 13px;
            color: #6b7280;
        }
    </style>
</head>
<body>

<header>
    <div class="brand">تعليم صيانة الكمبيوتر - داود الشريحي</div>
    <nav>
        <a href="#home">الرئيسية</a>
        <a href="#lessons">الدروس</a>
        <a href="#articles">المقالات</a>
        <a href="#about">عن المعلّم</a>
        <a href="#contact">اتصل بنا</a>
    </nav>
</header>

<section class="hero" id="home">
    <h1>تعليم صيانة الكمبيوتر من الصفر حتى الاحتراف</h1>
    <p>
        تعلّم خطوة بخطوة كيفية تشخيص الأعطال، إصلاح الأجهزة، التعامل مع أنظمة التشغيل،
        وتسريع أداء الكمبيوتر واللابتوب بأسلوب عملي وواضح.
    </p>
    <a href="#lessons" class="btn-primary">ابدأ التعلم الآن</a>
</section>

<section class="section" id="lessons">
    <h2>دروس صيانة الكمبيوتر</h2>
    <div class="grid grid-2">
        <div class="card">
            <h3>تشخيص الأعطال</h3>
            <ul>
                <li>معرفة سبب المشكلة من الأعراض</li>
                <li>فحص الحرارة ومراقبة المراوح</li>
                <li>فحص الرامات والأخطاء الشائعة</li>
                <li>فحص الهارد والتأكد من سلامته</li>
                <li>فحص الباور ومشاكل التشغيل</li>
                <li>قراءة رسائل الخطأ وتحليلها</li>
            </ul>
        </div>
        <div class="card">
            <h3>صيانة الهاردوير</h3>
            <ul>
                <li>تنظيف الجهاز من الداخل والخارج</li>
                <li>تغيير المعجون الحراري للمعالج</li>
                <li>تركيب وتغيير الرامات</li>
                <li>استبدال الهارد وترقيته إلى SSD</li>
                <li>صيانة المراوح وتنظيفها</li>
                <li>أساسيات صيانة اللابتوب</li>
            </ul>
        </div>
        <div class="card">
            <h3>صيانة السوفتوير</h3>
            <ul>
                <li>إصلاح مشاكل الإقلاع</li>
                <li>حل مشكلة الشاشة الزرقاء</li>
                <li>إصلاح تعريفات الأجهزة</li>
                <li>إزالة الفيروسات والبرامج الضارة</li>
                <li>تسريع النظام وتحسين الأداء</li>
            </ul>
        </div>
        <div class="card">
            <h3>الفورمات والويندوز</h3>
            <ul>
                <li>تجهيز USB إقلاع للويندوز</li>
                <li>الدخول إلى BIOS/UEFI وضبط الإقلاع</li>
                <li>تثبيت ويندوز خطوة بخطوة</li>
                <li>تثبيت التعريفات الأساسية</li>
                <li>البرامج الضرورية بعد الفورمات</li>
            </ul>
        </div>
        <div class="card">
            <h3>أدوات الصيانة</h3>
            <ul>
                <li>أفضل أدوات الفك والتركيب</li>
                <li>برامج فحص الهارد والرامات</li>
                <li>برامج مراقبة الحرارة</li>
                <li>برامج الحماية الموثوقة</li>
                <li>أدوات النسخ الاحتياطي والاستعادة</li>
            </ul>
        </div>
    </div>
</section>

<section class="section" id="articles">
    <h2>مقالات ونصائح</h2>
    <div class="grid grid-3">
        <div class="card">
            <h3>أفضل 10 برامج لصيانة الكمبيوتر</h3>
            <p style="font-size:14px; line-height:1.8;">
                مجموعة من البرامج المجانية والاحترافية لفحص الجهاز، تنظيف الملفات المؤقتة،
                مراقبة الحرارة، وحل المشاكل الشائعة.
            </p>
        </div>
        <div class="card">
            <h3>كيف تحمي جهازك من الفيروسات</h3>
            <p style="font-size:14px; line-height:1.8;">
                نصائح عملية لاختيار برنامج حماية مناسب، وتجنّب الروابط والملفات المشبوهة،
                وأهمية التحديثات الدورية.
            </p>
        </div>
        <div class="card">
            <h3>لماذا يصبح الكمبيوتر بطيئًا؟</h3>
            <p style="font-size:14px; line-height:1.8;">
                أهم الأسباب التي تؤدي لبطء الجهاز، من الهارد والرامات إلى البرامج الثقيلة،
                وكيفية معالجة كل سبب.
            </p>
        </div>
        <div class="card">
            <h3>الفرق بين SSD و HDD</h3>
            <p style="font-size:14px; line-height:1.8;">
                مقارنة بين الأقراص التقليدية والـ SSD من حيث السرعة، العمر، والاستخدام الأنسب
                لكل نوع.
            </p>
        </div>
        <div class="card">
            <h3>نصائح لإطالة عمر اللابتوب</h3>
            <p style="font-size:14px; line-height:1.8;">
                كيفية التعامل الصحيح مع البطارية، التهوية، الشحن، والتنظيف للحفاظ على أداء
                اللابتوب لأطول فترة ممكنة.
            </p>
        </div>
    </div>
</section>

<section class="section" id="about">
    <h2>عن المعلّم</h2>
    <div class="card">
        <p style="line-height:1.9; font-size:15px;">
            أنا داود الشريحي، فني محترف في صيانة الكمبيوتر والأنظمة. أقدّم خبرتي في هذا الموقع
            لتعليم صيانة الكمبيوتر بشكل مبسّط وواضح، يناسب المبتدئين ومن يريد تطوير نفسه
            في مجال الصيانة.
        </p>
        <p style="line-height:1.9; font-size:15px;">
            أمتلك خبرة عملية في تشخيص الأعطال، إصلاح الأجهزة المكتبية واللابتوبات، التعامل
            مع أنظمة التشغيل، وضبط الإعدادات المتقدمة مثل BIOS، بالإضافة إلى تنظيم خطوات
            العمل بشكل منهجي وواضح.
        </p>
        <p style="line-height:1.9; font-size:15px;">
            هدفي أن أساعدك على فهم الصيانة بثقة، وأن تكون قادرًا على حل المشاكل بنفسك
            خطوة بخطوة.
        </p>
    </div>
</section>

<section class="section" id="contact">
    <h2>اتصل بنا</h2>
    <div class="contact-box">
        <p>
            يسعدني تواصلك في أي وقت للاستفسارات أو طلب المساعدة في صيانة الكمبيوتر
            أو الدروس التعليمية.
        </p>
        <p>
            <span class="contact-label">📱 واتساب / جوال:</span>
            ٠٥٧١٤٩٩٥٥٤
        </p>
        <p>
            <span class="contact-label">📧 البريد الإلكتروني:</span>
            Dawoodrrr20@gmail.com
        </p>
        <p>
            <span class="contact-label">📍 الموقع:</span>
            الدمام – المملكة العربية السعودية
        </p>
    </div>
</section>

<footer>
    © جميع الحقوق محفوظة لـ داود الشريحي – تعليم صيانة الكمبيوتر
</footer>

</body>
</html>
