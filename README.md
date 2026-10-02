<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instituto Superior de La Vega | Excelencia Educativa</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="header">
        <div class="container header-container">
            <a href="#inicio" class="logo">
                <img src="imagenes/logo.png" alt="Logo Pequeño">
                <span class="logo-text">Instituto Superior de La Vega</span>
            </a>
            <input type="checkbox" id="menu-toggle" class="menu-toggle">
            <label for="menu-toggle" class="menu-icon">&#9776;</label>
            <nav class="nav-menu">
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#docentes">Docentes</a></li>
                    <li><a href="#estudiantes">Estudiantes</a></li>
                    <li><a href="#cursos">Cursos</a></li>
                    <li><a href="#inscripcion" class="btn-nav">Inscripción</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main style="padding-top: 70px;">
        
        <section id="inicio" class="hero">
            <div class="hero-overlay"></div>
            <div class="container hero-content-wrapper">
                
                <div class="hero-logo-box">
                    <img src="imagenes/logo.png" alt="Logo Instituto Superior de La Vega">
                </div>
                
                <div class="hero-text-box">
                    <p class="hero-subtitle">Transformando el futuro a través de la tecnología</p>
                    <h1 class="hero-title">Educación Superior de Excelencia</h1>
                    <p class="hero-text">Formamos profesionales líderes con las herramientas tecnológicas más avanzadas del mercado. Tu camino hacia el éxito comienza aquí.</p>
                    <div class="hero-buttons">
                        <a href="#cursos" class="btn btn-primary">Ver Cursos</a>
                        <a href="#inscripcion" class="btn btn-secondary">Inscribirme Ahora</a>
                    </div>
                </div>
                
            </div>
        </section>

        <section class="institucion section container">
            <div class="institucion-header">
                <h2>Bienvenidos al Instituto Superior de La Vega</h2>
                <p>Somos una institución dedicada a la excelencia académica, enfocada en carreras tecnológicas y herramientas modernas que demandan las empresas globales.</p>
            </div>
            <div class="institucion-grid">
                <article class="institucion-card">
                    <div class="icon-circle">M</div>
                    <h3>Nuestra Misión</h3>
                    <p>Proveer educación tecnológica de vanguardia, desarrollando profesionales altamente capacitados, éticos e innovadores que aporten al crecimiento de la sociedad.</p>
                </article>
                <article class="institucion-card">
                    <div class="icon-circle">V</div>
                    <h3>Nuestra Visión</h3>
                    <p>Ser reconocidos internacionalmente como el instituto líder en innovación educativa y formación técnica superior en la República Dominicana.</p>
                </article>
            </div>
        </section>

        <section id="docentes" class="docentes section bg-white-section">
            <div class="container">
                <div class="split-layout">
                    <div class="split-image">
                        <img src="imagenes/docentes.jpg" alt="Equipo de docentes en reunión de planificación">
                    </div>
                    <div class="split-content">
                        <h2>Cuerpo Docente</h2>
                        <p class="section-desc">Nuestros profesores son expertos activos en la industria tecnológica. Al unirte a nuestro equipo docente, accedes a un entorno de crecimiento continuo.</p>
                        <div class="feature-grid">
                            <div class="feature-item">
                                <h4>Planificación Académica</h4>
                                <p>Herramientas modernas para estructurar tus clases.</p>
                            </div>
                            <div class="feature-item">
                                <h4>Gestión de Clases</h4>
                                <p>Aulas equipadas con tecnología de última generación.</p>
                            </div>
                            <div class="feature-item">
                                <h4>Seguimiento Estudiantil</h4>
                                <p>Sistemas integrados para monitorear el progreso.</p>
                            </div>
                            <div class="feature-item">
                                <h4>Capacitación Profesional</h4>
                                <p>Programas de actualización técnica constante.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="estudiantes" class="estudiantes section container">
            <div class="split-layout reverse">
                <div class="split-image">
                    <img src="imagenes/estudiantes.jpg" alt="Estudiantes trabajando en un laboratorio de computación">
                </div>
                <div class="split-content">
                    <h2>Vida Estudiantil</h2>
                    <p class="section-desc">Ser estudiante en el Instituto Superior de La Vega significa ser parte de una comunidad dinámica. Ofrecemos todos los servicios necesarios para tu desarrollo integral.</p>
                    <div class="cards-grid-2">
                        <article class="service-card">
                            <h4>Biblioteca Virtual</h4>
                            <p>Miles de recursos, libros y papers a tu disposición 24/7.</p>
                        </article>
                        <article class="service-card">
                            <h4>Orientación Académica</h4>
                            <p>Asesoría personalizada para tu plan de carrera.</p>
                        </article>
                        <article class="service-card">
                            <h4>Laboratorios Tech</h4>
                            <p>Equipos de alto rendimiento para prácticas reales.</p>
                        </article>
                        <article class="service-card">
                            <h4>Clubes Estudiantiles</h4>
                            <p>Hackathons, torneos de e-sports y proyectos colaborativos.</p>
                        </article>
                    </div>
                </div>
            </div>
        </section>

        <section id="cursos" class="cursos section bg-white-section">
            <div class="container">
                <div class="section-header text-center">
                    <h2>Cursos Tecnológicos</h2>
                    <p>Descubre nuestros programas diseñados para las demandas del mercado laboral actual.</p>
                </div>
                <div class="courses-grid">
                    
                    <article class="course-card">
                        <div class="course-img"><img src="imagenes/programacion-web.jpg" alt="Programación Web"></div>
                        <div class="course-content">
                            <h3>Programación Web</h3>
                            <p>Aprende los fundamentos del desarrollo de aplicaciones web utilizando tecnologías modernas.</p>
                            <div class="course-meta">
                                <span><strong>Duración:</strong> 6 meses</span>
                                <span><strong>Modalidad:</strong> Presencial / Virtual</span>
                            </div>
                            <a href="#inscripcion" class="btn btn-outline">Más información</a>
                        </div>
                    </article>

                    <article class="course-card">
                        <div class="course-img"><img src="imagenes/diseno-sistemas.jpg" alt="Diseño de Sistemas"></div>
                        <div class="course-content">
                            <h3>Diseño de Sistemas</h3>
                            <p>Domina el análisis, estructuración y arquitectura de software utilizando patrones de diseño.</p>
                            <div class="course-meta">
                                <span><strong>Duración:</strong> 4 meses</span>
                                <span><strong>Modalidad:</strong> Virtual</span>
                            </div>
                            <a href="#inscripcion" class="btn btn-outline">Más información</a>
                        </div>
                    </article>

                    <article class="course-card">
                        <div class="course-img"><img src="imagenes/base-datos.jpg" alt="Base de Datos"></div>
                        <div class="course-content">
                            <h3>Base de Datos</h3>
                            <p>Diseña, administra y optimiza bases de datos relacionales y no relacionales con SQL y NoSQL.</p>
                            <div class="course-meta">
                                <span><strong>Duración:</strong> 3 meses</span>
                                <span><strong>Modalidad:</strong> Presencial</span>
                            </div>
                            <a href="#inscripcion" class="btn btn-outline">Más información</a>
                        </div>
                    </article>

                    <article class="course-card">
                        <div class="course-img"><img src="imagenes/redes.jpg" alt="Redes de Computadoras"></div>
                        <div class="course-content">
                            <h3>Redes de Computadoras</h3>
                            <p>Configuración de equipos, protocolos de enrutamiento y administración de servidores.</p>
                            <div class="course-meta">
                                <span><strong>Duración:</strong> 5 meses</span>
                                <span><strong>Modalidad:</strong> Presencial</span>
                            </div>
                            <a href="#inscripcion" class="btn btn-outline">Más información</a>
                        </div>
                    </article>

                    <article class="course-card">
                        <div class="course-img"><img src="imagenes/programacion-movil.jpg" alt="Programación Móvil"></div>
                        <div class="course-content">
                            <h3>Programación Móvil</h3>
                            <p>Crea aplicaciones nativas y multiplataforma para iOS y Android con interfaces responsivas.</p>
                            <div class="course-meta">
                                <span><strong>Duración:</strong> 6 meses</span>
                                <span><strong>Modalidad:</strong> Virtual</span>
                            </div>
                            <a href="#inscripcion" class="btn btn-outline">Más información</a>
                        </div>
                    </article>

                    <article class="course-card">
                        <div class="course-img"><img src="imagenes/ofimatica.jpg" alt="Ofimática Avanzada"></div>
                        <div class="course-content">
                            <h3>Ofimática Avanzada</h3>
                            <p>Maximiza tu productividad corporativa dominando Excel, textos y presentaciones de alto impacto.</p>
                            <div class="course-meta">
                                <span><strong>Duración:</strong> 2 meses</span>
                                <span><strong>Modalidad:</strong> Presencial / Virtual</span>
                            </div>
                            <a href="#inscripcion" class="btn btn-outline">Más información</a>
                        </div>
                    </article>

                </div>
            </div>
        </section>

        <section id="inscripcion" class="inscripcion section container">
            <div class="form-container">
                <div class="form-header">
                    <h2>Formulario de Inscripción</h2>
                    <p>Completa tus datos para iniciar el proceso de admisión.</p>
                </div>
                <form class="registro-form" action="#" method="POST">
                    
                    <div class="form-row">
                        <div class="form-group">
                            <label for="nombre">Nombre <span class="required">*</span></label>
                            <input type="text" id="nombre" name="nombre" placeholder="Ej. Juan Rafael" required>
                        </div>
                        <div class="form-group">
                            <label for="apellido">Apellido <span class="required">*</span></label>
                            <input type="text" id="apellido" name="apellido" placeholder="Ej. Pérez" required>
                        </div>
                    </div>

                    <div class="form-row">
                        <div class="form-group">
                            <label for="cedula">Cédula del Estudiante <span class="required">*</span></label>
                            <input type="text" id="cedula" name="cedula" placeholder="11 dígitos (Sin guiones)" required pattern="[0-9]{11}" maxlength="11" title="La cédula debe contener exactamente 11 números, sin guiones ni letras.">
                        </div>
                        <div class="form-group">
                            <label for="fecha">Fecha de Nacimiento <span class="required">*</span></label>
                            <input type="date" id="fecha" name="fecha" required>
                        </div>
                    </div>

                    <div class="form-row">
                        <div class="form-group">
                            <label for="correo">Correo Electrónico <span class="required">*</span></label>
                            <input type="email" id="correo" name="correo" placeholder="correo@ejemplo.com" required>
                        </div>
                        <div class="form-group">
                            <label for="telefono">Teléfono / Celular <span class="required">*</span></label>
                            <input type="tel" id="telefono" name="telefono" placeholder="10 dígitos (Sin guiones)" required pattern="[0-9]{10}" maxlength="10" title="El teléfono debe contener exactamente 10 números, sin guiones ni letras.">
                        </div>
                    </div>

                    <div class="form-group full-width">
                        <label for="direccion">Dirección Completa</label>
                        <input type="text" id="direccion" name="direccion" placeholder="Calle, Número, Sector, Ciudad">
                    </div>

                    <div class="form-row">
                        <div class="form-group">
                            <label for="curso">Curso de Interés <span class="required">*</span></label>
                            <select id="curso" name="curso" required>
                                <option value="" disabled selected>Seleccione un curso...</option>
                                <option value="web">Programación Web</option>
                                <option value="sistemas">Diseño de Sistemas</option>
                                <option value="bd">Base de Datos</option>
                                <option value="redes">Redes de Computadoras</option>
                                <option value="movil">Programación Móvil</option>
                                <option value="ofimatica">Ofimática Avanzada</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="modalidad">Modalidad de Estudio <span class="required">*</span></label>
                            <select id="modalidad" name="modalidad" required>
                                <option value="" disabled selected>Seleccione modalidad...</option>
                                <option value="presencial">Presencial</option>
                                <option value="virtual">Virtual</option>
                            </select>
                        </div>
                    </div>

                    <fieldset class="form-group full-width radio-group">
                        <legend>Sexo</legend>
                        <div class="radio-options">
                            <label><input type="radio" name="sexo" value="masculino" checked> Masculino</label>
                            <label><input type="radio" name="sexo" value="femenino"> Femenino</label>
                        </div>
                    </fieldset>

                    <div class="form-group full-width">
                        <label for="comentarios">Comentarios Adicionales</label>
                        <textarea id="comentarios" name="comentarios" rows="3" placeholder="¿Tienes alguna duda o requerimiento especial?"></textarea>
                    </div>

                    <div class="form-group full-width checkbox-group">
                        <label>
                            <input type="checkbox" name="terminos" required> 
                            Acepto las políticas de privacidad y términos de la institución.
                        </label>
                    </div>

                    <div class="form-submit">
                        <button type="submit" class="btn btn-primary btn-block">Enviar Solicitud de Inscripción</button>
                    </div>
                </form>
            </div>
        </section>

        <section id="contacto" class="contacto section bg-dark text-white">
            <div class="container">
                <div class="contacto-grid">
                    <div class="contacto-info">
                        <h2>Contacto</h2>
                        <p>¿Tienes dudas? Visítanos o comunícate con nosotros, nuestro equipo está listo para ayudarte.</p>
                        
                        <div class="info-item">
                            <span class="info-label">Dirección:</span>
                            <p>Av. Principal #13, La Vega, República Dominicana.</p>
                        </div>
                        <div class="info-item">
                            <span class="info-label">Teléfono:</span>
                            <p>(809) 242-7000</p>
                        </div>
                        <div class="info-item">
                            <span class="info-label">Correo:</span>
                            <p>info@institutosuperiorlavega.edu.do</p>
                        </div>
                        <div class="info-item">
                            <span class="info-label">Horario:</span>
                            <p>Lunes a viernes: 8:00 AM - 5:00 PM</p>
                        </div>
                    </div>

                    <div class="contacto-social">
                        <h3>Síguenos en Redes</h3>
                        <div class="social-links">
                            <a href="#" class="social-card">
                                <span>Facebook</span>
                                <small>@InstitutoSuperiorLaVega</small>
                            </a>
                            <a href="#" class="social-card">
                                <span>Instagram</span>
                                <small>@is_lavega</small>
                            </a>
                            <a href="#" class="social-card">
                                <span>YouTube</span>
                                <small>InsLaVega</small>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="footer">
        <div class="container footer-content">
            <div class="footer-logo">
                <strong>Instituto Superior de La Vega</strong>
                <p>Formando líderes tecnológicos desde 2026.</p>
            </div>
            <div class="footer-links">
                <a href="#inicio">Inicio</a>
                <a href="#cursos">Cursos</a>
                <a href="#inscripcion">Inscripción</a>
                <a href="#contacto">Contacto</a>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 Instituto Superior de La Vega. Todos los derechos reservados.</p>
        </div>
    </footer>

</body>
</html>

/* =========================
   VARIABLES (Paleta del Logo)
========================= */
:root {
    --primary: #0c2340;
    --green-logo: #245236;
    --accent: #c49027;
    
    --secondary: #ced4da;
    --text-main: #212529;
    --bg-body: #f4f7f6;
    --bg-white: #ffffff;
    --gray: #6c757d;
    --gray-dark: #343a40;
    --red: #ca3120;
    
    --shadow-navbar: 0 0 20px rgba(0, 0, 0, .1);
    --shadow-navbar-inner: 0 2px 4px rgba(0, 0, 0, .08);
    --shadow-card: 0 2px 4px rgba(0, 0, 0, .08);
    --shadow-card-hover: 0 10px 20px rgba(0, 0, 0, .12);
    
    --radius: 8px;
    --transition: all 0.3s ease;
}

/* =========================
   RESET & GLOBAL
========================= */
*, *::before, *::after {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    line-height: 1.15;
    -webkit-text-size-adjust: 100%;
}

body {
    margin: 0;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: .9375rem;
    font-weight: 400;
    line-height: 1.6;
    color: var(--text-main);
    text-align: left;
    background-color: var(--bg-body);
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

img {
    max-width: 100%;
    height: auto;
    display: block;
}

a {
    text-decoration: none;
    color: inherit;
    transition: var(--transition);
}

ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}

.section {
    padding: 5rem 0;
}

.bg-white-section {
    background-color: var(--bg-white);
}

.bg-dark {
    background-color: var(--primary);
}

.text-white {
    color: var(--bg-white);
}

.text-center {
    text-align: center;
}

/* BOTONES */
.btn {
    display: inline-block;
    padding: 0.8rem 1.5rem;
    border-radius: var(--radius);
    font-weight: bold;
    text-align: center;
    cursor: pointer;
    border: 2px solid transparent;
    transition: var(--transition);
}

.btn-primary {
    background-color: var(--accent);
    color: var(--bg-white);
}

.btn-primary:hover {
    background-color: #a3751e;
    transform: translateY(-2px);
    box-shadow: var(--shadow-card);
}

.btn-secondary {
    background-color: transparent;
    color: var(--bg-white);
    border-color: var(--bg-white);
}

.btn-secondary:hover {
    background-color: var(--bg-white);
    color: var(--primary);
}

.btn-outline {
    background-color: transparent;
    color: var(--primary);
    border-color: var(--primary);
}

.btn-outline:hover {
    background-color: var(--primary);
    color: var(--bg-white);
}

.btn-block {
    display: block;
    width: 100%;
    padding: 1rem;
}

/* =========================
   HEADER
========================= */
.header {
    height: 70px; /* Forzando que ocupe de la línea rosada a la línea rosada */
    min-height: 70px;
    max-height: 70px;
    background-color: #fff;
    -webkit-box-shadow: 5px 0 10px rgba(0, 0, 0, .1);
    box-shadow: var(--shadow-navbar);
    position: fixed;
    top: 0;
    right: 0;
    left: 0;
    z-index: 1030;
    display: flex;
    align-items: center;
}

.header::after {
    content: '';
    position: absolute;
    bottom: 0; left: 0; right: 0;
    box-shadow: var(--shadow-navbar-inner);
    height: 1px;
}

.header-container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    height: 100%; /* Toma la altura completa de .header */
    padding: 0 1rem;
}

.logo {
    display: flex;
    align-items: center;
    height: 100%; /* Toma la altura completa del nav */
    gap: 10px;
}

.logo img {
    height: 100%; /* Ocupará el 100% de la barra blanca sin sobresalir */
    max-height: 100%;
    width: auto;
    object-fit: contain;
}

.logo-text {
    font-size: 1.25rem;
    font-weight: bold;
    color: var(--primary);
}

.nav-menu ul {
    display: flex;
    flex-flow: row nowrap;
    align-items: center;
    gap: 1.5rem;
}

.nav-menu a {
    font-weight: normal;
    color: var(--gray-dark);
    font-size: 0.95rem;
}

.nav-menu a:hover {
    color: var(--green-logo);
}

.btn-nav {
    background-color: var(--primary);
    color: var(--bg-white) !important;
    padding: 0.5rem 1.2rem;
    border-radius: 4px;
    font-weight: bold;
}

.btn-nav:hover {
    background-color: var(--green-logo);
}

.menu-toggle, .menu-icon {
    display: none;
}

/* =========================
   HERO / INICIO
========================= */
.hero {
    position: relative;
    background-image: url('imagenes/institucion.jpg');
    background-color: var(--primary);
    background-size: cover;
    background-position: center;
    min-height: calc(100vh - 70px); /* Ocupa completamente el espacio blanco vacío hacia abajo según las líneas amarillas */
    width: 100%;
    display: flex;
    align-items: center;
    padding: 4rem 0;
}

.hero-overlay {
    position: absolute;
    top: 0; left: 0; width: 100%; height: 100%;
    background: rgba(0, 0, 0, 0.4); 
}

.hero-content-wrapper {
    position: relative;
    z-index: 1;
    display: grid;
    grid-template-columns: 1fr 1.2fr;
    gap: 3rem;
    align-items: center;
    width: 100%;
}

.hero-logo-box {
    display: flex;
    justify-content: flex-start;
}

.hero-logo-box img {
    width: 100%;
    max-width: 480px;
    height: auto;
    display: block;
}

.hero-text-box {
    color: var(--bg-white);
}

.hero-subtitle {
    font-size: 1rem;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-bottom: 1rem;
    color: var(--accent);
    font-weight: bold;
}

.hero-title {
    font-size: 2.5rem;
    line-height: 1.3;
    margin-bottom: 1.5rem;
    font-weight: bold;
}

.hero-text {
    font-size: 1.05rem;
    margin-bottom: 2rem;
    opacity: 0.9;
}

.hero-buttons {
    display: flex;
    gap: 1rem;
}

/* =========================
   MISION & VISIÓN
========================= */
.institucion-header {
    text-align: center;
    max-width: 800px;
    margin: 0 auto 3rem;
}

.institucion-header h2 {
    font-size: 2rem;
    color: var(--primary);
    margin-bottom: 1rem;
    font-weight: bold;
}

.institucion-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 2rem;
}

.institucion-card {
    background: var(--bg-white);
    padding: 2.5rem;
    border-radius: var(--radius);
    box-shadow: var(--shadow-card);
    text-align: center;
    border-top: 4px solid var(--green-logo);
    transition: var(--transition);
}

.institucion-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-card-hover);
}

.icon-circle {
    width: 60px;
    height: 60px;
    background-color: var(--bg-body);
    color: var(--primary);
    font-size: 1.5rem;
    font-weight: bold;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    margin: 0 auto 1.5rem;
}

.institucion-card h3 {
    margin-bottom: 1rem;
    color: var(--primary);
}

/* =========================
   SPLIT LAYOUT (Docentes/Estudiantes)
========================= */
.split-layout {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
}

.split-layout.reverse .split-content {
    order: -1;
}

.split-image img {
    border-radius: var(--radius);
    box-shadow: var(--shadow-card-hover);
    width: 100%;
    object-fit: cover;
    height: 400px;
}

.split-content h2 {
    font-size: 2rem;
    color: var(--primary);
    margin-bottom: 1rem;
}

.section-desc {
    color: var(--gray);
    margin-bottom: 2rem;
}

.feature-grid, .cards-grid-2 {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1.5rem;
}

.feature-item, .service-card {
    background: var(--bg-white);
    padding: 1.25rem;
    border-radius: var(--radius);
    box-shadow: var(--shadow-card);
    border-left: 3px solid var(--primary);
}

.service-card {
    border-left: none;
    border-bottom: 3px solid var(--accent);
    text-align: center;
    transition: var(--transition);
}

.service-card:hover {
    transform: translateY(-3px);
    box-shadow: var(--shadow-card-hover);
}

.feature-item h4, .service-card h4 {
    color: var(--primary);
    margin-bottom: 0.5rem;
    font-size: 1rem;
}

.feature-item p, .service-card p {
    font-size: 0.85rem;
    color: var(--gray);
    margin: 0;
}

/* =========================
   CURSOS 
========================= */
.section-header {
    margin-bottom: 3rem;
}

.section-header h2 {
    font-size: 2.2rem;
    color: var(--primary);
    margin-bottom: 0.5rem;
}

.courses-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
}

.course-card {
    background: var(--bg-white);
    border-radius: var(--radius);
    overflow: hidden;
    box-shadow: var(--shadow-card);
    transition: var(--transition);
    display: flex;
    flex-direction: column;
}

.course-card:hover {
    transform: translateY(-8px);
    box-shadow: var(--shadow-card-hover);
}

.course-img {
    height: 180px;
    background-color: var(--primary);
    overflow: hidden;
}

.course-img img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.4s ease;
}

.course-card:hover .course-img img {
    transform: scale(1.05);
}

.course-content {
    padding: 1.5rem;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
}

.course-content h3 {
    color: var(--primary);
    margin-bottom: 0.5rem;
    font-size: 1.15rem;
    font-weight: bold;
}

.course-content p {
    color: var(--gray);
    font-size: 0.9rem;
    margin-bottom: 1.5rem;
    flex-grow: 1;
}

.course-meta {
    background: var(--bg-body);
    padding: 0.8rem;
    border-radius: 4px;
    margin-bottom: 1.5rem;
    display: flex;
    flex-direction: column;
    gap: 0.3rem;
    font-size: 0.85rem;
    color: var(--primary);
}

/* =========================
   INSCRIPCIÓN (FORMULARIO)
========================= */
.form-container {
    background: var(--bg-white);
    padding: 3rem;
    border-radius: var(--radius);
    box-shadow: var(--shadow-card);
    max-width: 900px;
    margin: 0 auto;
    border-top: 4px solid var(--accent);
}

.form-header h2 {
    color: var(--primary);
    font-size: 2rem;
    margin-bottom: 0.5rem;
}

.form-header p {
    color: var(--gray);
    margin-bottom: 2rem;
}

.registro-form .form-row {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1.5rem;
    margin-bottom: 1.25rem;
}

.form-group {
    display: flex;
    flex-direction: column;
}

.form-group.full-width {
    margin-bottom: 1.25rem;
}

.form-group label, .form-group legend {
    font-weight: bold;
    margin-bottom: 0.5rem;
    color: var(--gray-dark);
    font-size: 0.9rem;
}

.required {
    color: var(--red);
}

.registro-form input[type="text"],
.registro-form input[type="email"],
.registro-form input[type="number"],
.registro-form input[type="tel"],
.registro-form input[type="date"],
.registro-form select,
.registro-form textarea {
    padding: 0.8rem;
    border: 1px solid var(--secondary);
    border-radius: 4px;
    font-family: inherit;
    font-size: 0.95rem;
    transition: var(--transition);
    background-color: var(--bg-body);
}

.registro-form input:focus,
.registro-form select:focus,
.registro-form textarea:focus {
    outline: none;
    border-color: var(--primary);
    box-shadow: 0 0 0 3px rgba(12, 35, 64, 0.15);
    background-color: var(--bg-white);
}

.radio-group {
    border: 1px solid var(--secondary);
    padding: 1rem;
    border-radius: 4px;
    background-color: var(--bg-body);
}

.radio-options {
    display: flex;
    gap: 2rem;
}

.radio-options label {
    font-weight: normal;
    font-size: 0.9rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    cursor: pointer;
}

.checkbox-group label {
    font-size: 0.9rem;
    cursor: pointer;
}

/* =========================
   CONTACTO
========================= */
.contacto-grid {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 4rem;
}

.contacto-info h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

.contacto-info > p {
    margin-bottom: 2rem;
    color: var(--secondary);
}

.info-item {
    margin-bottom: 1.25rem;
    background: rgba(255, 255, 255, 0.05);
    padding: 1rem;
    border-radius: var(--radius);
    border-left: 3px solid var(--accent);
}

.info-label {
    display: block;
    font-weight: bold;
    color: var(--accent);
    margin-bottom: 0.25rem;
}

.contacto-social h3 {
    margin-bottom: 1.5rem;
}

.social-links {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.social-card {
    background: rgba(255, 255, 255, 0.1);
    padding: 1rem;
    border-radius: var(--radius);
    display: flex;
    flex-direction: column;
}

.social-card:hover {
    background: var(--green-logo);
    transform: translateX(5px);
}

.social-card span {
    font-weight: bold;
    font-size: 1rem;
}

.social-card small {
    color: var(--secondary);
}

/* =========================
   FOOTER
========================= */
.footer {
    background-color: #06111f;
    color: var(--bg-white);
    padding: 2.5rem 0 1rem;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid rgba(255,255,255,0.1);
    padding-bottom: 1.5rem;
    margin-bottom: 1.5rem;
}

.footer-logo strong {
    font-size: 1.3rem;
    display: block;
    margin-bottom: 0.25rem;
    color: var(--accent);
}

.footer-logo p {
    color: var(--secondary);
    font-size: 0.9rem;
}

.footer-links {
    display: flex;
    gap: 1.5rem;
}

.footer-links a {
    color: var(--secondary);
    font-size: 0.9rem;
}

.footer-links a:hover {
    color: var(--bg-white);
}

.footer-bottom {
    text-align: center;
    color: var(--gray);
    font-size: 0.85rem;
}

/* =========================
   RESPONSIVE DESIGN (MEDIA QUERIES)
========================= */
@media (max-width: 1200px) {
    body { font-size: calc(0.90375rem + 0.045vw); }
}

@media (max-width: 992px) {
    .courses-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 768px) {
    .menu-icon {
        display: block;
        font-size: 1.5rem;
        cursor: pointer;
        color: var(--primary);
    }
    
    .nav-menu {
        position: absolute;
        top: 70px;
        left: 0;
        width: 100%;
        background-color: var(--bg-white);
        box-shadow: var(--shadow-navbar);
        display: none;
        flex-direction: column;
        padding: 1rem 0;
    }
    
    .nav-menu ul {
        flex-direction: column;
        gap: 0;
    }
    
    .nav-menu a {
        display: block;
        padding: 1rem;
        border-bottom: 1px solid var(--secondary);
        text-align: center;
    }
    
    .btn-nav {
        background-color: transparent;
        color: var(--primary) !important;
    }

    #menu-toggle:checked ~ .nav-menu {
        display: flex;
    }

    .hero-title { font-size: 2.2rem; }
    .hero-buttons { flex-direction: column; }
    
    .hero-content-wrapper {
        grid-template-columns: 1fr;
        text-align: center;
    }

    .hero-logo-box {
        justify-content: center;
    }

    .hero-logo-box img {
        max-width: 350px;
    }
    
    .institucion-grid,
    .split-layout,
    .cards-grid-2,
    .feature-grid,
    .courses-grid,
    .registro-form .form-row,
    .contacto-grid {
        grid-template-columns: 1fr;
        gap: 1.5rem;
    }
    
    .split-layout.reverse .split-content { order: 0; }
    .form-container { padding: 1.5rem; }
    .footer-content { flex-direction: column; text-align: center; gap: 1.5rem; }
}

<img width="736" height="491" alt="estudiantes" src="https://github.com/user-attachments/assets/e8c14f79-251c-46d3-8b07-e799a021e6e5" />
<img width="735" height="490" alt="docentes" src="https://github.com/user-attachments/assets/e31bdbb4-ec26-46c1-943d-cbc87aff3e4b" />
<img width="735" height="508" alt="diseno-sistemas" src="https://github.com/user-attachments/assets/e3a4cc95-68f2-4543-9a33-ae56f853004c" />
<img width="550" height="412" alt="base-datos" src="https://github.com/user-attachments/assets/a3753082-a0d9-4c6d-88f2-0bf31a8fe407" />
<img width="736" height="414" alt="redes" src="https://github.com/user-attachments/assets/56788e11-9ec1-4a23-b4b3-d47f3749077e" />
<img width="736" height="736" alt="programacion-web" src="https://github.com/user-attachments/assets/aebb950d-3fb4-4302-9d3d-007810214fb4" />
<img width="735" height="503" alt="programacion-movil" src="https://github.com/user-attachments/assets/7f645002-5ec8-4b0b-aa5d-629cea9e4191" />
<img width="735" height="490" alt="ofimatica" src="https://github.com/user-attachments/assets/f4d6ce4c-9b79-4961-b5a8-25dcbd2340de" />
<img width="1254" height="1254" alt="LOGO" src="https://github.com/user-attachments/assets/6ff81415-3524-46f9-88e9-3ba18c8a5428" />
<img width="736" height="448" alt="institucion" src="https://github.com/user-attachments/assets/e6ea0d40-f2cc-4526-937a-0dd2ce9801f9" />
