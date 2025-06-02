<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CTP_LC</title>
    <style>
         body {
      margin: 0;
      font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
      background: linear-gradient(to right, #d1d8d4, #89aae6);
      color: #000;
      line-height: 1.5;
      padding-left: 70px; /* Espacio para la barra lateral */
    }
    .container {
      width: 90%;
      height: auto;
      margin: 5% auto;
      background: linear-gradient(to bottom right, #bac0c4, #c5cec8);
      border: 2px solid black;
      padding: 20px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      border-radius: 50px;
    }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #004080;
      color: white;
      padding: 10px 20px;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      border-radius: 50PX;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 1.5em;
      font-weight: bold;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    .nav-links li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    .nav-links li a:hover {
      color: #ffcc00;
    }

    main {
      padding-top: 80px;
    }


    .carousel {
      position: relative;
      max-width: 800px;
      margin: 40px auto;
      overflow: hidden;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }

    .carousel-images {
      display: flex;
      transition: transform 0.5s ease-in-out;
    }

    .carousel-images a {
      flex-shrink: 0;
      width: 100%;
      text-align: center;
      color: #000;
      text-decoration: none;
    }

    .carousel-images figure {
      margin: 0;
      padding: 10px;
    }

    .carousel-images img {
      height: 200px;
      width: 200px;
      object-fit: cover;
      border-radius: 8px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      cursor: pointer;
    }

    .carousel-images img:hover {
      transform: scale(1.05);
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
    }

    .carousel-images figcaption {
      margin-top: 8px;
      font-size: 14px;
      color: #555;
    }

    .carousel-buttons {
      position: absolute;
      top: 50%;
      width: 100%;
      display: flex;
      justify-content: space-between;
      transform: translateY(-50%);
      pointer-events: none;
    }

    .carousel-buttons button {
      background: rgba(0, 0, 0, 0.5);
      border: none;
      color: white;
      padding: 10px 20px;
      cursor: pointer;
      font-size: 24px;
      pointer-events: all;
      transition: background 0.3s ease;
    }

    .carousel-buttons button:hover {
      background: rgba(255, 255, 255, 0.2);
    }
    </style>
</head>
<body>
    <header>
        <nav>
          <div class="logo">Colegio Tecnico Profesional Los Chiles</div>
          <ul class="nav-links">
            <li><a href="#inicio">bienvenido</a></li>
            <li><a href="#nosotros">Nosotros</a></li>
            <li><a href="#cursos">especialidades</a></li>
            <li><a href="#galeria">Galería</a></li>
            <li><a href="#contacto">Contacto</a></li>
          </ul>
        </nav>
      </header>
    
      <main>
<div class="container">
    <section id="inicio">
        <h1>Bienvenidos al Colegio Tecnico Profesional Los Chiles</h1>
        <p>Os daamos la mas calida bienvenidad con los brazos abiertos y les brindamos a oportunidad de formar
          parte de la gran familia del CTP Los Chiles donde te ayudaremos a reforzar tu nivel de aprandeizaje y mejorar todos tus  ambitos estudiantiles,
          formamos un futuro mejor para un mejor mundo
        </p>
      </section>
</div>
    
        
            <section id="nosotros">
                <h2>nuestra historia</h2>
                <div class="container">
                <p>
                  El 21 de octubre de 1971 en decreto 4874, la Asamblea Legislativa de la República de Costa Rica, crea El Colegio Técnico Profesional Los Chiles, como resultado de las gestiones realizadas por un comité integrado por miembros de la comunidad y con el apoyo de funcionarios del Ministerio de Educación Pública.
                  
                  
                  
                  Con su creación se abrió la posibilidad para que gran cantidad de jóvenes del lugar, pudieran cursar Educación de Nivel Medio; ya que hasta entonces pocos podían hacerlo, debido a la gran distancia en que se ubican los colegios más próximos y en su mayoría no tenían los recursos económicos requeridos.</p>
              </section>
          
        </div>

        <section id="cursos">
          <h2>Especialidades</h2>
          <div class="container">
          <p>Nuestro colegio se preocupa por la sociedad de nuestro mundo por eso presentamos algunas especialidades como lo son:
          </p>
          <p>Desarrollo web:</p><br>
          <p>Es una especialidad que se basa en la programación, el diseño web, el mantenimiento, entre otras cosas... Aqui se encuentra una gran cantidad de
             posibilidades de practicas mas que interesantes en las que es posible mantenerse con trabajo y brinda alto conocimiento en amplias areas de la informatica
            a los estudiantes</p><br><br>
            <p>Contabilidad:</p><br>
            <p>una especialidad fundamental en la hisstoria, una de las favoritas de la comunidad estudiantil, va muy de la mano con especialidades como desarrollo web o secretariado,
                una especialidad que no es para todos pero aquellos que la logren aprovechar saldran muy beneficiados.
            </p><br><br>
            <p>secretariado:</p><br>
            <p>La especialidad favorita de la comunidad estudiantil una especialidad que se cenra mucho en su trabajo y que es bastante pesada pues la cantidad es grande comparada a algunas especialidades mas sus opciones de empleo no son tantas</p><br><br>
            <p>Agropecuaria</p><br>
            <p>Una especialidad que lleva acompañando al colegio desde un inicio es basada en el trabajo en el campo tiene una popularidad mediana entre los estudiantes del colegio y es ejecutada en la finca del colegio</p><br><br>
            <p>aduanas:</p><br>
            <p>la especialidad por excelencia que a la mayoria de estuduiantes les encanta, es una especialidad muy completa pues enseña mucho y ademas de ello se presta para varios empleos.</p><br><br>
            <p>turismo:</p><br>
            <p>una especialidad que a diferencia de su nombre no se sentra en el turismo sino que se sentra en la cocina y en la manipulación de alimentos</p>

        </section>
    </div>
    
        <section id="galeria">
       <div class="container">   <h2>Galería</h2>
       <center> <img src="img/gen 2024.jpg" alt="generació n 2024" style="height: 500px; width: 800px;"></center></div>
        </section>
    
        <section id="contacto">
        <div class="container">
            <h2>Contacto</h2>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            Nis porro, iusto neque temporibus facere molestias quis est saepe ipsa. 
            Explicabo eaque vitae nobis nulla. Eaque natus accusantium optio dolor ad?</p>
        </div>
        </section>
      </main>

      <center><h1>PROFESORES</h1></center>
      <DIV class="container">
         
  <h1 class="reveal">Los Rio Fellas</h1>

  <div class="container reveal">
    <div class="carousel">
      <div class="carousel-images" id="carousel-images">
        <a href="description1.html">
          <figure><img src="img/" alt="Fútbol 1"><figcaption>Paul</figcaption></figure>
        </a>
        <a href="description2.html">
          <figure><img src="img/Eithan.jpeg" alt="Fútbol 2"><figcaption>Eithan</figcaption></figure>
        </a>
        <a href="description3.html">
          <figure><img src="img/Farid.jpeg" alt="Fútbol 3"><figcaption>Farid</figcaption></figure>
        </a>
        <a href="description4.html">
          <figure><img src="img/Eithon.jpeg" alt="Fútbol 4"><figcaption>Eithon</figcaption></figure>
        </a>
        <a href="description5.html">
          <figure><img src="img/cesar serio.jpeg" alt="Fútbol 5"><figcaption>César</figcaption></figure>
        </a>
      </div>
      <div class="carousel-buttons">
        <button onclick="moveSlide(-1)">❮</button>
        <button onclick="moveSlide(1)">❯</button>
      </div>
    
      </DIV>
</body>
</html>
