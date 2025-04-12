<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>JENNO</title>
  <style>
    body {
      margin: 0;
      background-color: #000;
      color: #fff;
      font-family: 'Helvetica Neue', sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
      background-image: radial-gradient(circle at center, #0A0A5B 0%, #000 100%);
    }
    h1 {
      font-size: 4em;
      color: #0078FF;
      text-shadow: 0 0 10px #00FFFF, 0 0 20px #00FFFF;
      animation: fadeIn 2s ease-in-out;
      letter-spacing: 6px;
    }
    .photo {
      width: 300px;
      height: 300px;
      background-image: url('sua-foto.jpg'); /* Substitua pelo caminho da sua foto */
      background-size: cover;
      background-position: center;
      border-radius: 50%;
      margin: 20px 0;
      box-shadow: 0 0 20px #0078FF;
      animation: fadeIn 2s ease-in-out 0.5s forwards;
      opacity: 0;
    }
    .links {
      display: flex;
      gap: 20px;
      opacity: 0;
      animation: fadeIn 2s ease-in-out 1s forwards;
    }
    .links a {
      color: white;
      text-decoration: none;
      font-size: 1.2em;
      transition: color 0.3s;
    }
    .links a:hover {
      color: #0078FF;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <h1>JENNO</h1>
  <div class="photo"></div>
  <div class="links">
    <a href="https://instagram.com/jennokca" target="_blank">Instagram</a>
    <a href="https://youtube.com/seucanal" target="_blank">YouTube</a>
    <a href="https://open.spotify.com/artist/seuartista" target="_blank">Spotify</a>
  </div>
</body>
</html>