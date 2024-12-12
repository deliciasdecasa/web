<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Delicias de Casa - Mi cocina a tu escritorio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #f28d66;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-size: 1.2em;
            margin: 0;
        }
        nav {
            background-color: #e7e7e7;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #333;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.1em;
        }
        nav a:hover {
            color: #f28d66;
        }
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin: 20px 0;
        }
        .menu-item {
            margin: 10px;
            text-align: center;
        }
        .menu-item img {
            width: 150px;
            height: 150px;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        .menu-item img:hover {
            transform: scale(1.1);
        }
        .menu-item h3 {
            margin-top: 10px;
            font-size: 1.2em;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .button {
            display: inline-block;
            background-color: #f28d66;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.1em;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #e67e4d;
        }
    </style>
</head>
<body>

    <header>
        <h1>Delicias de Casa</h1>
        <p>De mi cocina a tu escritorio</p>
    </header>

    <nav>
        <a href="#menu">Menú Semanal</a>
        <a href="#whatsapp">WhatsApp</a>
        <a href="#cuenta">Cuenta Bancaria</a>
    </nav>

    <section id="menu">
        <h2>Menú Semanal</h2>
        <p>Descubre lo que tenemos para ofrecerte esta semana. Comidas caseras con el mejor sabor.</p>

        <div class="menu">
            <div class="menu-item">
                <img src="images/sopa_pollo.jpg" alt="Sopa de Pollo">
                <h3>Lunes: Sopa de Pollo</h3>
            </div>
            <div class="menu-item">
                <img src="images/arroz_pollo.jpg" alt="Arroz con Pollo">
                <h3>Martes: Arroz con Pollo</h3>
            </div>
            <div class="menu-item">
                <img src="images/tacos_carne.jpg" alt="Tacos de Carne Asada">
                <h3>Miércoles: Tacos de Carne</h3>
            </div>
            <div class="menu-item">
                <img src="images/pasta.jpg" alt="Pasta con Salsa">
                <h3>Jueves: Pasta con Salsa</h3>
            </div>
            <div class="menu-item">
                <img src="images/pescado.jpg" alt="Pescado al Horno">
                <h3>Viernes: Pescado al Horno</h3>
            </div>
        </div>
    </section>

    <section id="whatsapp">
        <h2>Contáctanos por WhatsApp</h2>
        <p>¿Tienes alguna pregunta o quieres hacer un pedido? Haz clic en el siguiente enlace para hablar con nosotros en WhatsApp.</p>
        <a href="https://wa.me/1234567890" class="button">Chatea con nosotros</a>
    </section>

    <section id="cuenta">
        <h2>Cuenta Bancaria</h2>
        <p>Si deseas realizar un pago, puedes hacerlo a través de la siguiente cuenta bancaria:</p>
        <p><strong>Banco: XYZ</strong></p>
        <p><strong>Cuenta: 1234567890</strong></p>
        <p><strong>CLABE: 9876543210</strong></p>
        <p>¡Gracias por confiar en nosotros!</p>
    </section>

    <footer>
        <p>&copy; 2024 Delicias de Casa. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
