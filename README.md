<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Musica</title>
</head>
<body>
    <header> 
         <h1> Musica Angolana </h1>
    </header>
        <main>
            <section>
           <input type="text" placeholder="Digite o nome do musico" id= "campo-pesquisa">
           <button onclick="Buscar()">Buscar</button>
        </section>
        <section class="resultados-pesquisa" 
        id = "resultados-pesquisa" >
        </section>
        </main>
        <footer>
            <p>2024 - musicas mais ouvidas de Angola. as mais ouvidas </p>
            <p>procurem por nossas informacoes no whatsapp: 9588885566166</p>
        </footer>
        <script src="dados.js"></script>
    </body>
        <script src="app.js"></script>
</body>

</html> 
