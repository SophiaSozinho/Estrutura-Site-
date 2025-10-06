<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Artistas Preferidos</title>
  <link rel="icon" href="icone.png" type="image/png">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🎶 Meus Artistas Preferidos 🎤</h1>
  </header>

  <main>
    <section class="bloco">
      <h2>Evanescence</h2>
      <p>A banda de rock gótico liderada por Amy Lee. Sons marcantes e letras intensas!</p>
      <img src="evanescence.jpg" alt="Evanescence">
      <button onclick="alert('Mais sobre Evanescence em breve!')">Saiba mais</button>
    </section>

    <section class="bloco">
      <h2>Britney Spears</h2>
      <p>Ícone do pop dos anos 2000. Hits que marcaram uma geração!</p>
      <img src="britney spears.jpg" alt="Britney Spears">
      <button onclick="alert('Mais sobre Britney em breve!')">Saiba mais</button>
    </section>
  </main>

  <footer>
    <p>Feito por Sophia  </p>
  </footer>
</body>
</html>



css


/* Reset básico */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: linear-gradient(to right, #fdf0f7, #e0c3fc);
  color: #333;
}

/* Cabeçalho */
header {
  background-color: #bb86fc;
  color: white;
  padding: 20px;
  text-align: center;
  font-size: 1.8em;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

/* Conteúdo principal */
main {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 30px;
}

/* Blocos de artistas */
.bloco {
  background: white;
  border-radius: 15px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  padding: 20px;
  width: 280px;
  text-align: center;
  transition: transform 0.3s ease;
}

.bloco:hover {
  transform: scale(1.05);
}

.bloco img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  margin: 15px 0;
  border: 4px solid #bb86fc;
}

.bloco p {
  font-size: 1em;
  margin-bottom: 15px;
}

/* Botões */
button {
  background-color: #bb86fc;
  color: white;
  border: none;
  padding: 10px 20px;
  font-weight: bold;
  border-radius: 20px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #9f6ce0;
}

/* Rodapé */
footer {
  text-align: center;
  padding: 15px;
  background-color: #f3e8ff;
  color: #555;
  margin-top: 40px;
