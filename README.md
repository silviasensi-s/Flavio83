<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Profilo Personale</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #dbeafe, #bfdbfe, #93c5fd);
      color: #1e293b;
      padding: 30px 15px;
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
      background: white;
      border-radius: 24px;
      overflow: hidden;
      box-shadow: 0 12px 30px rgba(30, 64, 175, 0.15);
    }

    .hero {
      background: linear-gradient(135deg, #2563eb, #1d4ed8, #1e40af);
      color: white;
      text-align: center;
      padding: 50px 25px;
    }

    .hero h1 {
      font-size: 2.4rem;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 700px;
      margin: 0 auto;
      font-size: 1.05rem;
      line-height: 1.7;
      color: rgba(255, 255, 255, 0.92);
    }

    .sections {
      display: grid;
      grid-template-columns: 1fr;
      gap: 24px;
      padding: 30px;
    }

    .card {
      background: #eff6ff;
      border-left: 6px solid #2563eb;
      border-radius: 18px;
      padding: 24px;
      box-shadow: 0 6px 16px rgba(37, 99, 235, 0.08);
      transition: transform 0.25s ease, box-shadow 0.25s ease;
    }

    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 10px 20px rgba(37, 99, 235, 0.15);
    }

    .card h2 {
      font-size: 1.4rem;
      color: #1d4ed8;
      margin-bottom: 12px;
    }

    .card p {
      font-size: 1rem;
      line-height: 1.7;
      color: #334155;
    }

    .footer {
      text-align: center;
      padding: 20px;
      background: #dbeafe;
      color: #1e3a8a;
      font-size: 0.95rem;
    }

    @media (min-width: 768px) {
      .sections {
        grid-template-columns: repeat(3, 1fr);
      }

      .hero h1 {
        font-size: 2.8rem;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <header class="hero">
      <h1>Ciao, sono Flavio👋</h1>
      <p>
        Ho 14 anni e sono un ragazzo curioso, socievole e pieno di energia.
        Mi piace conoscere nuove persone, imparare cose interessanti e immaginare
        il mio futuro con entusiasmo. Ogni giorno cerco di migliorarmi e di vivere
        nuove esperienze che mi aiutino a crescere.
      </p>
    </header>

    <main class="sections">
      <section class="card">
        <h2>🎧 Hobby</h2>
        <p>
          Nel mio tempo libero mi piace ascoltare musica, fare sport e uscire con i miei amici.
          Amo anche guardare film, serie TV e passare del tempo online per scoprire novità
          e argomenti che mi incuriosiscono.
        </p>
      </section>

      <section class="card">
        <h2>📚 Scuola</h2>
        <p>
          Frequento la scuola superiore e cerco di impegnarmi ogni giorno.
          Mi piacciono soprattutto le materie in cui posso usare creatività,
          logica e immaginazione. La scuola per me è anche un luogo dove crescere
          e confrontarmi con gli altri.
        </p>
      </section>

      <section class="card">
        <h2>✨ Sogni</h2>
        <p>
          Il mio sogno è costruire un futuro che mi rappresenti davvero,
          sviluppare le mie passioni e fare esperienze importanti.
          Vorrei crescere come persona, realizzare i miei obiettivi
          e trovare una strada che mi renda felice.
        </p>
      </section>
    </main>

    <footer class="footer">
      Pagina personale in HTML e CSS - stile moderno blu
    </footer>
  </div>

</body>
</html>
