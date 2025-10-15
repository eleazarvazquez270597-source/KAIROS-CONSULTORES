<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kairos Consultores</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap" rel="stylesheet">
  <style>
    /* ======= ESTILO GENERAL ======= */
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #222;
      line-height: 1.6;
    }
    h1, h2, h3 {
      color: #16213e;
    }

    /* ======= ENCABEZADO ======= */
    header {
      background: linear-gradient(135deg, #0f172a, #1a1a2e);
      color: white;
      text-align: center;
      padding: 3rem 1rem 2rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    header img {
      max-width: 150px;
      margin-bottom: 1rem;
    }
    header h1 {
      font-size: 2rem;
      margin-bottom: 0.5rem;
      letter-spacing: 2px;
    }
    header p {
      font-size: 1.1rem;
      color: #e0e0e0;
    }

    /* ======= NAVEGACIÓN ======= */
    nav {
      background: #16213e;
      padding: 1rem;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #f0c674;
    }

    /* ======= SECCIÓN HERO ======= */
    #inicio {
      background: linear-gradient(rgba(26,26,46,0.85), rgba(26,26,46,0.85)), url('office-background.jpg') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 6rem 2rem;
    }
    #inicio h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    #inicio p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }
    .btn {
      background: #f0c674;
      color: #16213e;
      padding: 0.8rem 1.5rem;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 600;
      transition: all 0.3s ease;
    }
    .btn:hover {
      background: #fff;
      color: #0f172a;
    }

    /* ======= SERVICIOS ======= */
    section {
      padding: 4rem 2rem;
      max-width: 1100px;
      margin: auto;
    }
    .servicios {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      margin-top: 2rem;
    }
    .card {
      background: white;
      padding: 2rem;
      border-radius: 12px;
      flex: 1;
      min-width: 250px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }
    .card h3 {
      color: #0f172a;
      margin-bottom: 0.8rem;
    }

    /* ======= NOSOTROS ======= */
    #nosotros {
      background: #f9f9f9;
      border-top: 2px solid #f0c674;
      border-bottom: 2px solid #f0c674;
    }
    #nosotros p {
      max-width: 800px;
      margin: auto;
      text-align: center;
      font-size: 1.1rem;
    }

    /* ======= CONTACTO ======= */
    #contacto p {
      font-size: 1.1rem;
      text-align: center;
      margin: 0.5rem 0;
    }

    /* ======= PIE DE PÁGINA ======= */
    footer {
      background: #0f172a;
      color: white;
      text-align: center;
      padding: 1.5rem;
      font-size: 0.9rem;
      margin-top: 2rem;
    }

    /* ======= RESPONSIVE ======= */
    @media (max-width: 768px) {
      header h1 { font-size: 1.6rem; }
      #inicio h2 { font-size: 1.6rem; }
      .servicios { flex-direction: column; }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Kairos Consultores">
    <h1>KAIROS CONSULTORES</h1>
    <p>DEL ORDEN CONTABLE AL ÉXITO ORGANIZACIONAL</p>
  </header>

  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#servicios">Servicios</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio">
    <h2>Tu aliado en soluciones fiscales y empresariales</h2>
    <p>Asesoría profesional para empresas, emprendedores y personas físicas.</p>
    <a href="#contacto" class="btn">Contáctanos</a>
  </section>

  <section id="servicios">
    <h2>Servicios</h2>
    <div class="servicios">
      <div class="card">
        <h3>Contabilidad General</h3>
        <p>Registro contable, pólizas y estados financieros.</p>
      </div>
      <div class="card">
        <h3>Declaraciones Fiscales</h3>
        <p>Mensuales y anuales para personas físicas y morales.</p>
      </div>
      <div class="card">
        <h3>Nómina y RH</h3>
        <p>Administración de nómina, IMSS, incidencias y asesoría laboral.</p>
      </div>
      <div class="card">
        <h3>Consultoría Empresarial</h3>
        <p>Estrategias financieras, apertura de negocios y cumplimiento fiscal.</p>
      </div>
    </div>
  </section>

  <section id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>En Kairos Consultores ofrecemos experiencia y profesionalismo para brindar soluciones integrales en contabilidad y consultoría empresarial, ayudando a tu negocio a crecer con seguridad y confianza.</p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p><strong>Teléfonos:</strong> 3314031639 / 3151035710</p>
    <p><strong>Sitio web:</strong> kairosconsultoresmx.com</p>
    <p><strong>WhatsApp:</strong> Atención personalizada disponible.</p>
  </section>

  <footer>
    <p>&copy; 2025 Kairos Consultores. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
