**Nama:** Wahyu Andika
**Kelas:** TI.24.A2
**Mata Kuliah:** Pemrograman Web
**Dosen Pengampu:** Agung Nugroho, S.Kom., M.Kom
**Universitas Pelita Bangsa**

---

## **TAHAP 1 Struktur HTML Dasar + Bootstrap**

### Kode:

```<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - Web Framework</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <div class="container text-center py-5">
        <h1 class="text-primary">Praktikum 6 - Web Framework</h1>
        <p class="lead">Membangun website dengan Bootstrap 5</p>
        <div class="alert alert-info mt-4">
            Website sedang dalam pengembangan...
        </div>
    </div>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

<img width="940" height="509" alt="image" src="https://github.com/user-attachments/assets/88bb7fb3-cc66-4000-a3a4-fe19847f8d92" />

---

##  **TAHAP 2 Navbar Responsif**

###  Kode:

```<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - Web Framework</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            padding-top: 76px;
        }
        .navbar-brand {
            font-weight: bold;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="bi bi-code-slash"></i> Lab6Web
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Tentang</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Project</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container text-center py-5">
        <h1 class="text-primary">Praktikum 6 - Web Framework</h1>
        <p class="lead">Membangun website dengan Bootstrap 5</p>
        <div class="alert alert-info mt-4">
            Navbar telah ditambahkan!
        </div>
    </div>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

<img width="940" height="506" alt="image" src="https://github.com/user-attachments/assets/87126f23-3d8f-4076-8664-a8ff31e88e6a" />

---

## **TAHAP 3 Hero Section dengan Gradient**

### Kode:

```<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - Web Framework</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        .hero-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 120px 0 80px;
            margin-top: 76px;
        }
        
        .hero-section h1 {
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 1.5rem;
        }
        
        .hero-section .lead {
            font-size: 1.25rem;
            opacity: 0.9;
            margin-bottom: 2rem;
        }
        
        .btn-hero {
            background: rgba(255,255,255,0.2);
            border: 2px solid white;
            color: white;
            padding: 12px 30px;
            border-radius: 50px;
            transition: all 0.3s ease;
        }
        
        .btn-hero:hover {
            background: white;
            color: #667eea;
            transform: translateY(-2px);
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="bi bi-code-slash"></i> Lab6Web
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Tentang</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Project</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-8">
                    <h1>Framework Web dengan Bootstrap 5</h1>
                    <p class="lead">Membangun layout responsif, modern, dan estetik untuk mahasiswa IT.</p>
                    <a href="#projects" class="btn btn-hero">
                        <i class="bi bi-rocket-takeoff"></i> Jelajahi Project
                    </a>
                </div>
                <div class="col-lg-4 text-center">
                    <i class="bi bi-laptop" style="font-size: 8rem; opacity: 0.8;"></i>
                </div>
            </div>
        </div>
    </section>

    <div class="container py-5 text-center">
        <div class="alert alert-success">
            Hero Section dengan gradient telah ditambahkan!
        </div>
    </div>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

<img width="940" height="504" alt="image" src="https://github.com/user-attachments/assets/f8abe9f4-9663-41a9-a8cc-ee1a5ed34fc9" />

---

## **TAHAP 4 About Section dengan Cards**

### Kode:

```<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - Web Framework</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        .hero-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 120px 0 80px;
            margin-top: 76px;
        }
        
        .about-section {
            padding: 80px 0;
            background: #f8f9fa;
        }
        
        .feature-card {
            background: white;
            border: none;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
            height: 100%;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
        }
        
        .card-icon {
            font-size: 3rem;
            color: #667eea;
            margin-bottom: 1rem;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="bi bi-code-slash"></i> Lab6Web
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">Tentang</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#projects">Project</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section" id="home">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-8">
                    <h1>Framework Web dengan Bootstrap 5</h1>
                    <p class="lead">Membangun layout responsif, modern, dan estetik untuk mahasiswa IT.</p>
                    <a href="#projects" class="btn btn-hero">
                        <i class="bi bi-rocket-takeoff"></i> Jelajahi Project
                    </a>
                </div>
                <div class="col-lg-4 text-center">
                    <i class="bi bi-laptop" style="font-size: 8rem; opacity: 0.8;"></i>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about-section" id="about">
        <div class="container">
            <div class="row mb-5">
                <div class="col-lg-8 mx-auto text-center">
                    <h2 class="fw-bold mb-3">Tentang Praktikum</h2>
                    <p class="lead">Praktikum ini membahas konsep dasar penggunaan CSS Framework Bootstrap 5 untuk pengembangan web modern.</p>
                </div>
            </div>
            
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="feature-card p-4 text-center">
                        <div class="card-icon">
                            <i class="bi bi-lightning-charge"></i>
                        </div>
                        <h5>Fast Development</h5>
                        <p>Bootstrap memungkinkan pengembangan website yang cepat dengan komponen siap pakai.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-card p-4 text-center">
                        <div class="card-icon">
                            <i class="bi bi-phone"></i>
                        </div>
                        <h5>Responsive Design</h5>
                        <p>Website otomatis menyesuaikan tampilan di berbagai perangkat dan ukuran layar.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-card p-4 text-center">
                        <div class="card-icon">
                            <i class="bi bi-palette"></i>
                        </div>
                        <h5>Customizable</h5>
                        <p>Mudah dikustomisasi sesuai kebutuhan dengan variabel CSS dan Sass.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

<img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/b870500e-83d9-4ae0-a3c2-ca7b6966b71d" />

---

## **TAHAP 5 Projects Section dengan Hover Effects**

### Kode:

```<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - Web Framework</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        .hero-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 120px 0 80px;
            margin-top: 76px;
        }
        
        .about-section {
            padding: 80px 0;
            background: #f8f9fa;
        }
        
        .projects-section {
            padding: 80px 0;
        }
        
        .project-card {
            border: none;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
            height: 100%;
        }
        
        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.2);
        }
        
        .project-img {
            height: 200px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 3rem;
        }
        
        .tech-badge {
            background: #667eea;
            color: white;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            margin-right: 5px;
            margin-bottom: 5px;
            display: inline-block;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="bi bi-code-slash"></i> Lab6Web
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">Tentang</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#projects">Project</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section" id="home">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-8">
                    <h1>Framework Web dengan Bootstrap 5</h1>
                    <p class="lead">Membangun layout responsif, modern, dan estetik untuk mahasiswa IT.</p>
                    <a href="#projects" class="btn btn-hero">
                        <i class="bi bi-rocket-takeoff"></i> Jelajahi Project
                    </a>
                </div>
                <div class="col-lg-4 text-center">
                    <i class="bi bi-laptop" style="font-size: 8rem; opacity: 0.8;"></i>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about-section" id="about">
        <div class="container">
            <div class="row mb-5">
                <div class="col-lg-8 mx-auto text-center">
                    <h2 class="fw-bold mb-3">Tentang Praktikum</h2>
                    <p class="lead">Praktikum ini membahas konsep dasar penggunaan CSS Framework Bootstrap 5 untuk pengembangan web modern.</p>
                </div>
            </div>
            
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="feature-card p-4 text-center">
                        <div class="card-icon">
                            <i class="bi bi-lightning-charge"></i>
                        </div>
                        <h5>Fast Development</h5>
                        <p>Bootstrap memungkinkan pengembangan website yang cepat dengan komponen siap pakai.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-card p-4 text-center">
                        <div class="card-icon">
                            <i class="bi bi-phone"></i>
                        </div>
                        <h5>Responsive Design</h5>
                        <p>Website otomatis menyesuaikan tampilan di berbagai perangkat dan ukuran layar.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-card p-4 text-center">
                        <div class="card-icon">
                            <i class="bi bi-palette"></i>
                        </div>
                        <h5>Customizable</h5>
                        <p>Mudah dikustomisasi sesuai kebutuhan dengan variabel CSS dan Sass.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="projects-section" id="projects">
        <div class="container">
            <div class="row mb-5">
                <div class="col-lg-8 mx-auto text-center">
                    <h2 class="fw-bold mb-3">Project Showcase</h2>
                    <p class="lead">Beberapa project yang dikembangkan menggunakan Bootstrap 5</p>
                </div>
            </div>
            
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="project-card">
                        <div class="project-img">
                            <i class="bi bi-grid-3x3-gap"></i>
                        </div>
                        <div class="card-body p-4">
                            <h5 class="card-title">Admin Dashboard</h5>
                            <p class="card-text">Dashboard admin modern dengan berbagai komponen UI Bootstrap.</p>
                            <div class="mb-3">
                                <span class="tech-badge">Bootstrap 5</span>
                                <span class="tech-badge">JavaScript</span>
                                <span class="tech-badge">Chart.js</span>
                            </div>
                            <a href="#" class="btn btn-primary btn-sm">
                                <i class="bi bi-eye"></i> Live Preview
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4">
                    <div class="project-card">
                        <div class="project-img">
                            <i class="bi bi-cart"></i>
                        </div>
                        <div class="card-body p-4">
                            <h5 class="card-title">E-commerce Store</h5>
                            <p class="card-text">Website toko online dengan shopping cart dan product catalog.</p>
                            <div class="mb-3">
                                <span class="tech-badge">Bootstrap 5</span>
                                <span class="tech-badge">PHP</span>
                                <span class="tech-badge">MySQL</span>
                            </div>
                            <a href="#" class="btn btn-primary btn-sm">
                                <i class="bi bi-eye"></i> Live Preview
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4">
                    <div class="project-card">
                        <div class="project-img">
                            <i class="bi bi-person-badge"></i>
                        </div>
                        <div class="card-body p-4">
                            <h5 class="card-title">Portfolio Website</h5>
                            <p class="card-text">Website portfolio pribadi dengan design modern dan responsive.</p>
                            <div class="mb-3">
                                <span class="tech-badge">Bootstrap 5</span>
                                <span class="tech-badge">HTML5</span>
                                <span class="tech-badge">CSS3</span>
                            </div>
                            <a href="#" class="btn btn-primary btn-sm">
                                <i class="bi bi-eye"></i> Live Preview
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

<img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/d91a4d3d-6714-49a9-bce4-cadd457017ba" />
.
---

## **TAHAP 6 Contact Section dengan Social Media**

### Kode:

```<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - Web Framework</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
    <style>
        /* ... (styles dari tahap sebelumnya) ... */
        
        .contact-section {
            padding: 80px 0;
            background: #f8f9fa;
        }
        
        .contact-card {
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            padding: 3rem;
        }
        
        .social-btn {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            margin: 0 10px;
            transition: all 0.3s ease;
            text-decoration: none;
        }
        
        .social-btn:hover {
            transform: translateY(-3px);
        }
        
        .btn-email {
            background: #dc3545;
            color: white;
        }
        
        .btn-linkedin {
            background: #0077b5;
            color: white;
        }
        
        .btn-github {
            background: #333;
            color: white;
        }
    </style>
</head>
<body>
    <!-- ... (navbar, hero, about, projects dari tahap sebelumnya) ... -->

    <!-- Contact Section -->
    <section class="contact-section" id="contact">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="contact-card text-center">
                        <h2 class="fw-bold mb-4">Hubungi Saya</h2>
                        <p class="lead mb-5">Silakan hubungi saya melalui media sosial berikut untuk kolaborasi project</p>
                        
                        <div class="row mb-4">
                            <div class="col-md-4 mb-3">
                                <div class="bg-primary rounded-circle p-3 mx-auto mb-3" style="width: 80px; height: 80px;">
                                    <i class="bi bi-envelope text-white fs-2"></i>
                                </div>
                                <h5>Email</h5>
                                <p>wahyu.andika@example.com</p>
                                <a href="mailto:wahyu.andika@example.com" class="btn btn-outline-primary">
                                    <i class="bi bi-send"></i> Kirim Email
                                </a>
                            </div>
                            
                            <div class="col-md-4 mb-3">
                                <div class="bg-success rounded-circle p-3 mx-auto mb-3" style="width: 80px; height: 80px;">
                                    <i class="bi bi-linkedin text-white fs-2"></i>
                                </div>
                                <h5>LinkedIn</h5>
                                <p>Wahyu Andika</p>
                                <a href="#" class="btn btn-outline-success">
                                    <i class="bi bi-box-arrow-up-right"></i> Connect
                                </a>
                            </div>
                            
                            <div class="col-md-4 mb-3">
                                <div class="bg-dark rounded-circle p-3 mx-auto mb-3" style="width: 80px; height: 80px;">
                                    <i class="bi bi-github text-white fs-2"></i>
                                </div>
                                <h5>GitHub</h5>
                                <p>@wahyuandika</p>
                                <a href="#" class="btn btn-outline-dark">
                                    <i class="bi bi-code-slash"></i> Follow
                                </a>
                            </div>
                        </div>
                        
                        <div class="social-links mt-4">
                            <a href="#" class="social-btn btn-email">
                                <i class="bi bi-envelope"></i>
                            </a>
                            <a href="#" class="social-btn btn-linkedin">
                                <i class="bi bi-linkedin"></i>
                            </a>
                            <a href="#" class="social-btn btn-github">
                                <i class="bi bi-github"></i>
                            </a>
                            <a href="#" class="social-btn" style="background: #1da1f2; color: white;">
                                <i class="bi bi-twitter"></i>
                            </a>
                            <a href="#" class="social-btn" style="background: #e4405f; color: white;">
                                <i class="bi bi-instagram"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

<img width="940" height="504" alt="image" src="https://github.com/user-attachments/assets/370cc25e-281e-42db-a5e8-5c258e49695b" />

---

## **TAHAP 7 Footer & Final Touches**

### Kode:

```<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - Web Framework</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
    <style>
        /* ... (semua styles dari tahap sebelumnya) ... */
        
        footer {
            background: #2d3748;
            color: white;
            padding: 2rem 0;
        }
        
        .footer-links a {
            color: #cbd5e0;
            text-decoration: none;
            margin: 0 10px;
            transition: color 0.3s ease;
        }
        
        .footer-links a:hover {
            color: white;
        }
    </style>
</head>
<body>
    <!-- ... (semua sections dari tahap sebelumnya) ... -->

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-start">
                    <h5 class="mb-3"><i class="bi bi-code-slash"></i> Lab6Web Framework</h5>
                    <p class="mb-0">Membuat web development lebih mudah dan menyenangkan</p>
                </div>
                <div class="col-md-6 text-center text-md-end">
                    <div class="footer-links mb-3">
                        <a href="#home">Home</a>
                        <a href="#about">Tentang</a>
                        <a href="#projects">Project</a>
                        <a href="#contact">Kontak</a>
                    </div>
                    <div class="social-links">
                        <a href="#" class="text-white me-3"><i class="bi bi-facebook"></i></a>
                        <a href="#" class="text-white me-3"><i class="bi bi-twitter"></i></a>
                        <a href="#" class="text-white me-3"><i class="bi bi-instagram"></i></a>
                        <a href="#" class="text-white"><i class="bi bi-github"></i></a>
                    </div>
                </div>
            </div>
            <hr class="my-4" style="background-color: rgba(255,255,255,0.1);">
            <div class="text-center">
                <p class="mb-0">&copy; 2025 Praktikum 6 - Wahyu Andika | Universitas Pelita Bangsa</p>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

<img width="940" height="501" alt="image" src="https://github.com/user-attachments/assets/ae197f6d-25fe-4cad-87c5-3bb06cff2197" />

---

## **TAHAP 8 Animasi & Interaktivitas**

### Kode:

```<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - Web Framework</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
    <!-- AOS Animation -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <style>
        :root {
            --primary: #667eea;
            --secondary: #764ba2;
            --accent: #f093fb;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        .navbar {
            transition: all 0.4s ease;
        }
        
        .navbar-scrolled {
            background: rgba(0,0,0,0.95) !important;
            backdrop-filter: blur(10px);
        }
        
        .hero-section {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            padding: 120px 0 80px;
            margin-top: 76px;
        }
        
        .btn-hero {
            background: rgba(255,255,255,0.2);
            border: 2px solid white;
            color: white;
            padding: 12px 30px;
            border-radius: 50px;
            transition: all 0.3s ease;
        }
        
        .btn-hero:hover {
            background: white;
            color: var(--primary);
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }
        
        .feature-card, .project-card {
            transition: all 0.3s ease;
        }
        
        .feature-card:hover, .project-card:hover {
            transform: translateY(-10px);
        }
        
        /* Smooth scroll */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#home">
                <i class="bi bi-code-slash"></i> Lab6Web
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">Tentang</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#projects">Project</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section" id="home">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-8" data-aos="fade-right">
                    <h1>Framework Web dengan Bootstrap 5</h1>
                    <p class="lead">Membangun layout responsif, modern, dan estetik untuk mahasiswa IT.</p>
                    <a href="#projects" class="btn btn-hero">
                        <i class="bi bi-rocket-takeoff"></i> Jelajahi Project
                    </a>
                </div>
                <div class="col-lg-4 text-center" data-aos="fade-left">
                    <i class="bi bi-laptop" style="font-size: 8rem; opacity: 0.8;"></i>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about-section" id="about">
        <div class="container">
            <div class="row mb-5">
                <div class="col-lg-8 mx-auto text-center" data-aos="fade-up">
                    <h2 class="fw-bold mb-3">Tentang Praktikum</h2>
                    <p class="lead">Praktikum ini membahas konsep dasar penggunaan CSS Framework Bootstrap 5 untuk pengembangan web modern.</p>
                </div>
            </div>
            
            <div class="row g-4">
                <div class="col-md-4" data-aos="zoom-in" data-aos-delay="100">
                    <div class="feature-card p-4 text-center">
                        <div class="card-icon">
                            <i class="bi bi-lightning-charge"></i>
                        </div>
                        <h5>Fast Development</h5>
                        <p>Bootstrap memungkinkan pengembangan website yang cepat dengan komponen siap pakai.</p>
                    </div>
                </div>
                <div class="col-md-4" data-aos="zoom-in" data-aos-delay="200">
                    <div class="feature-card p-4 text-center">
                        <div class="card-icon">
                            <i class="bi bi-phone"></i>
                        </div>
                        <h5>Responsive Design</h5>
                        <p>Website otomatis menyesuaikan tampilan di berbagai perangkat dan ukuran layar.</p>
                    </div>
                </div>
                <div class="col-md-4" data-aos="zoom-in" data-aos-delay="300">
                    <div class="feature-card p-4 text-center">
                        <div class="card-icon">
                            <i class="bi bi-palette"></i>
                        </div>
                        <h5>Customizable</h5>
                        <p>Mudah dikustomisasi sesuai kebutuhan dengan variabel CSS dan Sass.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="projects-section" id="projects">
        <div class="container">
            <div class="row mb-5">
                <div class="col-lg-8 mx-auto text-center" data-aos="fade-up">
                    <h2 class="fw-bold mb-3">Project Showcase</h2>
                    <p class="lead">Beberapa project yang dikembangkan menggunakan Bootstrap 5</p>
                </div>
            </div>
            
            <div class="row g-4">
                <div class="col-md-4" data-aos="flip-left" data-aos-delay="100">
                    <div class="project-card">
                        <div class="project-img">
                            <i class="bi bi-grid-3x3-gap"></i>
                        </div>
                        <div class="card-body p-4">
                            <h5 class="card-title">Admin Dashboard</h5>
                            <p class="card-text">Dashboard admin modern dengan berbagai komponen UI Bootstrap.</p>
                            <div class="mb-3">
                                <span class="tech-badge">Bootstrap 5</span>
                                <span class="tech-badge">JavaScript</span>
                                <span class="tech-badge">Chart.js</span>
                            </div>
                            <a href="#" class="btn btn-primary btn-sm">
                                <i class="bi bi-eye"></i> Live Preview
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4" data-aos="flip-left" data-aos-delay="200">
                    <div class="project-card">
                        <div class="project-img">
                            <i class="bi bi-cart"></i>
                        </div>
                        <div class="card-body p-4">
                            <h5 class="card-title">E-commerce Store</h5>
                            <p class="card-text">Website toko online dengan shopping cart dan product catalog.</p>
                            <div class="mb-3">
                                <span class="tech-badge">Bootstrap 5</span>
                                <span class="tech-badge">PHP</span>
                                <span class="tech-badge">MySQL</span>
                            </div>
                            <a href="#" class="btn btn-primary btn-sm">
                                <i class="bi bi-eye"></i> Live Preview
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4" data-aos="flip-left" data-aos-delay="300">
                    <div class="project-card">
                        <div class="project-img">
                            <i class="bi bi-person-badge"></i>
                        </div>
                        <div class="card-body p-4">
                            <h5 class="card-title">Portfolio Website</h5>
                            <p class="card-text">Website portfolio pribadi dengan design modern dan responsive.</p>
                            <div class="mb-3">
                                <span class="tech-badge">Bootstrap 5</span>
                                <span class="tech-badge">HTML5</span>
                                <span class="tech-badge">CSS3</span>
                            </div>
                            <a href="#" class="btn btn-primary btn-sm">
                                <i class="bi bi-eye"></i> Live Preview
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact-section" id="contact">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-8" data-aos="fade-up">
                    <div class="contact-card text-center">
                        <h2 class="fw-bold mb-4">Hubungi Saya</h2>
                        <p class="lead mb-5">Silakan hubungi saya melalui media sosial berikut untuk kolaborasi project</p>
                        
                        <div class="row mb-4">
                            <div class="col-md-4 mb-3" data-aos="zoom-in" data-aos-delay="100">
                                <div class="bg-primary rounded-circle p-3 mx-auto mb-3" style="width: 80px; height: 80px;">
                                    <i class="bi bi-envelope text-white fs-2"></i>
                                </div>
                                <h5>Email</h5>
                                <p>wahyu.andika@example.com</p>
                                <a href="mailto:wahyu.andika@example.com" class="btn btn-outline-primary">
                                    <i class="bi bi-send"></i> Kirim Email
                                </a>
                            </div>
                            
                            <div class="col-md-4 mb-3" data-aos="zoom-in" data-aos-delay="200">
                                <div class="bg-success rounded-circle p-3 mx-auto mb-3" style="width: 80px; height: 80px;">
                                    <i class="bi bi-linkedin text-white fs-2"></i>
                                </div>
                                <h5>LinkedIn</h5>
                                <p>Wahyu Andika</p>
                                <a href="#" class="btn btn-outline-success">
                                    <i class="bi bi-box-arrow-up-right"></i> Connect
                                </a>
                            </div>
                            
                            <div class="col-md-4 mb-3" data-aos="zoom-in" data-aos-delay="300">
                                <div class="bg-dark rounded-circle p-3 mx-auto mb-3" style="width: 80px; height: 80px;">
                                    <i class="bi bi-github text-white fs-2"></i>
                                </div>
                                <h5>GitHub</h5>
                                <p>@wahyuandika</p>
                                <a href="#" class="btn btn-outline-dark">
                                    <i class="bi bi-code-slash"></i> Follow
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-start">
                    <h5 class="mb-3"><i class="bi bi-code-slash"></i> Lab6Web Framework</h5>
                    <p class="mb-0">Membuat web development lebih mudah dan menyenangkan</p>
                </div>
                <div class="col-md-6 text-center text-md-end">
                    <div class="footer-links mb-3">
                        <a href="#home">Home</a>
                        <a href="#about">Tentang</a>
                        <a href="#projects">Project</a>
                        <a href="#contact">Kontak</a>
                    </div>
                </div>
            </div>
            <hr class="my-4" style="background-color: rgba(255,255,255,0.1);">
            <div class="text-center">
                <p class="mb-0">&copy; 2025 Praktikum 6 - Wahyu Andika | Universitas Pelita Bangsa</p>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <!-- AOS Animation -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    
    <script>
        // Initialize AOS
        AOS.init({
            duration: 800,
            once: true,
            offset: 100
        });

        // Navbar scroll effect
        window.addEventListener('scroll', function() {
            if (window.scrollY > 100) {
                document.querySelector('.navbar').classList.add('navbar-scrolled');
            } else {
                document.querySelector('.navbar').classList.remove('navbar-scrolled');
            }
        });

        // Active nav link
        const sections = document.querySelectorAll('section');
        const navLinks = document.querySelectorAll('.nav-link');

        window.addEventListener('scroll', function() {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (scrollY >= (sectionTop - 100)) {
                    current = section.getAttribute('id');
                }
            });

            navLinks.forEach(link => {
                link.classList.remove('active');
                if (link.getAttribute('href') === `#${current}`) {
                    link.classList.add('active');
                }
            });
        });
    </script>
</body>
</html>
```

<img width="940" height="506" alt="image" src="https://github.com/user-attachments/assets/ba3ea873-c3e4-48f4-bac7-d1b663b2a40e" />

---

## **TAHAP 9 Gambar & Penyempurnaan**

### Kode:

```<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - Web Framework Bootstrap 5</title>
    
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- AOS Animation -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style>
        :root {
            --primary: #667eea;
            --secondary: #764ba2;
            --accent: #f093fb;
            --dark: #2d3748;
            --light: #f8f9fa;
        }

        * {
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            overflow-x: hidden;
        }

        /* ===== NAVBAR ===== */
        .navbar {
            background: rgba(13, 13, 13, 0.95) !important;
            backdrop-filter: blur(20px);
            padding: 1rem 0;
            transition: all 0.4s ease;
        }

        .navbar-scrolled {
            background: rgba(13, 13, 13, 0.98) !important;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .navbar-brand {
            font-weight: 700;
            font-size: 1.5rem;
            background: linear-gradient(45deg, var(--primary), var(--accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .nav-link {
            color: #fff !important;
            font-weight: 500;
            margin: 0 0.3rem;
            padding: 0.5rem 1rem !important;
            border-radius: 25px;
            transition: all 0.3s ease;
        }

        .nav-link:hover,
        .nav-link.active {
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        /* ===== HERO SECTION ===== */
        .hero {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            min-height: 100vh;
            display: flex;
            align-items: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 100" fill="%23ffffff" opacity="0.1"><polygon points="1000,100 1000,0 0,100"></polygon></svg>');
            background-size: cover;
        }

        .hero-content h1 {
            font-size: 3.5rem;
            font-weight: 800;
            margin-bottom: 1.5rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .hero-content p {
            font-size: 1.3rem;
            opacity: 0.9;
            margin-bottom: 2rem;
        }

        .btn-hero {
            background: linear-gradient(45deg, var(--accent), #ffecd2);
            border: none;
            padding: 15px 35px;
            border-radius: 50px;
            font-weight: 600;
            color: var(--dark);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            transition: all 0.3s ease;
            font-size: 1.1rem;
        }

        .btn-hero:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.3);
        }

        .hero-image {
            animation: float 6s ease-in-out infinite;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
            border: 3px solid rgba(255,255,255,0.2);
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }

        /* ===== ABOUT SECTION ===== */
        .about-section {
            padding: 100px 0;
            background: var(--light);
        }

        .about-card {
            background: white;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
            padding: 3rem;
            transition: all 0.3s ease;
            border-left: 5px solid var(--primary);
        }

        .about-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 25px 50px rgba(0,0,0,0.15);
        }

        .about-img {
            border-radius: 15px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
        }

        .about-img:hover {
            transform: scale(1.02);
        }

        /* ===== FEATURES SECTION ===== */
        .features-section {
            padding: 100px 0;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
        }

        .feature-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.2);
            border-radius: 20px;
            padding: 2.5rem;
            text-align: center;
            transition: all 0.3s ease;
            height: 100%;
        }

        .feature-card:hover {
            transform: translateY(-10px);
            background: rgba(255,255,255,0.15);
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }

        .feature-icon {
            font-size: 3rem;
            margin-bottom: 1.5rem;
            background: linear-gradient(45deg, var(--accent), #ffecd2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* ===== PROJECTS SECTION ===== */
        .projects-section {
            padding: 100px 0;
            background: var(--light);
        }

        .project-card {
            background: white;
            border: none;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
            height: 100%;
        }

        .project-card:hover {
            transform: translateY(-15px);
            box-shadow: 0 25px 50px rgba(0,0,0,0.15);
        }

        .project-img {
            height: 250px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .project-card:hover .project-img {
            transform: scale(1.05);
        }

        .project-card .card-body {
            padding: 2rem;
        }

        .tech-badge {
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.8rem;
            margin-right: 5px;
            margin-bottom: 5px;
            display: inline-block;
        }

        /* ===== CONTACT SECTION ===== */
        .contact-section {
            padding: 100px 0;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }

        .contact-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.2);
            border-radius: 20px;
            padding: 3rem;
        }

        .contact-btn {
            background: linear-gradient(45deg, var(--accent), #ffecd2);
            border: none;
            color: var(--dark);
            padding: 12px 30px;
            border-radius: 50px;
            transition: all 0.3s ease;
            font-weight: 600;
        }

        .contact-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            color: var(--dark);
        }

        .social-links a {
            color: white;
            font-size: 1.5rem;
            margin: 0 10px;
            transition: all 0.3s ease;
            display: inline-block;
        }

        .social-links a:hover {
            color: var(--accent);
            transform: translateY(-5px);
        }

        /* ===== FOOTER ===== */
        footer {
            background: var(--dark);
            color: white;
            padding: 3rem 0 2rem;
        }

        .footer-links a {
            color: #cbd5e0;
            text-decoration: none;
            margin: 0 15px;
            transition: color 0.3s ease;
        }

        .footer-links a:hover {
            color: white;
        }

        /* ===== CODE SHOWCASE ===== */
        .code-showcase {
            background: #1a1a1a;
            color: #00ff00;
            padding: 2rem;
            border-radius: 10px;
            font-family: 'Courier New', monospace;
            font-size: 0.9rem;
            margin: 2rem 0;
        }

        /* ===== RESPONSIVE DESIGN ===== */
        @media (max-width: 768px) {
            .hero-content h1 {
                font-size: 2.5rem;
            }
            
            .hero-content p {
                font-size: 1.1rem;
            }
            
            .about-card, .feature-card, .project-card {
                margin-bottom: 2rem;
            }
        }
    </style>
</head>
<body>
    <!-- NAVBAR -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#home">
                <i class="bi bi-code-slash me-2"></i>Lab6 Framework
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">Tentang</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#features">Fitur</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#projects">Project</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section class="hero" id="home">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6" data-aos="fade-right">
                    <div class="hero-content">
                        <h1>Framework Web dengan Bootstrap 5</h1>
                        <p>Membangun website modern, responsif, dan profesional dengan framework CSS terpopuler. Praktikum ini mengajarkan konsep dasar hingga advanced Bootstrap 5.</p>
                        <div class="d-flex gap-3 flex-wrap">
                            <a href="#projects" class="btn btn-hero">
                                <i class="bi bi-rocket-takeoff me-2"></i>Jelajahi Project
                            </a>
                            <a href="#about" class="btn btn-outline-light">
                                <i class="bi bi-info-circle me-2"></i>Pelajari Lebih
                            </a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 text-center" data-aos="fade-left">
                    <img src="https://images.unsplash.com/photo-1627398242454-45a1465c2479?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" 
                         alt="Bootstrap Code" class="img-fluid hero-image">
                </div>
            </div>
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section class="about-section" id="about">
        <div class="container">
            <div class="row justify-content-center mb-5">
                <div class="col-lg-8 text-center" data-aos="fade-up">
                    <h2 class="fw-bold mb-3">Tentang Praktikum Web Framework</h2>
                    <p class="lead">Praktikum ini fokus pada penguasaan CSS Framework Bootstrap 5 untuk pengembangan web modern dan responsif</p>
                </div>
            </div>
            <div class="row g-5 align-items-center">
                <div class="col-lg-6" data-aos="fade-right">
                    <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" 
                         alt="Code Editor" class="img-fluid about-img">
                </div>
                <div class="col-lg-6" data-aos="fade-left">
                    <div class="about-card">
                        <h3 class="fw-bold mb-4">Apa itu Bootstrap 5?</h3>
                        <p class="mb-4">Bootstrap adalah framework CSS open-source yang digunakan untuk mengembangkan website responsif dan mobile-first dengan cepat dan mudah.</p>
                        
                        <div class="code-showcase">
                            <span class="text-warning">&lt;link</span> <span class="text-info">href=</span><span class="text-danger">"bootstrap.min.css"</span> <span class="text-info">rel=</span><span class="text-danger">"stylesheet"</span><span class="text-warning">&gt;</span><br>
                            <span class="text-warning">&lt;div</span> <span class="text-info">class=</span><span class="text-danger">"container"</span><span class="text-warning">&gt;</span><br>
                            &nbsp;&nbsp;<span class="text-warning">&lt;div</span> <span class="text-info">class=</span><span class="text-danger">"row"</span><span class="text-warning">&gt;</span><br>
                            &nbsp;&nbsp;&nbsp;&nbsp;<span class="text-warning">&lt;div</span> <span class="text-info">class=</span><span class="text-danger">"col-md-6"</span><span class="text-warning">&gt;</span><br>
                            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="text-white">// Your content here</span><br>
                            &nbsp;&nbsp;&nbsp;&nbsp;<span class="text-warning">&lt;/div&gt;</span><br>
                            &nbsp;&nbsp;<span class="text-warning">&lt;/div&gt;</span><br>
                            <span class="text-warning">&lt;/div&gt;</span>
                        </div>
                        
                        <div class="row mt-4 text-center">
                            <div class="col-4">
                                <h4 class="text-primary fw-bold">95%</h4>
                                <small>Website Responsif</small>
                            </div>
                            <div class="col-4">
                                <h4 class="text-success fw-bold">70%</h4>
                                <small>Waktu Development</small>
                            </div>
                            <div class="col-4">
                                <h4 class="text-warning fw-bold">100%</h4>
                                <small>Browser Support</small>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FEATURES SECTION -->
    <section class="features-section" id="features">
        <div class="container">
            <div class="row justify-content-center mb-5">
                <div class="col-lg-8 text-center" data-aos="fade-up">
                    <h2 class="fw-bold mb-3">Fitur Utama Bootstrap 5</h2>
                    <p class="lead">Keunggulan yang membuat Bootstrap menjadi pilihan utama developer</p>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-4" data-aos="zoom-in" data-aos-delay="100">
                    <div class="feature-card">
                        <div class="feature-icon">
                            <i class="bi bi-phone"></i>
                        </div>
                        <h4 class="fw-bold mb-3">Mobile-First</h4>
                        <p>Didesain dengan pendekatan mobile-first, memastikan website tampil sempurna di semua perangkat.</p>
                    </div>
                </div>
                <div class="col-md-4" data-aos="zoom-in" data-aos-delay="200">
                    <div class="feature-card">
                        <div class="feature-icon">
                            <i class="bi bi-lightning-charge"></i>
                        </div>
                        <h4 class="fw-bold mb-3">Fast Development</h4>
                        <p>Komponen siap pakai mempercepat proses development tanpa mengorbankan kualitas.</p>
                    </div>
                </div>
                <div class="col-md-4" data-aos="zoom-in" data-aos-delay="300">
                    <div class="feature-card">
                        <div class="feature-icon">
                            <i class="bi bi-palette"></i>
                        </div>
                        <h4 class="fw-bold mb-3">Customizable</h4>
                        <p>Mudah dikustomisasi dengan Sass variables dan utility classes sesuai kebutuhan.</p>
                    </div>
                </div>
            </div>
            
            <div class="row mt-5">
                <div class="col-12 text-center">
                    <img src="https://images.unsplash.com/photo-1633356122544-f134324a6cee?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80" 
                         alt="Bootstrap Components" class="img-fluid rounded-3" data-aos="fade-up">
                </div>
            </div>
        </div>
    </section>

    <!-- PROJECTS SECTION -->
    <section class="projects-section" id="projects">
        <div class="container">
            <div class="row justify-content-center mb-5">
                <div class="col-lg-8 text-center" data-aos="fade-up">
                    <h2 class="fw-bold mb-3">Project Showcase</h2>
                    <p class="lead">Beberapa project yang dikembangkan menggunakan Bootstrap 5</p>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-4" data-aos="flip-left" data-aos-delay="100">
                    <div class="project-card">
                        <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" 
                             class="project-img w-100" alt="Dashboard Analytics">
                        <div class="card-body">
                            <h5 class="fw-bold">Analytics Dashboard</h5>
                            <p class="mb-3">Dashboard analytics modern dengan chart, data visualization, dan responsive grid system.</p>
                            <div class="mb-3">
                                <span class="tech-badge">Bootstrap 5</span>
                                <span class="tech-badge">Chart.js</span>
                                <span class="tech-badge">JavaScript</span>
                            </div>
                            <a href="#" class="btn btn-primary">
                                <i class="bi bi-eye me-1"></i>Live Preview
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4" data-aos="flip-left" data-aos-delay="200">
                    <div class="project-card">
                        <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" 
                             class="project-img w-100" alt="E-commerce Platform">
                        <div class="card-body">
                            <h5 class="fw-bold">E-commerce Platform</h5>
                            <p class="mb-3">Platform e-commerce dengan product catalog, shopping cart, dan responsive design.</p>
                            <div class="mb-3">
                                <span class="tech-badge">Bootstrap 5</span>
                                <span class="tech-badge">PHP</span>
                                <span class="tech-badge">MySQL</span>
                            </div>
                            <a href="#" class="btn btn-primary">
                                <i class="bi bi-eye me-1"></i>Live Preview
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4" data-aos="flip-left" data-aos-delay="300">
                    <div class="project-card">
                        <img src="https://images.unsplash.com/photo-1467232004584-a241de8bcf5d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" 
                             class="project-img w-100" alt="Web Application">
                        <div class="card-body">
                            <h5 class="fw-bold">Web Application</h5>
                            <p class="mb-3">Aplikasi web modern dengan user interface yang clean dan user experience yang optimal.</p>
                            <div class="mb-3">
                                <span class="tech-badge">Bootstrap 5</span>
                                <span class="tech-badge">React</span>
                                <span class="tech-badge">API</span>
                            </div>
                            <a href="#" class="btn btn-primary">
                                <i class="bi bi-eye me-1"></i>Live Preview
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTACT SECTION -->
    <section class="contact-section" id="contact">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="contact-card text-center" data-aos="fade-up">
                        <h2 class="fw-bold mb-4">Hubungi Saya</h2>
                        <p class="lead mb-5">Silakan hubungi saya melalui media sosial berikut untuk kolaborasi project atau pertanyaan tentang Bootstrap</p>
                        
                        <div class="row mb-5">
                            <div class="col-md-4 mb-4" data-aos="zoom-in" data-aos-delay="100">
                                <div class="bg-primary rounded-circle p-4 mx-auto mb-3" style="width: 80px; height: 80px;">
                                    <i class="bi bi-envelope text-white fs-2"></i>
                                </div>
                                <h5>Email</h5>
                                <p>wahyu.andika@example.com</p>
                                <a href="mailto:wahyu.andika@example.com" class="btn contact-btn">
                                    <i class="bi bi-send me-1"></i>Kirim Email
                                </a>
                            </div>
                            
                            <div class="col-md-4 mb-4" data-aos="zoom-in" data-aos-delay="200">
                                <div class="bg-success rounded-circle p-4 mx-auto mb-3" style="width: 80px; height: 80px;">
                                    <i class="bi bi-linkedin text-white fs-2"></i>
                                </div>
                                <h5>LinkedIn</h5>
                                <p>Wahyu Andika</p>
                                <a href="#" class="btn contact-btn">
                                    <i class="bi bi-box-arrow-up-right me-1"></i>Connect
                                </a>
                            </div>
                            
                            <div class="col-md-4 mb-4" data-aos="zoom-in" data-aos-delay="300">
                                <div class="bg-dark rounded-circle p-4 mx-auto mb-3" style="width: 80px; height: 80px;">
                                    <i class="bi bi-github text-white fs-2"></i>
                                </div>
                                <h5>GitHub</h5>
                                <p>@wahyuandika</p>
                                <a href="#" class="btn contact-btn">
                                    <i class="bi bi-code-slash me-1"></i>Follow
                                </a>
                            </div>
                        </div>
                        
                        <div class="social-links">
                            <a href="#"><i class="bi bi-facebook"></i></a>
                            <a href="#"><i class="bi bi-twitter"></i></a>
                            <a href="#"><i class="bi bi-instagram"></i></a>
                            <a href="#"><i class="bi bi-linkedin"></i></a>
                            <a href="#"><i class="bi bi-github"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-start">
                    <h5 class="mb-3"><i class="bi bi-code-slash me-2"></i>Lab6 Framework</h5>
                    <p class="mb-0">Membuat web development lebih mudah dan menyenangkan dengan Bootstrap 5</p>
                </div>
                <div class="col-md-6 text-center text-md-end">
                    <div class="footer-links mb-3">
                        <a href="#home">Home</a>
                        <a href="#about">Tentang</a>
                        <a href="#features">Fitur</a>
                        <a href="#projects">Project</a>
                        <a href="#contact">Kontak</a>
                    </div>
                </div>
            </div>
            <hr class="my-4" style="background-color: rgba(255,255,255,0.1);">
            <div class="text-center">
                <p class="mb-0">&copy; 2025 Praktikum 6 - Wahyu Andika | Universitas Pelita Bangsa</p>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <!-- AOS Animation -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    
    <script>
        // Initialize AOS
        AOS.init({
            duration: 800,
            once: true,
            offset: 100
        });

        // Navbar scroll effect
        window.addEventListener('scroll', function() {
            if (window.scrollY > 100) {
                document.querySelector('.navbar').classList.add('navbar-scrolled');
            } else {
                document.querySelector('.navbar').classList.remove('navbar-scrolled');
            }
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Active nav link
        const sections = document.querySelectorAll('section');
        const navLinks = document.querySelectorAll('.nav-link');

        window.addEventListener('scroll', function() {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (scrollY >= (sectionTop - 100)) {
                    current = section.getAttribute('id');
                }
            });

            navLinks.forEach(link => {
                link.classList.remove('active');
                if (link.getAttribute('href') === `#${current}`) {
                    link.classList.add('active');
                }
            });
        });
    </script>
</body>
</html>
```

<img width="940" height="506" alt="image" src="https://github.com/user-attachments/assets/153de92b-98b7-43fe-9200-12a3b5eb6fb0" />

<img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/f226db2c-1efb-4fea-a5e4-1c4bd87082a4" />

<img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/ca94bda9-6119-4c17-a043-23b907392bce" />

