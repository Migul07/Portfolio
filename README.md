# Portfolio

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Miguel Morales Giménez</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #0f172a;
            --accent-color: #3b82f6;
            --text-color: #334155;
            --bg-color: #f8fafc;
            --white: #ffffff;
        }
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
        }
        header {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 4rem 2rem;
            text-align: center;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid var(--accent-color);
            object-fit: cover;
            margin-bottom: 1rem;
            background-color: #ccc;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header h2 {
            font-weight: 300;
            color: #94a3b8;
            margin-top: 0.5rem;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
        }
        section {
            background: var(--white);
            margin-bottom: 2rem;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }
        h3 {
            color: var(--primary-color);
            border-bottom: 2px solid var(--accent-color);
            padding-bottom: 0.5rem;
            margin-top: 0;
        }
        .timeline-item {
            margin-bottom: 1.5rem;
            padding-left: 1rem;
            border-left: 3px solid var(--accent-color);
        }
        .timeline-item h4 {
            margin: 0;
            font-size: 1.1rem;
        }
        .date {
            font-size: 0.9rem;
            color: #64748b;
            font-style: italic;
            display: block;
            margin-bottom: 0.5rem;
        }
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .skill-tag {
            background-color: #e2e8f0;
            color: var(--primary-color);
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
        }
        .contact-info {
            list-style: none;
            padding: 0;
        }
        .contact-info li {
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .contact-info i {
            color: var(--accent-color);
            width: 20px;
        }
        a {
            color: var(--accent-color);
            text-decoration: none;
        }
        footer {
            text-align: center;
            padding: 2rem;
            background-color: var(--primary-color);
            color: #64748b;
            font-size: 0.8rem;
        }
        @media (max-width: 600px) {
            header h1 { font-size: 2rem; }
            .container { padding: 1rem; }
        }
    </style>
</head>
<body>
    <header>
        <img src="Imagen de WhatsApp 2025-07-23 a las 15.10.44_df78214f.jpg" alt="Foto de Miguel Morales" class="profile-img">
        <h1>Miguel Morales Giménez</h1>
        <h2>Estudiante de Desarrollo de Aplicaciones Web </h2>
        <p>Granada, España </p>
    </header>
    <div class="container">
        <section id="sobre-mi">
            <h3><i class="fas fa-user"></i> Sobre Mí</h3>
            <p>
                Soy un estudiante comunicativo, amable y capaz de adaptarse a cada situación. 
                Busco una oportunidad laboral en la que demostrar mi compromiso, responsabilidad y capacidad de trabajo en equipo. 
                Destaco por ser muy amable y tener buen don de gentes.
            </p>
        </section>
        <section id="educacion">
            <h3><i class="fas fa-graduation-cap"></i> Estudios</h3>  
            <div class="timeline-item">
                <h4>Desarrollo de Aplicaciones Web</h4>
                <span class="date">Septiembre 2025 - Presente</span>
                <p>IES Zaidín Vergeles</p>
            </div>
            <div class="timeline-item">
                <h4>Bachillerato</h4>
                <span class="date">Septiembre 2023 - Mayo 2025</span>
                <p>IES Alonso Cano (Dúrcal)</p>
            </div>
            <div class="timeline-item">
                <h4>Educación Secundaria Obligatoria (ESO)</h4>
                <span class="date">Septiembre 2019 - Junio 2023</span>
                <p>IES Alonso Cano (Dúrcal)</p>
            </div>
        </section>
        <section id="experiencia">
            <h3><i class="fas fa-briefcase"></i> Experiencia Laboral</h3>
            <div class="timeline-item">
                <h4>Limpiador de casas (Autónomo)</h4>
                <span class="date">Agosto 2024 - Noviembre 2024</span>
                <p><strong>Webel, Granada</strong></p>
                <p>Adquisición de habilidades de limpieza y cuidado del hogar.</p>
            </div>
        </section>
        <section id="voluntariado">
            <h3><i class="fas fa-hand-holding-heart"></i> Voluntariado</h3>
            <div class="timeline-item">
                <h4>Voluntario en Cruz Roja</h4>
                <span class="date">Junio 2025 - Presente</span>
                <p>Participación en actividades de ayuda humanitaria y social.</p>
            </div>
        </section>
        <section id="habilidades">
            <h3><i class="fas fa-tools"></i> Habilidades</h3>
            <div class="skills-container">
                <span class="skill-tag">Manejo de tecnologías</span>
                <span class="skill-tag">Inglés</span>
                <span class="skill-tag">Trabajo en equipo</span>
                <span class="skill-tag">Adaptabilidad</span>
                <span class="skill-tag">Aprendizaje rápido</span>
                <span class="skill-tag">Paciencia y Respeto</span>
                <span class="skill-tag">Creatividad e innovación</span>
            </div>
        </section>
        <section id="contacto">
            <h3><i class="fas fa-envelope"></i> Contacto</h3>
            <ul class="contact-info">
                <li>
                    <i class="fas fa-envelope"></i>
                    <a href="mailto:migulmoralesgimenez07@gmail.com">migulmoralesgimenez07@gmail.com</a>
                </li>
                <li>
                    <i class="fas fa-phone"></i>
                    <a href="tel:+34611089250">611 08 92 50</a>
                </li>
                <li>
                    <i class="fas fa-map-marker-alt"></i>
                    <span>Dúrcal, Granada, España</span>
                </li>
            </ul>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 Miguel Morales Giménez - CV Portfolio</p>
    </footer>
</body>
</html>
