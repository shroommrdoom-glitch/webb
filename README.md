<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplicación Web - Producción</title>

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        body{
            background:#f5f5f5;
        }

        .hero{
            background:#0d6efd;
            color:white;
            padding:70px 20px;
            text-align:center;
        }

        .card{
            transition:.3s;
        }

        .card:hover{
            transform:scale(1.05);
            box-shadow:0 0 15px rgba(0,0,0,.2);
        }

        footer{
            background:#212529;
            color:white;
            padding:15px;
            text-align:center;
            margin-top:40px;
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">

        <a class="navbar-brand" href="#">
            Sistema Web
        </a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="menu">

            <ul class="navbar-nav ms-auto">

                <li class="nav-item">
                    <a class="nav-link active" href="#">Inicio</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">Servicios</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">CRUD</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#">Contacto</a>
                </li>

            </ul>

        </div>

    </div>
</nav>

<section class="hero">

    <div class="container">

        <h1>Aplicación Web Estática y Dinámica</h1>

        <p class="lead">
            Proyecto desarrollado con HTML, CSS, JavaScript, Bootstrap, PHP y MySQL.
        </p>

        <button class="btn btn-warning btn-lg" onclick="mensaje()">
            Ingresar
        </button>

    </div>

</section>

<div class="container mt-5">

    <div class="row">

        <div class="col-md-4">

            <div class="card">

                <div class="card-body">

                    <h3 class="card-title">Frontend</h3>

                    <p class="card-text">
                        Desarrollo con HTML5, CSS3, JavaScript y Bootstrap.
                    </p>

                </div>

            </div>

        </div>

        <div class="col-md-4">

            <div class="card">

                <div class="card-body">

                    <h3 class="card-title">Backend</h3>

                    <p class="card-text">
                        Sistema dinámico desarrollado con PHP.
                    </p>

                </div>

            </div>

        </div>

        <div class="col-md-4">

            <div class="card">

                <div class="card-body">

                    <h3 class="card-title">Base de Datos</h3>

                    <p class="card-text">
                        Gestión de información mediante MySQL con operaciones CRUD.
                    </p>

                </div>

            </div>

        </div>

    </div>

</div>

<footer>

    <p>
        © 2026 Aplicación Web | Desplegada en Producción | Git & GitHub
    </p>

</footer>

<script>

function mensaje(){

    alert("Bienvenido al Sistema Web");

}

</script>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
