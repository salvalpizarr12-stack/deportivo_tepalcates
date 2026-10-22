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

FORMULARIO TEPALCATES 

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Deportivo Tepalcates - Sistema de Formularios</title>
<style>
:root {
--bg-main: #e2ded7;
--card-bg: #f3efe6;
--dark-banner: #2b2b2b;
--dark-card: #3a3a3a;
--text-light: #ffffff;
--text-dark: #222222;
--accent-gray: #555555;
--border-radius: 12px;
}

body {
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
background-color: var(--bg-main);
color: var(--text-dark);
margin: 0;
padding: 20px;
display: flex;
flex-direction: column;
align-items: center;
gap: 30px;
}

.form-card {
width: 100%;
max-width: 900px;
background-color: var(--card-bg);
border-radius: var(--border-radius);
box-shadow: 0 4px 15px rgba(0,0,0,0.15);
overflow: hidden;
border: 1px solid #ccc;
}

/* HEADER BANNER */
.header-banner {
background-color: var(--dark-banner);
color: var(--text-light);
padding: 15px 25px;
display: flex;
justify-content: space-between;
align-items: center;
}

.logo-section h1 {
margin: 0;
font-size: 22px;
letter-spacing: 1px;
}

.logo-section p {
margin: 2px 0 0 0;
font-size: 11px;
color: #bbb;
text-transform: uppercase;
}

.motto {
font-size: 14px;
font-weight: bold;
font-style: italic;
color: #ddd;
}

.card-body {
padding: 20px 25px;
}

/* BARRA TITULO DE FORMULARIO */
.form-title-bar {
background-color: var(--dark-banner);
color: var(--text-light);
padding: 10px 15px;
border-radius: 8px;
margin-bottom: 15px;
}

.form-title-bar h2 {
margin: 0;
font-size: 15px;
}

.form-title-bar p {
margin: 2px 0 0 0;
font-size: 11px;
color: #ccc;
}

/* SUBTÍTULOS DE SECCIÓN */
.section-tag {
background-color: var(--accent-gray);
color: var(--text-light);
display: inline-block;
padding: 4px 12px;
border-radius: 15px;
font-size: 12px;
font-weight: bold;
margin-top: 10px;
margin-bottom: 10px;
}

/* CONTENEDORES DE CAMPOS */
.fields-box {
background-color: var(--dark-card);
color: var(--text-light);
padding: 15px;
border-radius: 10px;
margin-bottom: 15px;
}

.grid-3 {
display: grid;
grid-template-columns: repeat(3, 1fr);
gap: 12px;
}

.grid-2 {
display: grid;
grid-template-columns: repeat(2, 1fr);
gap: 12px;
}

.form-group {
display: flex;
flex-direction: column;
gap: 4px;
}

.form-group label {
font-size: 11px;
color: #ddd;
}

.form-group input, .form-group select, .form-group textarea {
background-color: #f0f0f0;
border: none;
padding: 8px;
border-radius: 15px;
font-size: 12px;
width: 100%;
box-sizing: border-box;
}

/* BOTONES */
.btn-container {
display: flex;
justify-content: flex-end;
margin-top: 10px;
}

.btn-submit {
background-color: var(--dark-banner);
color: var(--text-light);
border: none;
padding: 8px 25px;
border-radius: 15px;
font-size: 12px;
cursor: pointer;
font-weight: bold;
}

.btn-submit:hover {
background-color: #000;
}

/* DEPORTES OPCIONES */
.checkbox-group {
display: grid;
grid-template-columns: repeat(4, 1fr);
gap: 10px;
font-size: 11px;
color: #fff;
}

.checkbox-item {
display: flex;
align-items: center;
gap: 5px;
}

/* TABLA CONTROL DE ASISTENCIA */
table.attendance-table {
width: 100%;
border-collapse: collapse;
color: #fff;
font-size: 11px;
}

table.attendance-table th, table.attendance-table td {
border-bottom: 1px solid #555;
padding: 6px;
text-align: center;
}

/* FOOTER */
.card-footer {
background-color: var(--dark-banner);
color: #bbb;
padding: 8px 20px;
font-size: 11px;
display: flex;
justify-content: space-between;
align-items: center;
}
</style>
</head>
<body>

<!-- ================= 1. FORMULARIO DE INICIO ================= -->
<div class="form-card">
<div class="header-banner">
<div class="logo-section">
<h1>DEPORTIVO TEPALCATES</h1>
<p>Deporte • Salud • Comunidad</p>
</div>
<div class="motto">¡Tu esfuerzo también es parte del equipo!</div>
</div>

<div class="card-body">
<div class="grid-2">
<div>
<div class="form-title-bar">
<h2>Formulario de Inicio</h2>
<p>Completa tus datos para inscribirte a las actividades del "Deportivo Tepalcates"</p>
</div>

<div class="section-tag">👤 Datos personales</div>
<div class="fields-box">
<div class="grid-3">
<div class="form-group">
<label>Nombre Completo:</label>
<input type="text">
</div>
<div class="form-group">
<label>Fecha de nacimiento:</label>
<input type="date">
</div>
<div class="form-group">
<label>Género:</label>
<select><option>Seleccionar</option><option>M</option><option>F</option></select>
</div>
<div class="form-group">
<label>Edad:</label>
<input type="number">
</div>
<div class="form-group">
<label>Teléfono:</label>
<input type="tel">
</div>
<div class="form-group">
<label>Correo Electrónico:</label>
<input type="email">
</div>
</div>
</div>
</div>

<div>
<div class="section-tag">📄 Datos Adicionales</div>
<div class="fields-box">
<div class="form-group" style="margin-bottom: 8px;">
<label>¿Cómo te enteraste del deportivo?</label>
<input type="text">
</div>
<div class="form-group">
<label>¿Tienes alguna condición médica?</label>
<input type="text">
</div>
</div>

<div class="section-tag">📄 Contacto de Emergencia</div>
<div class="fields-box">
<div class="form-group" style="margin-bottom: 8px;">
<label>Nombre del titular:</label>
<input type="text">
</div>
<div class="form-group">
<label>Número Telefónico del titular:</label>
<input type="tel">
</div>
</div>

<div class="btn-container">
<button class="btn-submit">Enviar Solicitud</button>
</div>
</div>
</div>
</div>

<div class="card-footer">
<span>📍 Deportivo Tepalcates — <i>Más deporte, mejores personas</i></span>
<span>⚽ 🏀 🏐 🏊 🏋️</span>
</div>
</div>

<!-- ================= 2. FORMULARIO DE REGISTRO / DEPORTES ================= -->
<div class="form-card">
<div class="header-banner">
<div class="logo-section">
<h1>DEPORTIVO TEPALCATES</h1>
<p>Deporte • Salud • Comunidad</p>
</div>
<div class="motto">¡Tu esfuerzo también es parte del equipo!</div>
</div>

<div class="card-body">
<div class="form-title-bar">
<h2>Formulario de Registro</h2>
<p>Completa tus datos para inscribirte a las actividades del "Deportivo Tepalcates"</p>
</div>

<div class="section-tag">👤 Datos personales</div>
<div class="fields-box">
<div class="grid-3">
<div class="form-group"><label>Nombre Completo:</label><input type="text"></div>
<div class="form-group"><label>Fecha de nacimiento:</label><input type="date"></div>
<div class="form-group"><label>Género:</label><input type="text"></div>
<div class="form-group"><label>Edad:</label><input type="number"></div>
<div class="form-group"><label>Teléfono:</label><input type="tel"></div>
<div class="form-group"><label>Correo Electrónico:</label><input type="email"></div>
</div>
</div>

<div class="section-tag">🏃 Actividades / Deportes — Selecciona la disciplina:</div>
<div class="fields-box">
<div class="checkbox-group">
<div class="checkbox-item"><input type="checkbox"> Fútbol</div>
<div class="checkbox-item"><input type="checkbox"> Voleibol</div>
<div class="checkbox-item"><input type="checkbox"> Natación</div>
<div class="checkbox-item"><input type="checkbox"> Box</div>
<div class="checkbox-item"><input type="checkbox"> Básquetbol</div>
<div class="checkbox-item"><input type="checkbox"> Tenis</div>
<div class="checkbox-item"><input type="checkbox"> Kick Boxing</div>
<div class="checkbox-item"><input type="checkbox"> Taekwondo</div>
</div>
</div>

<div class="btn-container">
<button class="btn-submit">Enviar solicitud</button>
</div>
</div>

<div class="card-footer">
<span>📍 Deportivo Tepalcates — <i>Más deporte, mejores personas</i></span>
<span>⚽ 🏀 🏐 🏊 🏋️</span>
</div>
</div>

<!-- ================= 3. CONTROL DE ASISTENCIA ================= -->
<div class="form-card">
<div class="header-banner">
<div class="logo-section">
<h1>DEPORTIVO TEPALCATES</h1>
<p>Deporte • Salud • Comunidad</p>
</div>
<div class="motto">¡Tu esfuerzo también es parte del equipo!</div>
</div>

<div class="card-body">
<div class="form-title-bar">
<h2>Control de asistencia</h2>
<p>Registra la asistencia por actividad y participante.</p>
</div>

<div class="section-tag">👤 Datos del participante</div>
<div class="fields-box">
<div class="grid-3">
<div class="form-group"><label>Nombre completo:</label><input type="text"></div>
<div class="form-group"><label>Actividad:</label><input type="text"></div>
<div class="form-group"><label>Grupo / horario:</label><input type="text"></div>
<div class="form-group"><label>Mes:</label><input type="text"></div>
<div class="form-group"><label>Año:</label><input type="text"></div>
<div class="form-group"><label>Responsable:</label><input type="text"></div>
</div>
</div>

<div class="section-tag">🏃 Asistencia por sesión: marca el estado de cada fecha.</div>
<div class="fields-box">
<table class="attendance-table">
<thead>
<tr>
<th>Fecha</th>
<th>Asistió</th>
<th>Falta</th>
<th>Notas</th>
</tr>
</thead>
<tbody>
<tr>
<td><input type="text" placeholder="__ / __ / ____" style="width: 100px;"></td>
<td><input type="checkbox"></td>
<td><input type="checkbox"></td>
<td><input type="text"></td>
</tr>
<tr>
<td><input type="text" placeholder="__ / __ / ____" style="width: 100px;"></td>
<td><input type="checkbox"></td>
<td><input type="checkbox"></td>
<td><input type="text"></td>
</tr>
</tbody>
</table>
</div>

<div class="btn-container">
<button class="btn-submit">Guardar registro</button>
</div>
</div>

<div class="card-footer">
<span>📍 Deportivo Tepalcates — <i>Más deporte, mejores personas</i></span>
<span>⚽ 🏀 🏐 🏊 🏋️</span>
</div>
</div>

<!-- ================= 4. REPORTE DE INCIDENTE DEPORTIVO ================= -->
<div class="form-card">
<div class="header-banner">
<div class="logo-section">
<h1>DEPORTIVO TEPALCATES</h1>
<p>Deporte • Salud • Comunidad</p>
</div>
<div class="motto">¡Tu esfuerzo también es parte del equipo!</div>
</div>

<div class="card-body">
<div class="form-title-bar">
<h2>Reporte de incidente deportivo</h2>
<p>Registra un evento ocurrido durante una actividad.</p>
</div>

<div class="section-tag">👤 Datos del incidente</div>
<div class="fields-box">
<div class="grid-3">
<div class="form-group"><label>Participante:</label><input type="text"></div>
<div class="form-group"><label>Actividad:</label><input type="text"></div>
<div class="form-group"><label>Fecha:</label><input type="date"></div>
<div class="form-group"><label>Hora:</label><input type="time"></div>
<div class="form-group"><label>Lugar:</label><input type="text"></div>
<div class="form-group"><label>Reportado por:</label><input type="text"></div>
</div>
</div>

<div class="section-tag">🏃 Descripción y atención brindada</div>
<div class="fields-box">
<div class="checkbox-group" style="margin-bottom: 12px;">
<div class="checkbox-item"><input type="checkbox"> Lesión</div>
<div class="checkbox-item"><input type="checkbox"> Malestar</div>
<div class="checkbox-item"><input type="checkbox"> Accidente</div>
<div class="checkbox-item"><input type="checkbox"> Otro</div>
</div>
<div class="grid-2">
<div class="form-group">
<label>Descripción del incidente:</label>
<textarea rows="2"></textarea>
</div>
<div class="form-group">
<label>Atención brindada / persona notificada:</label>
<textarea rows="2"></textarea>
</div>
</div>
</div>

<div class="btn-container">
<button class="btn-submit">Guardar reporte</button>
</div>
</div>

<div class="card-footer">
<span>📍 Deportivo Tepalcates — <i>Más deporte, mejores personas</i></span>
<span>⚽ 🏀 🏐 🏊 🏋️</span>
</div>
</div>

<!-- ================= 5. SOLICITUD DE CAMBIO O BAJA ================= -->
<div class="form-card">
<div class="header-banner">
<div class="logo-section">
<h1>DEPORTIVO TEPALCATES</h1>
<p>Deporte • Salud • Comunidad</p>
</div>
<div class="motto">¡Tu esfuerzo también es parte del equipo!</div>
</div>

<div class="card-body">
<div class="form-title-bar">
<h2>Solicitud de cambio o baja</h2>
<p>Solicita actualizar datos o cambiar o cancelar una actividad.</p>
</div>

<div class="section-tag">👤 Datos del participante</div>
<div class="fields-box">
<div class="grid-3">
<div class="form-group"><label>Nombre completo:</label><input type="text"></div>
<div class="form-group"><label>Teléfono:</label><input type="tel"></div>
<div class="form-group"><label>Correo electrónico:</label><input type="email"></div>
<div class="form-group"><label>Actividad actual:</label><input type="text"></div>
<div class="form-group"><label>Grupo / horario:</label><input type="text"></div>
<div class="form-group"><label>Fecha:</label><input type="date"></div>
</div>
</div>

<div class="section-tag">🏃 Tipo de solicitud y detalle</div>
<div class="fields-box">
<div class="checkbox-group" style="margin-bottom: 12px; grid-template-columns: repeat(3, 1fr);">
<div class="checkbox-item"><input type="radio" name="solicitud"> Actualizar datos</div>
<div class="checkbox-item"><input type="radio" name="solicitud"> Cambiar actividad</div>
<div class="checkbox-item"><input type="radio" name="solicitud"> Cambiar horario</div>
<div class="checkbox-item"><input type="radio" name="solicitud"> Baja temporal</div>
<div class="checkbox-item"><input type="radio" name="solicitud"> Baja definitiva</div>
</div>
<div class="form-group">
<label>Detalle de la solicitud:</label>
<textarea rows="2"></textarea>
</div>
</div>

<div class="btn-container">
<button class="btn-submit">Enviar solicitud</button>
</div>
</div>

<div class="card-footer">
<span>📍 Deportivo Tepalcates — <i>Más deporte, mejores personas</i></span>
<span>⚽ 🏀 🏐 🏊 🏋️</span>
</div>
</div>

</body>
</html>

