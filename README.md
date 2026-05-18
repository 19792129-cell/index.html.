# index.html.
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Yansi Hernández</title>

<style>

body{
background:#0F172A;
font-family:Arial;
color:white;
text-align:center;
padding:40px;
}

h1{
font-size:50px;
color:#C084FC;
}

form{
max-width:500px;
margin:auto;
background:#111827;
padding:30px;
border-radius:20px;
}

input, textarea{
width:90%;
padding:15px;
margin:10px;
border:none;
border-radius:10px;
background:#1F2937;
color:white;
}

button{
padding:15px 40px;
border:none;
border-radius:10px;
background:#7C3AED;
color:white;
font-size:18px;
cursor:pointer;
}

</style>

</head>

<body>

<h1>Yansi Hernández 💜</h1>

<h2>Formulario de Contacto</h2>

<form action="https://formspree.io/f/xpqnwrpk" method="POST">

<input type="text" name="nombre" placeholder="Tu Nombre" required>

<input type="email" name="email" placeholder="Tu Correo" required>

<input type="tel" name="telefono" placeholder="Tu Teléfono" required>

<textarea name="mensaje" placeholder="Escribe tu mensaje" required></textarea>

<button type="submit">Enviar 🚀</button>

</form>

</body>
</html>
