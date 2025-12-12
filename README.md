[index.html](https://github.com/user-attachments/files/24117280/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>A S - Protegemos tus datos</title>
    
    <!-- Esto quita la URL fea cuando abres el archivo directamente -->
    <script>
        if (window.location.href.indexOf("file://") === 0 || window.location.href.indexOf("127.0.0.1") > -1) {
            history.replaceState({}, "A S - Protección de Datos", "/");
        }
    </script>
    
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        
        header {
            background-color: #0077be;
            color: white;
            text-align: center;
            padding: 40px;
        }
        
        header h1 {
            font-size: 40px;
            margin: 0;
        }
        
        header p {
            font-size: 20px;
            margin-top: 10px;
        }
        
        nav {
            background-color: white;
            padding: 15px;
            text-align: center;
            border-bottom: 3px solid #0077be;
        }
        
        nav a {
            margin: 0 25px;
            font-size: 18px;
            color: #0077be;
            text-decoration: none;
            font-weight: bold;
        }
        
        nav a:hover {
            color: #ff6600;
        }
        
        .seccion {
            width: 80%;
            margin: 30px auto;
            background-color: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 4px 15px #00000022;
        }
        
        h2 {
            color: #0077be;
            text-align: center;
            font-size: 28px;
        }
        
        p {
            font-size: 17px;
            text-align: justify;
        }
        
        ul {
            font-size: 17px;
        }
        
        img {
            width: 100%;
            max-width: 600px;
            border-radius: 12px;
            margin: 20px auto;
            display: block;
        }
        
        footer {
            background-color: #0077be;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        
        footer p {
            margin: 8px;
            font-size: 15px;
        }
    </style>
</head>
<body>

    <header>
        <h1>A S</h1>
        <p>Protegemos tus datos con cariño y seguridad</p>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#quienes">Quienes somos</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <div class="seccion" id="inicio">
        <h2>¡Hola! Bienvenido a A S</h2>
        <p>Me llamo Ambioris (tengo 15 años) y creé esta página porque me preocupa mucho que la gente pierda sus fotos, videos o documentos importantes por virus o robos en internet.</p>
        <p>En A S guardamos y protegemos tus cosas más importantes para que nunca las pierdas.</p>
        <img src="https://imgs.search.brave.com/c9DI4ByefyaHLHjEa8VEFGJwbZ51T9XJK7WbpQpzNc0/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly9jZG4u/Y3JlYXRlLnZpc3Rh/LmNvbS9hcGkvbWVk/aWEvc21hbGwvMzgz/MDM3MTc4L3N0b2Nr/LXBob3RvLWdyYXBo/aWNzLW9mLWxhdGVz/dC1kaWdpdGFsLXRl/Y2hub2xvZ3ktcHJv/dGVjdGlvbi1kYXRh/LXBhZGxvY2stc2Vj/dXJpdHktb24tdGhl/LXZpcnR1YWwtZGlz/cGxheS1idXNpbmVz/c21hbi13aXRo" alt="Candado digital">
    </div>

    <div class="seccion" id="quienes">
        <h2>¿Quiénes somos?</h2>
        <p>Soy un estudiante de 4to de SEC que le encanta la informática. Aprendí solo a programar viendo vídeos en YouTube y ahora quiero ayudar a otras personas a proteger sus recuerdos.</p>
        <p>No somos una empresa grande, soy solo yo (y a veces mi primo me ayuda jajaja), pero prometo cuidar tus datos como si fueran nuestros.</p>
        <img src="https://images.unsplash.com/photo-1587620962725-abab7fe55159?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80" alt="Chico programando">
    </div>

    <div class="seccion" id="servicios">
        <h2>Lo que puedo hacer por ti</h2>
        <ul>
            <li>Poner contraseña súper fuerte a tus carpetas</li>
            <li>Guardar copias de tus fotos en lugares seguros</li>
            <li>Enseñarte a no caer en trampas de internet</li>
            <li>Revisar si tus contraseñas son fáciles de adivinar</li>
            <li>Avisarte si veo que tus datos están en peligro</li>
        </ul>
        <img src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80" alt="Servicios de seguridad">
    </div>

    <div class="seccion" id="contacto">
        <h2>Contáctanos</h2>
        <p><strong>Email:</strong> somos_as@gmail.com</p>
        <p><strong>Instagram:</strong> @as.somos</p>
        <p>¡Todo es gratis porque estoy aprendiendo y me hace ilusión ayudar!</p>
    </div>

    <footer>
        <p>© 2025 A S - Somos la definicion de persistencia
        </p>
        <p>Esto lo hago por pasión</p>
    </footer>

</body>
</html>
