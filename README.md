# -<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>محمود أحمد عبد الوهاب الضيف - معرض الأعمال</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f9fa;
        }
        .hero-section {
            background: linear-gradient(135deg, #0d6efd 0%, #0a58ca 100%);
            color: white;
            padding: 80px 0;
        }
        .card {
            border: none;
            transition: transform 0.2s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body>

    <!-- شريط التنقل (Navbar) -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top shadow-sm">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">محمود الضيف</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">نبذة عني</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">المهارات</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">المشاريع</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">تواصل معي</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- القسم الرئيسي (Hero Section) -->
    <header class="hero-section text-center">
        <div class="container">
            <h1 class="display-4 fw-bold mb-3">محمود أحمد عبد الوهاب الضيف</h1>
            <p class="fs-4 mb-4">طالب بنظم المعلومات الإدارية | مطور واجهات وب</p>
            <a href="#projects" class="btn btn-light btn-lg fw-bold px-4">معاينة المشاريع</a>
        </div>
    </header>

    <!-- قسم نبذة عني (About Me) -->
    <section id="about" class="py-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-md-8 text-center">
                    <h2 class="fw-bold mb-4">نبذة عني</h2>
                    <div class="card p-4 shadow-sm bg-white">
                        <p class="fs-5 text-muted mb-0">
                            أنا <strong>محمود أحمد عبد الوهاب الضيف</strong>، طالب بالمعهد العالي للدلتا للحاسبات بالمنصورة (شعبة نظم معلومات إدارية - الفرقة الرابعة). مهتم بمجال البرمجيات وتطوير مواقع الويب، وأسعى لبناء تطبيقات واحترافية تلبي احتياجات المستخدمين.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم المهارات (Skills) -->
    <section id="skills" class="py-5 bg-white">
        <div class="container">
            <h2 class="text-center fw-bold mb-5">المهارات التقنية</h2>
            <div class="row text-center g-4">
                <div class="col-md-3 col-6">
                    <div class="p-3 border rounded shadow-sm">
                        <i class="bi bi-filetype-html display-4 text-danger"></i>
                        <h5 class="mt-2">HTML5</h5>
                    </div>
                </div>
                <div class="col-md-3 col-6">
                    <div class="p-3 border rounded shadow-sm">
                        <i class="bi bi-filetype-css display-4 text-primary"></i>
                        <h5 class="mt-2">CSS3</h5>
                    </div>
                </div>
                <div class="col-md-3 col-6">
                    <div class="p-3 border rounded shadow-sm">
                        <i class="bi bi-bootstrap display-4 text-purple" style="color: #6f42c1;"></i>
                        <h5 class="mt-2">Bootstrap</h5>
                    </div>
                </div>
                <div class="col-md-3 col-6">
                    <div class="p-3 border rounded shadow-sm">
                        <i class="bi bi-database display-4 text-warning"></i>
                        <h5 class="mt-2">قواعد البيانات (SQL)</h5>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم المشاريع (Projects) -->
    <section id="projects" class="py-5">
        <div class="container">
            <h2 class="text-center fw-bold mb-5">المشاريع والأعمال السابقة</h2>
            <div class="row g-4">
                <!-- مشروع 1 -->
                <div class="col-md-4">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">مشروع موقع شخصي (Portfolio)</h5>
                            <p class="card-text text-muted">موقع تعريفي متجاوب يعرض السيرة الذاتية والمهارات والمشاريع باستخدام HTML, CSS, و Bootstrap.</p>
                        </div>
                        <div class="card-footer bg-transparent border-0 mb-2">
                            <a href="#" class="btn btn-outline-primary w-100">معاينة الكود</a>
                        </div>
                    </div>
                </div>
                <!-- مشروع 2 (يمكنك تعديله لاحقاً) -->
                <div class="col-md-4">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">مشروع إدارة قواعد البيانات</h5>
                            <p class="card-text text-muted">تصميم وبناء نظام قواعد بيانات متكامل لتطبيق إداري كجزء من المشاريع الأكاديمية.</p>
                        </div>
                        <div class="card-footer bg-transparent border-0 mb-2">
                            <a href="#" class="btn btn-outline-primary w-100">معاينة التفاصيل</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم التواصل (Contact) -->
    <section id="contact" class="py-5 bg-dark text-white">
        <div class="container text-center">
            <h2 class="fw-bold mb-4">تواصل معي</h2>
            <p class="mb-4">يسعدني التواصل معك لأي استفسارات أو فرص عمل ومشاريع مشتركة.</p>
            <div class="d-flex justify-content-center gap-3">
                <a href="mailto:example@email.com" class="btn btn-outline-light"><i class="bi bi-envelope-fill me-2"></i>البريد الإلكتروني</a>
                <a href="#" class="btn btn-outline-light"><i class="bi bi-linkedin me-2"></i>LinkedIn</a>
                <a href="#" class="btn btn-outline-light"><i class="bi bi-github me-2"></i>GitHub</a>
            </div>
        </div>
    </section>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
