# Fantomes
Débusques tes abonnements inutilisés 
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Fantômes — Débusquez les abonnements que vous ne remarquez plus</title>
<meta name="description" content="Déposez votre relevé bancaire. On repère les abonnements oubliés et on génère vos lettres de résiliation. Audit complet à 19 €.">

<meta property="og:title" content="Fantômes — Débusquez les abonnements que vous ne remarquez plus">
<meta property="og:description" content="Déposez votre relevé bancaire. On repère les abonnements oubliés et on génère vos lettres de résiliation.">
<meta property="og:type" content="website">

<style>
  :root {
    --navy: #1A2332;
    --mustard: #E8A93B;
    --cream: #FAF6EE;
    --ink: #2A2A28;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  html { scroll-padding-top: env(safe-area-inset-top, 0px); }
  body {
    background: var(--cream);
    color: var(--ink);
    font-family: -apple-system, "Public Sans", "Segoe UI", sans-serif;
    line-height: 1.5;
    padding-top: env(safe-area-inset-top, 0px);
    padding-bottom: env(safe-area-inset-bottom, 0px);
  }
  .hero {
    background: var(--navy);
    color: var(--cream);
    padding: 48px 20px 40px;
    text-align: center;
  }
  .hero h1 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: clamp(28px, 7vw, 40px);
    line-height: 1.15;
    max-width: 480px;
    margin: 0 auto 16px;
  }
  .hero p {
    font-size: 17px;
    opacity: 0.85;
    max-width: 420px;
    margin: 0 auto;
  }
  .container { max-width: 480px; margin: 0 auto; padding: 32px 20px; }
  .benefits { display: flex; flex-direction: column; gap: 20px; margin-bottom: 32px; }
  .benefit { display: flex; gap: 14px; align-items: flex-start; }
  .benefit .num {
    background: var(--mustard);
    color: var(--navy);
    font-weight: 700;
    font-family: Georgia, serif;
    width: 32px; height: 32px;
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
  }
  .benefit h3 { font-size: 17px; margin-bottom: 2px; }
  .benefit p { font-size: 15px; color: #555; }
  .cta-wrap {
    position: sticky;
    bottom: 0;
    background: linear-gradient(to top, var(--cream) 60%, transparent);
    padding: 24px 20px 16px;
    text-align: center;
  }
  .cta {
    display: block;
    background: var(--mustard);
    color: var(--navy);
    font-weight: 700;
    font-size: 18px;
    text-decoration: none;
    padding: 18px 24px;
    border-radius: 12px;
    max-width: 480px;
    margin: 0 auto;
    box-shadow: 0 4px 14px rgba(0,0,0,0.15);
  }
  .cta small { display: block; font-weight: 400; font-size: 13px; margin-top: 2px; }
  .reassurance {
    text-align: center;
    font-size: 13px;
    color: #777;
    margin-top: 10px;
  }
  footer {
    text-align: center;
    font-size: 12px;
    color: #999;
    padding: 24px 20px 40px;
  }
</style>
</head>
<body>

  <div class="hero">
    <h1>Vous payez chaque mois des abonnements que vous avez oubliés.</h1>
    <p>Un essai jamais résilié, un service remplacé, une option activée une fois. Trop petits pour se voir sur un relevé. Trop nombreux pour disparaître tout seuls.</p>
  </div>

  <div class="container">
    <div class="benefits">
      <div class="benefit">
        <div class="num">1</div>
        <div>
          <h3>Déposez votre relevé bancaire</h3>
          <p>Un PDF suffit. Rien à trier, rien à cocher.</p>
        </div>
      </div>
      <div class="benefit">
        <div class="num">2</div>
        <div>
          <h3>On repère chaque prélèvement récurrent</h3>
          <p>Classés par ce qu'ils vous coûtent vraiment sur un an, pas par mois.</p>
        </div>
      </div>
      <div class="benefit">
        <div class="num">3</div>
        <div>
          <h3>Vous recevez vos lettres de résiliation</h3>
          <p>Prêtes à envoyer, pour chaque abonnement que vous voulez arrêter.</p>
        </div>
      </div>
    </div>
  </div>

  <div class="cta-wrap">
    <a class="cta" href="https://buy.stripe.com/test_aFa8wO6ireUYfAke543wQ00">
      Faire mon audit — 19 €
      <small>Paiement unique, sans engagement</small>
    </a>
    <p class="reassurance">Paiement sécurisé par Stripe · Accès envoyé par email</p>
  </div>

  <footer>
    © Fantômes 2026 — Mentions légales et CGV en cours de publication.
  </footer>

</body>
</html>
