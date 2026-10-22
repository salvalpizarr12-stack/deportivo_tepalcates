# deportivo_tepalcates
Desarrollo y organización del Deportivo Tepalcates 

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Deportivo Tepalcates</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #e2ded7;
    color: #222;
}

header {
    background-color: #2b2b2b;
    color: white;
    padding: 20px;
    text-align: center;
}

header p {
    color: #ccc;
    font-size: 13px;
}

nav {
    background-color: #3a3a3a;
    padding: 15px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 10px;
    font-size: 14px;
}

.portada {
    background-color: #f3efe6;
    margin: 30px auto;
    padding: 40px 20px;
    max-width: 900px;
    text-align: center;
    border-radius: 12px;
}

.portada h2 {
    font-size: 32px;
}

.portada p {
    line-height: 1.7;
}

.boton {
    display: inline-block;
    background-color: #2b2b2b;
    color: white;
    padding: 12px 25px;
    border-radius: 20px;
    text-decoration: none;
    margin-top: 10px;
}

.contenedor {
    max-width: 1000px;
    margin: auto;
    padding: 20px;
}

.titulo {
    background-color: #2b2b2b;
    color: white;
    padding: 15px;
    border-radius: 8px;
}

.deportes {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
}

.tarjeta {
    background-color: #f3efe6;
    padding: 20px;
    border-radius: 12px;
    text-align: center;
    border: 1px solid #ccc;
}

.formularios {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 15px;
}

.formulario {
    background-color: #3a3a3a;
    color: white;
    padding: 20px;
    border-radius: 12px;
}

.formulario p {
    color: #ddd;
    font-size: 14px;
    line-height: 1.5;
}

footer {
    background-color: #2b2b2b;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 30px;
}

@media (max-width: 600px) {
    .deportes {
        grid-template-columns: repeat(2, 1fr);
    }

    .formularios {
        grid-template-columns: 1fr;
    }

    .portada h2 {
        font-size: 25px;
    }

    nav a {
        display: inline-block;
        margin: 8px;
    }
}
</style>
</head>

<body>

<header>
    <h1>DEPORTIVO TEPALCATES</h1>
    <p>Deporte • Salud • Comunidad</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#deportes">Deportes</a>
    <a href="#formularios">Formularios</a>
    <a href="#nosotros">Nosotros</a>
</nav>

<section class="portada" id="inicio">
    <h2>¡Bienvenido al Deportivo Tepalcates!</h2>

    <p>
        Un espacio para practicar deporte,
        mejorar tu salud y convivir con la comunidad.
    </p>

    <p>
        Encuentra tu actividad favorita y
        forma parte de nuestro equipo.
    </p>

    <a href="#deportes" class="boton">
        Conoce nuestros deportes
    </a>
</section>

<section class="contenedor" id="deportes">
    <h2 class="titulo">Nuestros deportes</h2>

    <div class="deportes">
        <div class="tarjeta">
            <h3>⚽ Fútbol</h3>
            <p>Trabajo en equipo y diversión.</p>
        </div>

        <div class="tarjeta">
            <h3>🏀 Básquetbol</h3>
            <p>Velocidad y coordinación.</p>
        </div>

        <div class="tarjeta">
            <h3>🏐 Voleibol</h3>
            <p>Compañerismo y cooperación.</p>
        </div>

        <div class="tarjeta">
            <h3>🥊 Box</h3>
            <p>Disciplina y concentración.</p>
        </div>

        <div class="tarjeta">
            <h3>🏊 Natación</h3>
            <p>Actividad física en el agua.</p>
        </div>

        <div class="tarjeta">
            <h3>🎾 Tenis</h3>
            <p>Agilidad y estrategia.</p>
        </div>

        <div class="tarjeta">
            <h3>🥋 Taekwondo</h3>
            <p>Respeto y perseverancia.</p>
        </div>

        <div class="tarjeta">
            <h3>🏋️ Acondicionamiento</h3>
            <p>Fuerza y resistencia.</p>
        </div>
    </div>
</section>

<section class="contenedor" id="formularios">
    <h2 class="titulo">Sistema de formularios</h2>

    <div class="formularios">
        <div class="formulario">
            <h3>Registro de participantes</h3>
            <p>
                Recopila los datos de las personas
                interesadas en inscribirse.
            </p>
        </div>

        <div class="formulario">
            <h3>Selección de deportes</h3>
            <p>
                Permite conocer las actividades
                favoritas de los participantes.
            </p>
        </div>

        <div class="formulario">
            <h3>Control de asistencia</h3>
            <p>
                Organiza el registro de asistencia
                a las actividades deportivas.
            </p>
        </div>

        <div class="formulario">
            <h3>Reporte de incidentes</h3>
            <p>
                Registra situaciones ocurridas
                durante las actividades.
            </p>
        </div>

        <div class="formulario">
            <h3>Cambio o baja</h3>
            <p>
                Permite solicitar cambios de
                actividad u horario.
            </p>
        </div>
    </div>
</section>

<section class="contenedor" id="nosotros">
    <h2 class="titulo">¿Quiénes somos?</h2>

    <div class="portada">
        <h3>Nuestra misión</h3>
        <p>
            Promover el deporte, la salud y la convivencia
            mediante actividades físicas para la comunidad.
        </p>

        <h3>Nuestra visión</h3>
        <p>
            Ser un espacio donde las personas puedan
            aprender, participar y superarse.
        </p>

        <h3>Nuestros valores</h3>
        <p>
            Respeto, responsabilidad, disciplina
            y trabajo en equipo.
        </p>
    </div>
</section>

<footer>
    <h3>DEPORTIVO TEPALCATES</h3>
    <p>Deporte • Salud • Comunidad</p>
</footer>

</body>
</html>
