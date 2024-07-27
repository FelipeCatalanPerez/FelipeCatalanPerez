<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Felipe Ignacio Catalán Perez</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Roboto:wght@400&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333333;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .header {
            text-align: center;
            padding: 50px;
            background-color: #f5f5f5;
        }
        .header h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 2.5em;
            margin: 0;
        }
        .header p {
            font-size: 1.2em;
            margin-top: 10px;
            color: #666666;
        }
        .projects {
            margin: 20px 0;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }
        .project {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .project-title {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.5em;
            margin: 10px 0;
            color: #007acc;
        }
        .project-title a {
            text-decoration: none;
            color: #007acc;
        }
        .project-title a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Felipe Ignacio Catalán Perez</h1>
            <p>Ingeniero Comercial y Analista de Datos</p>
        </div>
        <div class="projects">
            <div class="project">
                <h2 class="project-title"><a href="https://github.com/FelipeCatalanPerez/CNN_SUV">CNN_SUV</a></h2>
                <p>Modelo clasificador basado en Deep Learning.</p>
            </div>
            <div class="project">
                <h2 class="project-title"><a href="https://github.com/FelipeCatalanPerez/Modelo-clasificador-de-correos-SPAM">Modelo Clasificador de Correos SPAM</a></h2>
                <p>Regresión Logística y Gaussian Naive Bayes.</p>
            </div>
        </div>
    </div>
</body>
</html>
