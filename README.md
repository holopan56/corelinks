<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MATAJIR CORELINKS</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #007bff; color: white; padding: 1em; text-align: center; }
    nav a { color: white; margin: 0 1em; text-decoration: none; }
    nav a:hover { text-decoration: underline; }
    .hero { padding: 2em; background: #f5f5f5; text-align: center; }
    .products { display: flex; flex-wrap: wrap; justify-content: center; gap: 1em; padding: 2em; }
    .product { border: 1px solid #ddd; padding: 1em; width: 200px; box-shadow: 2px 2px 5px rgba(0,0,0,0.1); border-radius: 5px; }
    .product img { max-width: 100%; height: auto; border-radius: 5px; }
    .product button { margin-top: 0.5em; background: #007bff; border: none; color: white; padding: 0.5em 1em; cursor: pointer; border-radius: 3px; }
    section#contact { padding: 2em; text-align: center; background: #eee; }
    section#contact button { background: #25d366; border: none; color: white; padding: 0.5em 1em; cursor: pointer; border-radius: 3px; }
    footer { background: #333; color: white; text-align: center; padding: 1em; font-size: 0.9em; }
  </style>
</head>
<body>

<header>
  <h1>MATAJIR CORELINKS</h1>
  <nav>
    <a href="#home">Accueil</a>
    <a href="#products">Produits</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero" id="home">
  <h2>L’avenir du e-commerce commence ici</h2>
  <p>Bienvenue chez MATAJIR CORELINKS, la plateforme qui connecte les marchands du futur.</p>
  <button onclick="window.location.href='mailto:contact@corelinksframer.com'">Contactez-nous</button>
</section>

<section class="products" id="products">
  <h2>Nos produits phares</h2>

  <div class="product">
    <img src="https://via.placeholder.com/200" alt="Produit 1" />
    <h3>Produit 1</h3>
    <p>Description courte du produit 1.</p>
    <p>Prix : 100 MAD</p>
    <button>Acheter</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/200" alt="Produit 2" />
    <h3>Produit 2</h3>
    <p>Description courte du produit 2.</p>
    <p>Prix : 200 MAD</p>
    <button>Acheter</button>
  </div>

  <!-- Tu peux copier/coller ce bloc pour ajouter d'autres produits -->

</section>

<section id="contact">
  <h2>Contactez-nous</h2>
  <p>Email : contact@corelinksframer.com</p>
  <p>Téléphone : +212 6 12 34 56 78</p>
  <button onclick="window.location.href='https://wa.me/212612345678'">Nous joindre sur WhatsApp</button>
</section>

<footer>
  <p>&copy; 2025 MATAJIR CORELINKS - Tous droits réservés</p>
</footer>

</body>
</html>
