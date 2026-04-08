<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portafolio profesional de Dilan Samir López Araujo - Ingeniero de Sistemas | Analista de Datos | Power BI & Python">
    <title>Dilan Samir López Araujo | Portafolio Profesional</title>
   
    <!-- Bootstrap 5 + Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
   
    <style>
        :root {
            --primary: #00bfff;
        }
       
        body {
            font-family: 'Segoe UI', system-ui, sans-serif;
        }
       
        .navbar {
            background: rgba(15, 23, 42, 0.95) !important;
            backdrop-filter: blur(10px);
        }
       
        .hero {
            background: linear-gradient(135deg, #0f172a 0%, #1e2937 100%);
            color: white;
            min-height: 100vh;
            display: flex;
            align-items: center;
        }

        /* ================================================ */
        /* CORRECCIÓN DEFINITIVA DEL NOMBRE (más pequeño y ajustado) */
        .hero-name {                                 
            font-size: clamp(1.9rem, 5.5vw, 3rem);   /* ← Más pequeño para que nunca se rompa */
            line-height: 1.05;
            font-weight: 800;
            word-wrap: break-word;
            overflow-wrap: break-word;
        }
        /* ================================================ */
       
        .section-title {
            position: relative;
            display: inline-block;
        }
       
        .section-title::after {
            content: '';
            position: absolute;
            width: 60%;
            height: 3px;
            background: var(--primary);
            bottom: -8px;
            left: 0;
        }
       
        .timeline-item {
            position: relative;
            padding-left: 40px;
        }
       
        .timeline-item::before {
            content: '';
            position: absolute;
            left: 12px;
            top: 10px;
            width: 20px;
            height: 20px;
            background: var(--primary);
            border-radius: 50%;
            border: 3px solid #fff;
            box-shadow: 0 0 0 4px rgba(0, 191, 255, 0.2);
        }
       
        .timeline-item::after {
            content: '';
            position: absolute;
            left: 21px;
            top: 30px;
            bottom: -30px;
            width: 2px;
            background: #64748b;
        }
       
        .last-item::after {
            display: none;
        }
       
        .skill-card {
            transition: all 0.3s ease;
        }
       
        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 191, 255, 0.3) !important;
        }
       
        .certificate-card {
            transition: all 0.3s ease;
        }
       
        .footer {
            background: #0f172a;
        }
       
        @media (max-width: 768px) {
            .hero {
                min-height: 80vh;
            }
        }
    </style>
</head>
<body>

    <!-- NAVBAR -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand fw-bold fs-4" href="#">
                <span class="text-info">D</span>ILAN <span class="text-info">L</span>ÓPEZ
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#sobre-mi">Sobre mí</a></li>
                    <li class="nav-item"><a class="nav-link" href="#experiencia">Experiencia</a></li>
                    <li class="nav-item"><a class="nav-link" href="#habilidades">Habilidades</a></li>
                    <li class="nav-item"><a class="nav-link" href="#educacion">Educación</a></li>
                    <li class="nav-item"><a class="nav-link" href="#certificaciones">Certificaciones</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
                </ul>
                <a href="https://wa.me/573103926582" target="_blank" class="btn btn-outline-info ms-3">
                    <i class="bi bi-whatsapp"></i> WhatsApp
                </a>
            </div>
        </div>
    </nav>

    <!-- HERO -->
    <section class="hero" id="hero">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-8">
                    <!-- ✅ NOMBRE CORREGIDO DEFINITIVAMENTE -->
                    <h1 class="hero-name">DILAN SAMIR LÓPEZ ARAUJO</h1>
                    <h2 class="fs-2 text-info mb-4">Tecnólogo en Análisis y Desarrollo de Sistemas</h2>
                    <p class="lead mb-4">Ingeniero de Sistemas (último semestre) • Especialista en análisis de datos, Power BI y Python</p>
                    <p class="mb-5">Ingeniero de sistemas con experiencia en análisis de datos, visualización, gestión documental y desarrollo de soluciones tecnológicas. Comprometido, proactivo y orientado a resultados.</p>
                   
                    <div class="d-flex flex-wrap gap-3">
                        <a href="#contacto" class="btn btn-info btn-lg px-5">Contáctame</a>
                        <a href="https://wa.me/573103926582" target="_blank" class="btn btn-outline-light btn-lg px-5">
                            <i class="bi bi-whatsapp me-2"></i>Hablar por WhatsApp
                        </a>
                        <a href="#" onclick="alert('Descarga tu CV en PDF desde el botón de descarga en la sección de contacto')" class="btn btn-outline-info btn-lg px-5">
                            <i class="bi bi-download me-2"></i>Descargar CV
                        </a>
                    </div>
                   
                    <div class="mt-5 d-flex gap-4 text-muted">
                        <div><i class="bi bi-geo-alt"></i> Bogotá D.C., Colombia</div>
                        <div><i class="bi bi-envelope"></i> dilansamir0712@gmail.com</div>
                        <div><i class="bi bi-telephone"></i> 310 392 6582</div>
                    </div>
                </div>
                <div class="col-lg-4 text-center mt-5 mt-lg-0">
                    <div class="bg-white text-dark rounded-circle mx-auto d-flex align-items-center justify-content-center shadow" style="width: 220px; height: 220px; font-size: 4rem; border: 8px solid #00bfff;">
                        <strong>DL</strong>
                    </div>
                    <p class="text-info mt-3 fw-bold">Ingeniero de Sistemas • Analista de Datos</p>
                </div>
            </div>
        </div>
    </section>

    <!-- El resto del código es exactamente el mismo que me enviaste (no se modificó nada más) -->
    <!-- SOBRE MÍ -->
    <section id="sobre-mi" class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title fs-1">Sobre mí</h2>
            </div>
            <div class="row justify-content-center">
                <div class="col-lg-10">
                    <p class="lead text-center">
                        Ingeniero de sistemas con conocimientos tecnológicos en análisis y desarrollo de sistemas, con conocimientos en <strong>Power BI</strong> y <strong>Python básico</strong>, e inglés B2. Experiencia laboral en análisis de datos, estrategias para visualización de datos, gestión y análisis de información, diseño e implementación de datos para los diferentes procesos organizacionales y programación en Python, así como elaboración de informes de gestión para entes de control.
                    </p>
                    <p class="text-center mt-4">
                        <strong>Competencias:</strong> Compromiso, perseverancia, trabajo en equipo, iniciativa y orientación al detalle.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- EXPERIENCIA LABORAL -->
    <section id="experiencia" class="py-5">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title fs-1">Experiencia Laboral</h2>
            </div>
           
            <div class="row">
                <div class="col-12">
                    <div class="timeline-item mb-5">
                        <div class="d-flex justify-content-between">
                            <h5 class="fw-bold">Analista de Tecnología – Técnico de Sistemas TI</h5>
                            <span class="badge bg-info">Febrero 2025 – Actualidad</span>
                        </div>
                        <p class="text-primary mb-1"><strong>Sonda de Colombia – Proyecto Compensar</strong></p>
                        <ul class="text-muted">
                            <li>Apoyo en análisis de datos y estrategias de visualización para procesos organizacionales.</li>
                            <li>Gestión y análisis de información para entes de control.</li>
                            <li>Elaboración de informes de gestión.</li>
                        </ul>
                    </div>
                   
                    <div class="timeline-item mb-5">
                        <div class="d-flex justify-content-between">
                            <h5 class="fw-bold">Consultor Técnico en Gestión Documental</h5>
                            <span class="badge bg-info">Junio 2024 – Enero 2025</span>
                        </div>
                        <p class="text-primary mb-1"><strong>Memory HUB, Fi Group – España (Remoto, Bogotá)</strong></p>
                        <ul class="text-muted">
                            <li>Gestión documental multitarea en proyectos de I+D+i.</li>
                            <li>Revisión de documentación y justificación técnico-económica.</li>
                            <li>Cálculos de coste/hora, soporte en partes horarios y preparación de memorias.</li>
                        </ul>
                    </div>
                   
                    <div class="timeline-item mb-5">
                        <div class="d-flex justify-content-between">
                            <h5 class="fw-bold">Auxiliar de Sistemas – Ciencia de Datos (LABSIS)</h5>
                            <span class="badge bg-info">Octubre 2023 – Diciembre 2023</span>
                        </div>
                        <p class="text-primary mb-1"><strong>INVEMAR – Instituto de Investigaciones Marinas y Costeras</strong></p>
                        <ul class="text-muted">
                            <li>Análisis de información institucional y custodia de datos.</li>
                            <li>Soporte de bases de datos, programación en Python y generación de informes con Power BI.</li>
                            <li>Organización del proceso de gestión documental.</li>
                            <li>Ascendido de practicante a auxiliar en septiembre 2023.</li>
                        </ul>
                    </div>
                   
                    <div class="timeline-item last-item">
                        <div class="d-flex justify-content-between">
                            <h5 class="fw-bold">Prácticas – Aprendiz SENA</h5>
                            <span class="badge bg-info">Marzo 2023 – Septiembre 2023</span>
                        </div>
                        <p class="text-primary mb-1"><strong>INVEMAR – Instituto de Investigaciones Marinas y Costeras</strong></p>
                        <ul class="text-muted">
                            <li>Estudios en bases de datos, desarrollo de software y análisis de APIs.</li>
                            <li>Proceso de custodia de información institucional.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- HABILIDADES -->
    <section id="habilidades" class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title fs-1">Habilidades Técnicas</h2>
            </div>
            <div class="row g-4">
                <div class="col-md-4 col-sm-6">
                    <div class="card skill-card h-100 text-center border-0 shadow-sm">
                        <div class="card-body">
                            <i class="bi bi-bar-chart-line fs-1 text-info mb-3"></i>
                            <h5>Power BI</h5>
                            <p class="text-muted">Visualización de datos y generación de informes ejecutivos</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="card skill-card h-100 text-center border-0 shadow-sm">
                        <div class="card-body">
                            <i class="bi bi-file-earmark-code fs-1 text-info mb-3"></i>
                            <h5>Python</h5>
                            <p class="text-muted">Programación básica, análisis de datos y automatización</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="card skill-card h-100 text-center border-0 shadow-sm">
                        <div class="card-body">
                            <i class="bi bi-database fs-1 text-info mb-3"></i>
                            <h5>Bases de Datos</h5>
                            <p class="text-muted">Diseño, administración y consultas SQL</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="card skill-card h-100 text-center border-0 shadow-sm">
                        <div class="card-body">
                            <i class="bi bi-folder2 fs-1 text-info mb-3"></i>
                            <h5>Gestión Documental</h5>
                            <p class="text-muted">Organización, custodia y control de información</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="card skill-card h-100 text-center border-0 shadow-sm">
                        <div class="card-body">
                            <i class="bi bi-file-earmark-spreadsheet fs-1 text-info mb-3"></i>
                            <h5>Ofimática Avanzada</h5>
                            <p class="text-muted">Excel, Word, PowerPoint y herramientas de productividad</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="card skill-card h-100 text-center border-0 shadow-sm">
                        <div class="card-body">
                            <i class="bi bi-globe fs-1 text-info mb-3"></i>
                            <h5>Inglés B2</h5>
                            <p class="text-muted">Certificado por SENA – English Dot Works Beginner</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- EDUCACIÓN, CERTIFICACIONES, CONTACTO y FOOTER son exactamente iguales al código que me enviaste -->

    <!-- EDUCACIÓN -->
    <section id="educacion" class="py-5">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title fs-1">Educación</h2>
            </div>
            <div class="row g-4">
                <div class="col-md-6">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="card-title">Ingeniería de Sistemas</h5>
                            <p class="text-info">Corporación Unificada Nacional de Educación Superior – CUN</p>
                            <p class="text-muted">2023 – Actualidad (Décimo semestre nivelatorio – 15 créditos – Modalidad virtual)</p>
                            <small class="text-success">• Periodo 25V01: 03 febrero 2025 – 30 mayo 2025</small>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="card-title">Tecnólogo en Análisis y Desarrollo de Sistemas de Información</h5>
                            <p class="text-info">Servicio Nacional de Aprendizaje – SENA</p>
                            <p class="text-muted">2023</p>
                            <a href="#" class="btn btn-sm btn-outline-info">Ver título</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CERTIFICACIONES -->
    <section id="certificaciones" class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title fs-1">Certificaciones y Constancias</h2>
            </div>
            <div class="row g-4">
                <div class="col-lg-4 col-md-6">
                    <div class="card certificate-card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="text-primary">Bootcamp Análisis de Datos Nivel Básico</h5>
                            <p class="text-muted">Ministerio TIC – UT Innova Digital • 159 horas</p>
                            <small>Marzo 2026</small>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="card certificate-card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="text-primary">Tecnólogo en Análisis y Desarrollo de Sistemas de Información</h5>
                            <p class="text-muted">SENA • Registrado electrónicamente</p>
                            <small>13 de octubre de 2023</small>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="card certificate-card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="text-primary">Certificación Académica 10° Semestre</h5>
                            <p class="text-muted">CUN – Ingeniería de Sistemas</p>
                            <small>20 de enero de 2025</small>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="card certificate-card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="text-primary">Contrato Aprendizaje + Auxiliar de Sistemas</h5>
                            <p class="text-muted">INVEMAR – GEZ (Ciencia de Datos)</p>
                            <small>Marzo – Diciembre 2023</small>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="card certificate-card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="text-primary">Contrato Laboral a Término Fijo</h5>
                            <p class="text-muted">INVEMAR – Auxiliar de Investigación</p>
                            <small>Octubre – Diciembre 2023</small>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="card certificate-card h-100 shadow-sm">
                        <div class="card-body">
                            <h5 class="text-primary">English Dot Works Beginner</h5>
                            <p class="text-muted">SENA • 60 horas</p>
                            <small>Diciembre 2020</small>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTACTO -->
    <section id="contacto" class="py-5">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title fs-1">Contáctame</h2>
                <p class="lead">Estoy disponible para proyectos freelance en análisis de datos, Power BI, Python y gestión documental.</p>
            </div>
           
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="card shadow">
                        <div class="card-body p-5">
                            <div class="row">
                                <div class="col-md-6 mb-4">
                                    <h5><i class="bi bi-telephone-fill text-info"></i> Teléfono / WhatsApp</h5>
                                    <a href="https://wa.me/573103926582" target="_blank" class="fs-3 text-decoration-none">310 392 6582</a>
                                </div>
                                <div class="col-md-6 mb-4">
                                    <h5><i class="bi bi-envelope-fill text-info"></i> Correo electrónico</h5>
                                    <a href="mailto:dilansamir0712@gmail.com" class="fs-3 text-decoration-none">dilansamir0712@gmail.com</a>
                                </div>
                                <div class="col-12">
                                    <h5 class="mb-3">Ubicación</h5>
                                    <p class="fs-5">Bogotá D.C., Colombia</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="footer py-5 text-white">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <p>© 2026 Dilan Samir López Araujo. Todos los derechos reservados.</p>
                    <p class="small">Desarrollado con ❤️ y Flask para mi perfil de Freelancer</p>
                </div>
                <div class="col-md-6 text-md-end">
                    <a href="https://www.linkedin.com/in/dilanlopez" target="_blank" class="text-white mx-2"><i class="bi bi-linkedin fs-3"></i></a>
                    <a href="https://github.com/tuusuario" target="_blank" class="text-white mx-2"><i class="bi bi-github fs-3"></i></a>
                    <p class="small mt-3">Listo para nuevos desafíos en análisis de datos y desarrollo de sistemas</p>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // Smooth scroll para los enlaces del navbar
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                if (this.getAttribute('href') !== '#') {
                    e.preventDefault();
                    const target = document.querySelector(this.getAttribute('href'));
                    if (target) {
                        target.scrollIntoView({ behavior: 'smooth' });
                    }
                }
            });
        });
    </script>
</body>
</html>
