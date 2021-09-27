# ProyectoPatitas
pantallas de maquetado web para el proyecto "Rescate de patitas"
Este proyecto fue parte de la cursada de la materia Diseño de sistemas de la carrera Ingenieria en sistemas en UTN-frba. 

<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.4.0/font/bootstrap-icons.css">
    <link rel="stylesheet" href="./pantallaAdmin.css">
    <script src="js/formulario-quiero-adoptar.js"></script>
    <script src="https://kit.fontawesome.com/7fcb757e78.js" crossorigin="anonymous"></script>
    <title>Admin - Pantalla</title>
</head>

<body>
    <h1 class="texto-banner">PATITAS AL RESCATE</h1>

    <div class="imgcontainer">
        <img src="../login.jpg" alt="Avatar" class="avatar">
    </div>
    <main class="container">
        <h1>ONG</h1>
        <div class="row mt-4">
            <div class="col-12">
                <form action="">
                    <div class="row">
                        <div class="col-6">
                            <label for="" class="form-label ">Nombre</label>
                            <input type="text" class="form-control">
                        </div>
                        <div class="col-6">
                            <label for="" class="form-label ">Direccion</label>
                            <input type="text" class="form-control">
                        </div>
                    </div>
                    <div class="row mt-3">

                        <div class="col-6">
                            <h3>Formato fotos</h3>
                            <label for="" class="form-label ">Alto</label>
                            <input type="text" class="form-control">
                            <label for="" class="form-label ">Ancho</label>
                            <input type="text" class="form-control">
                        </div>
                    </div>
                    
                    <div class="row mt-3">
                        <h3 class="mt-3">Agregar preguntas</h3>
                        <div class="col-10">
                            <input type="text" class="form-control">
                        </div>
                        <div class="col d-flex justify-content-end" >
                            <input type="button" class="boton " value="AGREGAR">
                        </div>
                    </div>
                    <br><br>
                    <div class="row mt-3 mb-5">
                        <div class="col-12 d-flex justify-content-end">
                            <input type="button" class="boton " value="ACEPTAR">
                            <input type="button" class="botonEliminar" value="CANCELAR">
                        </div>
                    </div>
                </form>
            </div>
        </div>

    </main>


    <script src="js/bootstrap.bundle.min.js "></script>
</body>

</html>
