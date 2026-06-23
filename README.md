<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Meu Blog Tech</title>

<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family: 'Segoe UI', sans-serif;
    }

    body{
        background: linear-gradient(135deg, #0078d7, #001f3f);
        color: white;
        min-height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 20px;
    }

    .container{
        max-width: 900px;
        width: 100%;
        background: rgba(20,20,40,0.9);
        border-radius: 20px;
        padding: 30px;
        box-shadow: 0 0 30px rgba(0,0,0,0.4);
        backdrop-filter: blur(10px);
    }

    header{
        text-align: center;
        margin-bottom: 30px;
    }

    header h1{
        font-size: 3rem;
        color: #4fc3ff;
        margin-bottom: 10px;
    }

    header p{
        color: #cfd8dc;
    }

    .post{
        background: #0d1117;
        border-left: 5px solid #4fc3ff;
        padding: 20px;
        border-radius: 10px;
        margin-top: 20px;
    }

    .post h2{
        color: #4fc3ff;
        margin-bottom: 10px;
    }

    .autor{
        color: #9cdcfe;
        margin-bottom: 15px;
    }

    footer{
        text-align: center;
        margin-top: 30px;
        color: #cfd8dc;
        font-size: 0.9rem;
    }
</style>
</head>

<body>

<div class="container">

    <header>
        <h1>💻 Meu Blog Tech</h1>
        <p>Compartilhando conhecimentos sobre tecnologia e programação</p>
    </header>

    <main>
        <div class="post">
            <h2>🚀 Meu Primeiro Post</h2>
            <p class="autor">Por: Giovana Ferreira de Mello

            <p>
                Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de
                programação, desenvolvimento web, inteligência artificial
                e curiosidades do mundo da tecnologia.
            </p>
        </div>
    </main>

    <footer>
        © 2026 Meu Blog Tech - Todos os direitos reservados.
    </footer>

</div>

</body>
</html>
