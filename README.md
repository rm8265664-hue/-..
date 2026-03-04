<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بحث: التغيرات المناخية</title>
    <!-- استدعاء خط عربي جميل من جوجل -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        /* إعدادات عامة */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Cairo', sans-serif;
            color: #fff;
            line-height: 1.8;
            /* خلفية كوكب الأرض */
            background: url('https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=2072&auto=format&fit=crop') no-repeat center center fixed;
            background-size: cover;
            overflow-x: hidden;
        }

        /* طبقة تعتيم فوق الخلفية لجعل النص مقروءاً */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(10, 25, 47, 0.85); /* لون أزرق غامق شفاف */
            z-index: -1;
        }

        /* حاوية المحتوى الرئيسية */
        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 40px;
            background: rgba(255, 255, 255, 0.05); /* تأثير الزجاج */
            backdrop-filter: blur(10px);
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 0 30px rgba(0, 255, 128, 0.1);
        }

        /* العناوين */
        h1 {
            text-align: center;
            font-size: 2.5rem;
            color: #4CAF50; /* أخضر فاتح */
            margin-bottom: 30px;
            text-shadow: 0 0 10px rgba(76, 175, 80, 0.5);
        }

        h2 {
            color: #81D4FA; /* أزرق سماوي */
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 10px;
            margin-top: 40px;
            margin-bottom: 20px;
            font-size: 1.8rem;
        }

        h3 {
            color: #fff;
            margin-top: 20px;
            font-size: 1.3rem;
        }

        p {
            margin-bottom: 15px;
            font-size: 1.1rem;
        }

        /* القوائم */
        ul {
            list-style-type: none;
            padding-right: 20px;
        }

        ul li {
            position: relative;
            margin-bottom: 10px;
            padding-right: 25px;
        }

        ul li::before {
            content: '🌱';
            position: absolute;
            right: 0;
            top: 2px;
        }

        /* قسم المعلومات الغريبة */
        .fun-facts {
            background: rgba(76, 175, 80, 0.2);
            border-right: 5px solid #4CAF50;
            padding: 20px;
            margin: 30px 0;
            border-radius: 8px;
        }

        .fun-facts h3 {
            color: #4CAF50;
            margin-top: 0;
        }

        /* الخاتمة */
        .conclusion {
            background: rgba(0, 0, 0, 0.3);
            padding: 20px;
            border-radius: 10px;
            margin-top: 40px;
            text-align: center;
            font-weight: bold;
        }

        /* تأثيرات الحركة */
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }

        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* التجاوب مع الشاشات الصغيرة */
        @media (max-width: 600px) {
            .container {
                margin: 10px;
                padding: 20px;
            }
            h1 {
                font-size: 1.8rem;
            }
            h2 {
                font-size: 1.4rem;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>التغيرات المناخية: تحدي عصرنا</h1>

        <div class="fade-in">
            <p>تُعد التغيرات المناخية من أخطر المشكلات التي تواجه العالم في العصر الحديث. فقد شهد كوكب الأرض في السنوات الأخيرة ارتفاعًا ملحوظًا في درجات الحرارة، وتغيرًا في أنماط الأمطار، وزيادة في الكوارث الطبيعية مثل الأعاصير والفيضانات. ويرتبط هذا التغير بشكل أساسي بالأنشطة البشرية، مما يجعل الإنسان مسؤولًا عن جزء كبير من المشكلة، وفي نفس الوقت قادرًا على المساهمة في الحل.</p>
        </div>

        <div class="fade-in">
            <h2>أولًا: ما المقصود بالتغيرات المناخية؟</h2>
            <p>التغيرات المناخية هي تغيرات طويلة المدى في درجات الحرارة وأنماط الطقس على سطح الأرض. وقد تحدث هذه التغيرات طبيعيًا، لكن منذ القرن التاسع عشر بدأت الأنشطة البشرية تؤثر بشكل واضح على المناخ، خاصة بعد الثورة الصناعية.</p>
        </div>

        <div class="fade-in">
            <h2>ثانيًا: أسباب التغيرات المناخية</h2>
            <ul>
                <li><strong>حرق الوقود الأحفوري:</strong> مثل الفحم والبترول والغاز الطبيعي، حيث يؤدي احتراقها إلى انبعاث غازات ضارة مثل ثاني أكسيد الكربون.</li>
                <li><strong>إزالة الغابات:</strong> الأشجار تمتص ثاني أكسيد الكربون، وعند قطعها يقل امتصاص هذا الغاز فيزداد في الجو.</li>
                <li><strong>التلوث الصناعي:</strong> المصانع ووسائل النقل تطلق كميات كبيرة من الغازات المسببة للاحتباس الحراري.</li>
                <li><strong>الأنشطة الزراعية:</strong> بعض الأنشطة الزراعية وتربية الماشية تنتج غاز الميثان، وهو من الغازات التي تساهم في ارتفاع درجة حرارة الأرض.</li>
            </ul>
        </div>

        <div class="fade-in">
            <h2>ثالثًا: ما هو الاحتباس الحراري؟</h2>
            <p>الاحتباس الحراري هو ارتفاع درجة حرارة الأرض بسبب تراكم الغازات في الغلاف الجوي، مما يمنع خروج حرارة الشمس مرة أخرى إلى الفضاء.</p>
            <h3>ومن أهم هذه الغازات:</h3>
            <ul>
                <li>ثاني أكسيد الكربون</li>
                <li>الميثان</li>
                <li>أكسيد النيتروز</li>
            </ul>
        </div>

        <div class="fade-in">
            <h2>رابعًا: آثار التغيرات المناخية</h2>
            <ul>
                <li>🌡️ <strong>ارتفاع درجات الحرارة:</strong> أصبحت موجات الحر أكثر شدة وتكرارًا.</li>
                <li>🌊 <strong>ذوبان الجليد:</strong> ذوبان الجليد في المناطق القطبية يؤدي إلى ارتفاع مستوى سطح البحر.</li>
                <li>🌪️ <strong>زيادة الكوارث الطبيعية:</strong> مثل الأعاصير والفيضانات وحرائق الغابات.</li>
                <li>🌾 <strong>تأثيرها على الزراعة:</strong> تؤثر التغيرات المناخية على المحاصيل الزراعية وقد تسبب نقصًا في الغذاء.</li>
                <li>🐠 <strong>تهديد الكائنات الحية:</strong> بعض الحيوانات مهددة بالانقراض بسبب تغير بيئتها الطبيعية.</li>
            </ul>
        </div>

        <div class="fade-in">
            <h2>خامسًا: الجهود العالمية لمواجهة التغير المناخي</h2>
            <ul>
                <li>عقد مؤتمرات دولية مثل مؤتمرات المناخ التابعة للأمم المتحدة.</li>
                <li>توقيع اتفاقيات دولية مثل اتفاقية باريس التي تهدف إلى تقليل انبعاث الغازات الضارة.</li>
                <li>تشجيع استخدام الطاقة المتجددة مثل الطاقة الشمسية وطاقة الرياح.</li>
            </ul>
        </div>

        <div class="fade-in">
            <h2>سادسًا: كيف نساهم نحن في الحل؟</h2>
            <p>حتى الطلاب يمكنهم المساعدة من خلال:</p>
            <ul>
                <li>ترشيد استهلاك الكهرباء والمياه.</li>
                <li>زراعة الأشجار.</li>
                <li>استخدام المواصلات العامة لتقليل التلوث.</li>
                <li>نشر الوعي بين الأصدقاء والأسرة.</li>
            </ul>
        </div>

        <div class="fun-facts fade-in">
            <h3>🤔 معلومات قد لا يعرفها الكثيرون</h3>
            <ul>
                <li>ارتفاع درجة حرارة الأرض بدرجة أو درجتين فقط قد يسبب تغيرات خطيرة جدًا.</li>
                <li>بعض الدول مهددة بالغرق بسبب ارتفاع مستوى سطح البحر.</li>
                <li>الطاقة الشمسية أصبحت من أرخص مصادر الطاقة في العالم.</li>
            </ul>
        </div>

        <div class="conclusion fade-in">
            <h2>خاتمة</h2>
            <p>التغيرات المناخية ليست مشكلة تخص دولة معينة، بل هي قضية عالمية تؤثر على جميع البشر. وإذا لم يتكاتف الجميع للحد منها، فقد يواجه العالم تحديات خطيرة في المستقبل. لذلك يجب علينا أن نكون واعين بخطورة المشكلة، ونعمل معًا لحماية كوكب الأرض من أجل الأجيال القادمة.</p>
        </div>
    </div>

    <script>
        // كود جافاسكريبت بسيط لإظهار العناصر بحركة انسيابية عند التمرير
        document.addEventListener("DOMContentLoaded", function() {
            const observerOptions = {
                root: null,
                rootMargin: '0px',
                threshold: 0.1
            };

            const observer = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                        observer.unobserve(entry.target); // التوقف عن المراقبة بعد الظهور
                    }
                });
            }, observerOptions);

            const elements = document.querySelectorAll('.fade-in');
            elements.forEach(el => observer.observe(el));
        });
    </script>
</body>
</html>
