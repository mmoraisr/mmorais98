<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Matheus Ribeiro | Portfólio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet"/>
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #0e0e10;
      color: #fff;
      line-height: 1.6;
    }

    header {
      background: #1f1f22;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #aaa;
    }

    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .highlight {
      color: #00ff99;
    }

    .card {
      background: #1c1c1f;
      padding: 1.5rem;
      border-radius: 12px;
      margin-bottom: 1.5rem;
      box-shadow: 0 0 15px #111;
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.02);
    }

    footer {
      text-align: center;
      padding: 1rem;
      color: #666;
      background: #111;
    }

    a {
      color: #00ffcc;
      text-decoration: none;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Matheus Ribeiro</h1>
  <p>Auditor | Especialista em Compliance | Desenvolvedor em formação</p>
</header>

<section>
  <h2 class="highlight">Sobre Mim</h2>
  <div class="card">
    <p>Sou formado em Direito, com pós-graduação em Compliance e atualmente estou cursando Análise e Desenvolvimento de Sistemas. Tenho experiência sólida com auditoria e projetos de integridade, e agora estou expandindo para o universo da tecnologia com foco em automações e inteligência artificial.</p>
  </div>

  <h2 class="highlight">Empresa: Autonoma IA</h2>
  <div class="card">
    <p><strong>Autonoma IA</strong> é minha nova empresa focada em soluções inteligentes de automação. Nosso lema é: <em>"Sua empresa independente"</em>. Criamos agentes como:</p>
    <ul>
      <li>🤖 Agente de agendamento com integração ao Google Agenda</li>
      <li>💬 Chatbot inteligente para atendimento básico</li>
      <li>📞 Agente SDR para prospecção automatizada</li>
    </ul>
  </div>

  <h2 class="highlight">Projetos</h2>
  <div class="grid">
    <div class="card">
      <h3>Agente de Agendamento</h3>
      <p>Automatiza marcações e envia invites pelo Google Agenda. Ideal para clínicas, consultórios e prestadores de serviço.</p>
    </div>
    <div class="card">
      <h3>Chatbot Simples</h3>
      <p>Responde perguntas frequentes e coleta dados do cliente. Pode ser integrado ao WhatsApp ou site.</p>
    </div>
    <div class="card">
      <h3>Agente SDR</h3>
      <p>Faz a prospecção inicial de leads e repassa os qualificados para o time de vendas.</p>
    </div>
  </div>

  <h2 class="highlight">Contato</h2>
  <div class="card">
    <p>📧 Email: seuemail@email.com<br/>
       💼 LinkedIn: <a href="https://www.linkedin.com/in/seuperfil" target="_blank">linkedin.com/in/seuperfil</a><br/>
       🌐 GitHub: <a href="https://github.com/seuperfil" target="_blank">github.com/seuperfil</a>
    </p>
  </div>
</section>

<footer>
  <p>© 2025 Matheus Ribeiro. Todos os direitos reservados.</p>
</footer>

</body>
</html>
