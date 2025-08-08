<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alicia Norambuena | GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #5e35b1;
            --secondary: #7e57c2;
            --accent: #ff4081;
            --light: #f5f5f7;
            --dark: #121212;
            --gray: #424242;
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            border-radius: 12px;
            margin-bottom: 30px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }
        
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid white;
            margin: 0 auto 20px;
            background-color: #e0e0e0;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
            color: var(--primary);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            font-weight: 600;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 15px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
        }
        
        .badge {
            background: rgba(255, 255, 255, 0.2);
            padding: 6px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 5px;
        }
        
        section {
            background: white;
            border-radius: 12px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
        }
        
        h2 {
            color: var(--primary);
            margin-bottom: 25px;
            font-size: 1.8rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
        }
        
        .card {
            background: var(--light);
            border-radius: 10px;
            padding: 20px;
            transition: var(--transition);
            border: 1px solid rgba(0, 0, 0, 0.05);
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
        }
        
        .card h3 {
            color: var(--secondary);
            margin-bottom: 15px;
            font-size: 1.3rem;
        }
        
        .tech-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }
        
        .tech-item {
            background: rgba(94, 53, 177, 0.1);
            color: var(--primary);
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
        }
        
        .social-link {
            display: flex;
            align-items: center;
            gap: 8px;
            text-decoration: none;
            color: var(--primary);
            padding: 10px 20px;
            border-radius: 8px;
            transition: var(--transition);
            border: 1px solid rgba(94, 53, 177, 0.2);
        }
        
        .social-link:hover {
            background: rgba(94, 53, 177, 0.05);
            transform: translateY(-3px);
        }
        
        .time-badge {
            background: var(--accent);
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            margin-top: 20px;
            font-weight: 500;
        }
        
        footer {
            text-align: center;
            padding: 30px;
            color: var(--gray);
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .grid {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            header {
                padding: 30px 15px;
            }
            
            section {
                padding: 25px 15px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="profile-pic">
            <i class="fas fa-user"></i>
        </div>
        <h1>Alicia Norambuena</h1>
        <p class="tagline">Desarrolladora Full Stack & Especialista UX/UI | Estudiante de Ingeniería en Informática</p>
        
        <div class="badges">
            <div class="badge">
                <i class="fas fa-graduation-cap"></i>
                Técnica en Telecomunicaciones
            </div>
            <div class="badge">
                <i class="fas fa-map-marker-alt"></i>
                Santiago, Chile
            </div>
            <div class="badge">
                <i class="fas fa-certificate"></i>
                13+ Certificaciones
            </div>
        </div>
    </header>
    
    <section>
        <h2><i class="fas fa-user"></i> Perfil Profesional</h2>
        <p>Estudiante de último año de Ingeniería en Informática (INACAP) con especialización en UX/UI y desarrollo full stack. Apasionada por crear experiencias de usuario intuitivas y soluciones tecnológicas centradas en el usuario. Busco oportunidades de práctica profesional para aplicar mis habilidades técnicas y de diseño en proyectos innovadores.</p>
    </section>
    
    <section>
        <h2><i class="fas fa-laptop-code"></i> Habilidades Técnicas</h2>
        <div class="grid">
            <div class="card">
                <h3>UX/UI & Frontend</h3>
                <div class="tech-list">
                    <span class="tech-item">Figma</span>
                    <span class="tech-item">Adobe XD</span>
                    <span class="tech-item">React</span>
                    <span class="tech-item">Vue.js</span>
                    <span class="tech-item">Tailwind CSS</span>
                    <span class="tech-item">JavaScript</span>
                    <span class="tech-item">HTML5/CSS3</span>
                    <span class="tech-item">Bootstrap</span>
                </div>
            </div>
            
            <div class="card">
                <h3>Backend & Bases de Datos</h3>
                <div class="tech-list">
                    <span class="tech-item">Django</span>
                    <span class="tech-item">Node.js</span>
                    <span class="tech-item">MongoDB</span>
                    <span class="tech-item">MySQL</span>
                    <span class="tech-item">Oracle</span>
                    <span class="tech-item">SQLite</span>
                </div>
            </div>
            
            <div class="card">
                <h3>DevOps & Cloud</h3>
                <div class="tech-list">
                    <span class="tech-item">Docker</span>
                    <span class="tech-item">AWS</span>
                    <span class="tech-item">Azure</span>
                    <span class="tech-item">Git/GitHub</span>
                    <span class="tech-item">Render</span>
                </div>
            </div>
            
            <div class="card">
                <h3>Herramientas & Otros</h3>
                <div class="tech-list">
                    <span class="tech-item">Jira</span>
                    <span class="tech-item">Power BI</span>
                    <span class="tech-item">KNIME</span>
                    <span class="tech-item">Linux</span>
                    <span class="tech-item">Wireshark</span>
                    <span class="tech-item">RStudio</span>
                </div>
            </div>
        </div>
    </section>
    
    <section>
        <h2><i class="fas fa-project-diagram"></i> Proyectos Destacados</h2>
        <div class="grid">
            <div class="card">
                <h3>MedBook - Plataforma Médica</h3>
                <p>Sistema de reservas médicas con enfoque UX. Desarrollo full stack con React, Django y MongoDB.</p>
                <div class="tech-list">
                    <span class="tech-item">React</span>
                    <span class="tech-item">Django</span>
                    <span class="tech-item">Figma</span>
                </div>
            </div>
            
            <div class="card">
                <h3>Dashboard de Analítica</h3>
                <p>Panel de visualización de datos en tiempo real con Power BI y KNIME, implementado en Azure.</p>
                <div class="tech-list">
                    <span class="tech-item">Power BI</span>
                    <span class="tech-item">KNIME</span>
                    <span class="tech-item">Azure</span>
                </div>
            </div>
            
            <div class="card">
                <h3>App Educativa EduPlay</h3>
                <p>Plataforma de aprendizaje interactivo con Vue.js y AWS, enfocada en experiencia de usuario.</p>
                <div class="tech-list">
                    <span class="tech-item">Vue.js</span>
                    <span class="tech-item">AWS</span>
                    <span class="tech-item">Adobe XD</span>
                </div>
            </div>
        </div>
    </section>
    
    <section>
        <h2><i class="fas fa-id-card"></i> Contacto</h2>
        <div class="social-links">
            <a href="#" class="social-link">
                <i class="fab fa-linkedin"></i> LinkedIn
            </a>
            <a href="#" class="social-link">
                <i class="fas fa-envelope"></i> Email
            </a>
            <a href="#" class="social-link">
                <i class="fas fa-globe"></i> Portafolio UX
            </a>
            <a href="#" class="social-link">
                <i class="fab fa-github"></i> GitHub
            </a>
        </div>
        
        <div class="time-badge">
            <i class="fas fa-clock"></i> Hora local: <span id="local-time">Cargando...</span>
        </div>
    </section>
    
    <footer>
        <p>© 2023 Alicia Norambuena | Estudiante de Ingeniería en Informática</p>
    </footer>
    
    <script>
        // Función para mostrar la hora local de Santiago
        function updateSantiagoTime() {
            const options = {
                timeZone: 'America/Santiago',
                hour: '2-digit',
                minute: '2-digit',
                second: '2-digit',
                hour12: false
            };
            
            const formatter = new Intl.DateTimeFormat('es-CL', options);
            const santiagoTime = formatter.format(new Date());
            
            document.getElementById('local-time').textContent = santiagoTime;
        }
        
        // Actualizar cada segundo
        updateSantiagoTime();
        setInterval(updateSantiagoTime, 1000);
    </script>
</body>
</html>
