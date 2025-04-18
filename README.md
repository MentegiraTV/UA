<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Universidade Amoedo + Emissora PET</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #0057b8;
      --secondary: #007edc;
      --light: #f4faff;
      --dark: #0a1f44;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background-color: var(--light);
      color: var(--dark);
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }
    .container {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .content {
      margin-bottom: 40px;
    }
    .content h2 {
      color: var(--primary);
      margin-bottom: 20px;
    }
    .content p {
      margin-bottom: 15px;
    }
    .form-container {
      background-color: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0, 87, 184, 0.1);
    }
    .form-container form {
      display: flex;
      flex-direction: column;
    }
    .form-container input,
    .form-container textarea {
      padding: 12px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    .form-container button {
      background-color: var(--primary);
      color: white;
      padding: 12px;
      border: none;
      border-radius: 6px;
      font-weight: 600;
      cursor: pointer;
      transition: background 0.3s;
    }
    .form-container button:hover {
      background-color: var(--dark);
    }
    footer {
      background-color: var(--dark);
      color: white;
      text-align: center;
      padding: 30px 20px;
    }
    .socials {
      margin-top: 15px;
    }
    .socials a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
      font-size: 1.2rem;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
      .content h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Universidade Amoedo + Emissora PET</h1>
    <p>Transformando conhecimento em conteúdo. Conectando toda a cadeia do mercado PET.</p>
  </header>

  <div class="container">
    <div class="content">
      <h2>Sobre o Projeto</h2>
      <p>Estamos criando a primeira emissora do Brasil dedicada a educação, entretenimento e desenvolvimento do setor PET. Em parceria com a Universidade Amoedo, nossa proposta é conectar especialistas, lojistas, distribuidores, tutores e apaixonados por animais em uma jornada de transformação.</p>
      <p>Nosso conteúdo é baseado em dados reais, prática de campo e colaboração com os principais profissionais do mercado. Queremos produzir juntos, crescer juntos e educar o Brasil com linguagem acessível, confiável e moderna.</p>
    </div>

    <div class="form-container">
      <h2>Entre em Contato</h2>
      <form action="https://formspree.io/f/SEU_ID_AQUI" method="POST">
        <input type="text" name="name" placeholder="Seu nome" required />
        <input type="email" name="email" placeholder="Seu e-mail" required />
        <textarea name="message" rows="5" placeholder="Sua mensagem ou proposta" required></textarea>
        <button type="submit">Enviar</button>
      </form>
    </div>
  </div>

  <footer>
    <p>© 2025 Universidade Amoedo + Emissora PET</p>
    <div class="socials">
      <a href="https://instagram.com/seuperfil" target="_blank">Instagram</a>
      <a href="https://linkedin.com/in/seuperfil" target="_blank">LinkedIn</a>
      <a href="https://youtube.com/seucanal" target="_blank">YouTube</a>
    </div>
  </footer>

</body>
</html>
