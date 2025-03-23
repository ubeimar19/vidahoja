# vidahoja
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida CV - Ubeimar Iván Herrera Cevallos</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Times New Roman', sans-serif;
        }
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #2c3e50;
            color: white;
        }
        .container {
            display: flex;
            width: 100%;
            max-width: 1300px;
            height: 90vh;
            background: white;
            color: #333;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
        }
        .contact-info, .links {
            margin-top: 20px;
            text-align: left;
        }
        .contact-info a, .links a {
            color: rgb(207, 203, 203);
            text-decoration: none;
            display: block;
            margin-top: 5px;
        }
        .contact-info a:hover, .links a:hover {
            text-decoration: underline;
        }
        .bio h2, .interests h2, .portfolio h2 {
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 5px;
            margin-bottom: 10px;
            color: #2c3e50;
        }
        .bio p, .interests ul {
            font-size: 14px;
            color: #333;
        }
        .interests ul {
            list-style: none;
            padding-left: 0;
        }
        /* Barra lateral */
        .sidebar {
            width: 30%;
            background: #01084d;
            color: white;
            text-align: center;
            padding: 30px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .sidebar img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid white;
            margin-bottom: 15px;
        }
        .sidebar h2 {
            font-size: 22px;
        }
        .contact-info {
            margin-top: 20px;
            text-align: center;
        }
        .contact-info p {
            font-size: 14px;
            margin: 5px 0;
        }
        .contact-info a {
            color: white;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        /* Contenido principal */
        .main-content {
            width: 100%;
            padding: 30px;
            overflow-y: auto;
        }
        .title {
            font-size: 26px;
            font-weight: bold;
            text-align: center;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        .bio, .portfolio {
            margin-bottom: 20px;
        }
        .bio h2, .portfolio h2 {
            color: #34495e;
            border-bottom: 2px solid #78afe7;
            padding-bottom: 5px;
            margin-bottom: 10px;
        }
        .bio p {
            font-size: 16px;
            line-height: 1.5;
            text-align: justify;
        }
        .interests li {
            font-size: 14px;
            margin-bottom: 5px;
        }
        /* Portafolio */
        .portfolio .tabs {
            display: flex;
            justify-content: space-around;
            background: #160161;
            color: white;
            padding: 8px;
            border-radius: 5px;
        }
        .portfolio .tabs div {
            flex: 1;
            text-align: center;
            padding: 7px;
            cursor: pointer;
            transition: background 0.3s, color 0.3s;
        }
        .portfolio .tabs div:hover {
            background: #5707d8;
        }
        .portfolio .tabs div.active {
            background: #4a0152;
            font-weight: bold;
        }
        .tab-content {
            display: none;
            padding: 8px;
            background: #ecf0f1;
            border-radius: 4px;
            margin-top: 8px;
            color: #13012f;
        }
        .tab-content.active {
            display: block;
        }
        /* Botones de años */
        .year {
            background: #1e5f8a;
            padding: 8px;
            margin: 4px 0;
            border-radius: 4px;
            cursor: pointer;
            font-weight: bold;
            text-align: center;
            transition: background 0.3s;
        }
        .year:hover {
            background: #024bf5;
        }
        .year-content {
            display: none;
            padding: 4px 8px;
            background: white;
            border-left: 3px solid #022b53;
            margin-top: 4px;
        }
        /* Responsivo */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                height: auto;
            }
            .sidebar {
                width: 100%;
                padding: 20px;
            }
            .main-content {
                width: 100%;
                padding: 20px;
            }
            .portfolio .tabs {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Barra lateral -->
        <div class="sidebar">
            <img src="https://media.licdn.com/dms/image/v2/D5603AQG94swsgQOi2w/profile-displayphoto-shrink_800_800/B56ZWpkc4.HEAc-/0/1742306660624?e=1747872000&v=beta&t=2i6QzcUG3ndJwR_lYk_sQKMRANE2fQw5mdITXlN16dc" alt="Foto de perfil">
            <h2>Ubeimar Iván Herrera Cevallos</h2>
            <div class="contact-info">
                <p><strong>Correo:</strong> <a href="mailto:ubeimar2121@gmail.com"><i class="fas fa-envelope"></i> ubeimar2121@gmail.com</a></p>
                <p><strong>Teléfono:</strong> <a href="tel:+593998957995"><i class="fas fa-phone"></i> +593 998957995</a></p>
            </div>
            <br>
            <div class="links">
                <h3>Links Externos</h3>
                <a href="https://upecedu-my.sharepoint.com/:b:/g/personal/ubeimar_herrera_upec_edu_ec/EakKe0V2KCVKvblpLF4A83UB_ib-omnWHGvkNi7L7yHcAQ?e=dUliOH"><i class="fas fa-file-pdf" style="color: #FF6F61;"></i> Hoja de vida PDF</a>
                <a href="https://www.linkedin.com/in/ubeimar-iván-herrera-cevallos-568b292a2/"><i class="fab fa-linkedin" style="color: #1E88E5;"></i> LinkedIn</a>
            </div>
        </div>
        <!-- Sección Principal -->
        <div class="main-content">
            <div class="title">Hoja de Vida CV</div>
            <div class="bio">
                <h2><i class="fas fa-user"></i> Biografía</h2>
                <p>Tengo título de bachiller con formación técnica en Electromecánica
                    Automotriz, Unidad Educativa Vicente Fierro. Cuento con título de tercer nivel de ingeniería en Logística
                    y Transporte en la Universidad Politécnica Estatal del Carchi.
                    He desarrollado habilidades en herramientas tecnológicas con conocimientos en mecánica automotriz,
                    al igual cuento con conocimientos en logística, gestión de almacenes, inventarios, análisis de datos
                    manejado de indicadores clave (KPIs), lo que me permite analizar y mejorar procesos en el ámbito del
                    transporte y la gestión operativa. Intereses profesionales: gestión en cadena de suministros, optimización
                    de rutas de transporte, gestión de inventarios y almacenamiento.
                    Habilidad para trabajar en equipo, aprender rápidamente y resolver problemas de manera eficiente.
                    Disponibilidad inmediata y flexibilidad para horarios y ubicación.
                </p>
            </div>
            <div class="interests">
                <h2><i class="fas fa-briefcase"></i> Intereses Profesionales</h2>
                <ul>
                    <li><i class="fas fa-truck"></i> Logística y Transporte – Gestión de la cadena de suministro</li>
                    <li><i class="fas fa-industry"></i> Logística y Transporte – Optimización de procesos productivos</li>
                    <li><i class="fas fa-map-marked-alt"></i> Logística y Transporte – Gestión de rutas de transporte</li>
                    <li><i class="fas fa-file-invoice"></i> Comercio exterior – Gestión de documentación aduanera</li>
                    <li><i class="fas fa-globe"></i> Comercio exterior – Normativas internacionales de comercio</li>
                </ul>
            </div>
            <div class="portfolio">
                <h2><i class="fas fa-folder-open"></i> Portafolio de Proyectos</h2>
                <div class="tabs">
                    <div class="tab-btn" onclick="showTab('consultoria', this)"><i class="fas fa-graduation-cap"></i> Formación Académica</div>
                    <div class="tab-btn" onclick="showTab('investigacion', this)"><i class="fas fa-flask"></i> Proyectos Investigación</div>
                    <div class="tab-btn" onclick="showTab('cursos', this)"><i class="fas fa-book"></i> Cursos</div>
                    <div class="tab-btn" onclick="showTab('colaboraciones', this)"><i class="fas fa-handshake"></i> Colaboraciones</div>
                    <div class="tab-btn" onclick="showTab('idiomas', this)"><i class="fas fa-language"></i> Idiomas</div> 
                    <div class="tab-btn" onclick="showTab('software', this)"><i class="fas fa-laptop-code"></i> Experiencia</div>
                    <div class="tab-btn" onclick="showTab('premios', this)"><i class="fas fa-trophy"></i> Distinciones, Premios o Becas</div>
                    <div class="tab-btn" onclick="showTab('contenido', this)"><i class="fas fa-file-alt"></i> Desarrollo de Contenido Virtual y Prototipos</div>
                </div>
                <!-- Proyectos consultoría -->
                <div id="consultoria" class="tab-content active">
                    <div class="year" onclick="toggleYear('pc2025')">2025</div>
                    <div id="pc2025" class="year-content">
                        <ul>
                            <li>Ingeniería en Logística y Transporte en la Universidad Politécnica Estatal Del Carchi</li>
                        </ul>
                    </div>
                    <div class="year" onclick="toggleYear('pc2024')">2020</div>
                    <div id="pc2024" class="year-content">
                        <ul>
                            <li>Título de Bachiller Técnico en Electromecánica Automotriz, en la Unidad Educativa Vicente Fierro</li>
                        </ul>
                    </div>
                </div>
                <!-- Proyectos Investigación -->
                <div id="investigacion" class="tab-content">
                    <div class="year" onclick="toggleYear('pi2025')">2025</div>
                    <div id="pi2025" class="year-content">
                        <ul>
                            <li>Factores de riesgo para el transporte y la eficiencia logística en la empresa de transporte Ameex
                                isCargo S.A. Universidad Politécnica Estatal del Carchi.</li>
                        </ul>
                    </div>
                </div>
                <!-- Cursos -->
                <div id="cursos" class="tab-content">
                    <div class="year" onclick="toggleYear('c20251')">2025</div>
                    <div id="c20251" class="year-content">
                        <ul>
                            <li>Excel Intermedio. Duración: 20 horas. TEACHLR. Modalidad Virtual. 17-28 de marzo, 2025.</li>
                        </ul>
                    </div>
                    <div class="year" onclick="toggleYear('c2024')">2024</div>
                    <div id="c2024" class="year-content">
                        <ul>
                            <li>Práctica en el llenado de declaraciones Aduaneras en el Sistema Aduanero. Duración: 10 horas.
                                My Intelecto. Guayaquil, Ecuador. 12-24 de noviembre, 2024.</li>
                            <li>Actividades Simultáneas Latinoamericanas de Estudiantes e Ingenieros Industriales. Duración: 6
                                horas. Universidad del Istmo. Modalidad Virtual Panamá. 10 de mayo, 2024.</li>
                        </ul>
                    </div>
                    <div class="year" onclick="toggleYear('c2022')">2022</div>
                    <div id="c2022" class="year-content">
                        <ul>
                            <li>Introducción a la Realidad Virtual y Simulación. Duración: 40 horas. Universidad Politécnica
                                Estatal del Carchi. Tulcán, Ecuador. 05 de mayo-26 de julio, 2022.</li>
                        </ul>
                    </div>
                </div>
                <!-- Nueva sección de idiomas -->
                <div id="idiomas" class="tab-content">
                    <div class="year" onclick="toggleYear('nat2000')">Nativo</div>
                    <div id="nat2000" class="year-content">
                        <ul>
                            <li><strong>Español:</strong> Nativo</li>
                        </ul>
                    </div>
                    <div class="year" onclick="toggleYear('idiomas2025')">2022</div>
                    <div id="idiomas2025" class="year-content">
                        <ul>
                             <li><strong>Inglés:</strong> Nivel B1 – Certificado por la Universidad Politécnica Estatal del Carchi (2022)</li>
                        </ul>
                     </div>
                </div>
                <!-- Colaboraciones -->
                <div id="colaboraciones" class="tab-content">
                    <div class="year" onclick="toggleYear('col2024')">2024</div>
                    <div id="col2024" class="year-content">
                        <ul>
                            <li>Proyecto de Vinculación con la Sociedad denominado “Diseño de rutas para el mejoramiento del
                                servicio de transporte comercial, modalidad escolar e institucional con las operadoras domiciliadas
                                en la ciudad de Tulcán”.</li>
                        </ul>
                    </div>
                </div>
                <!-- Experiencia en Software -->
                <div id="software" class="tab-content">
                    <div class="year" onclick="toggleYear('sof12')">Experiencia en Software</div>
                    <div id="sof12" class="year-content">
                        <ul>
                            <li><i class="fab fa-microsoft"></i> Microsoft Excel (Intermedio) - Analizar base de datos con funciones avanzadas</li>
                            <li><i class="fas fa-chart-line"></i> Power Bi (Básico) - Presentación de informes y análisis de datos</li>
                            <li><i class="fas fa-drafting-compass"></i> Auto Cad (Básico) - Diseño y modelado de plantas de producción</li>
                            <li><i class="fas fa-cogs"></i> Flexsim (Básico) - Simulación de procesos productivos</li>
                            <li><i class="fas fa-map-marked-alt"></i> Arc Map (Básico) - Diseño y optimización de rutas</li>
                            <li><i class="fas fa-paint-brush"></i> Sketchup (Básico) - Creación de modelos personalizados</li>
                            <li><i class="fab fa-python"></i> Python (Básico) - Desarrollo de scripts para análisis de datos</li>
                            <li><i class="fas fa-gamepad"></i> Unreal Engine (Básico) - Visualizar diseños y crear experiencias cinematográficas</li>
                        </ul>
                    </div>
                    <div class="year" onclick="toggleYear('expp')">Experiencia Profesional</div>
                    <div id="expp" class="year-content">
                        <ul>
                            <li>2023: Prácticas preprofesionales en Encomiendas Ecuador S.A recolección y distribución en paquetería,
                                digitación de guías.</li>           
                        </ul>
                    </div>
                </div>
                <!-- Distinciones, Premios o Becas -->
                <div id="premios" class="tab-content">
                    <div class="year" onclick="toggleYear('pre11')">2024</div>
                    <div id="pre11" class="year-content">
                        <ul>
                            <li><i class="fas fa-trophy"></i> Beca Excelencia Académica</li>
                        </ul>
                    </div>
                    <div class="year" onclick="toggleYear('pre10')">2023</div>
                    <div id="pre10" class="year-content">
                        <ul>
                            <li><i class="fas fa-award"></i> Beca Socioeconómica</li>           
                        </ul>
                    </div>
                </div>
                <!-- Desarrollo de Contenido Virtual y Prototipos -->
                <div id="contenido" class="tab-content">
                    <ul>
                        <li><i class="fas fa-file-alt"></i> Diseño de rutas para el mejoramiento del servicio de transporte comercial, modalidad escolar e institucional con las operadoras domiciliadas en la ciudad de Tulcán con el software ARC MAP</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <script>
        function showTab(tabName, element) {
            document.querySelectorAll('.tab-content').forEach(tab => tab.classList.remove('active'));
            document.getElementById(tabName).classList.add('active');
            document.querySelectorAll('.tab-btn').forEach(btn => btn.classList.remove('active'));
            element.classList.add('active');
        }
        function toggleYear(yearId) {
            let yearContent = document.getElementById(yearId);
            yearContent.style.display = yearContent.style.display === 'block' ? 'none' : 'block';
        }
    </script>
</body>
</html>
