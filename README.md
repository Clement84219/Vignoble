<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Le Vignoble de France 🍇</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fdf6f0;
            color: #333;
        }
        header {
            background-color: #4b2e1f;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            font-family: 'Playfair Display', serif;
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            background-color: #7a4c2a;
            display: flex;
            justify-content: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            padding: 15px 0;
        }
        nav a:hover {
            color: #ffd700;
        }
        section {
            padding: 50px 20px;
            max-width: 1000px;
            margin: auto;
        }
        section h2 {
            font-family: 'Playfair Display', serif;
            color: #4b2e1f;
            text-align: center;
            margin-bottom: 20px;
        }
        .cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            width: 280px;
            text-align: center;
            transition: transform 0.2s;
        }
        .card:hover {
            transform: scale(1.05);
        }
        footer {
            background-color: #4b2e1f;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>

<header>
    <h1>Le Vignoble de France 🍇</h1>
    <p>Tradition, passion et excellence viticole</p>
</header>

<nav>
    <a href="#lore">Histoire</a>
    <a href="#produits">Produits</a>
    <a href="#recrutement">Recrutement</a>
    <a href="#contact">Contact</a>
</nav>

<section id="lore">
    <h2>Notre Histoire</h2>
    <p>
        Le Vignoble de France est né d’une passion pour la terre et la vigne. Depuis plusieurs générations, 
        notre famille cultive les vignes avec patience et savoir-faire. Chaque raisin est récolté avec soin 
        et chaque bouteille raconte une histoire unique.
    </p>
</section>

<section id="produits">
    <h2>Nos Produits</h2>
    <div class="cards">
        <div class="card">
            <h3>Vin Rouge</h3>
            <p>Un vin fruité et corsé, parfait pour accompagner vos repas.</p>
        </div>
        <div class="card">
            <h3>Vin Blanc</h3>
            <p>Un vin frais et délicat, idéal pour les apéritifs et plats légers.</p>
        </div>
        <div class="card">
            <h3>Vin Rosé</h3>
            <p>Un vin léger et floral, parfait pour les journées ensoleillées.</p>
        </div>
    </div>
</section>

<section id="recrutement">
    <h2>Rejoignez notre équipe</h2>
    <p>
        Nous recherchons des passionnés pour travailler au sein du Vignoble de France. 
        Postes disponibles : vignerons, sommeliers, livreurs et commerciaux. 
        Rejoignez une entreprise où tradition et excellence sont au cœur de chaque activité.
    </p>
</section>

<section id="contact">
    <h2>Contactez-nous</h2>
    <p>Email : contact@levignobledefrance.fr</p>
    <p>Téléphone : +33 1 23 45 67 89</p>
    <p>Adresse : 12 Route des Vignes, 75000 Paris, France</p>
</section>

<footer>
    &copy; 2026 Le Vignoble de France. Tous droits réservés.
</footer>

</body>
</html>
