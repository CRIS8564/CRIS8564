<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Club de Padel</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 1rem;
            text-decoration: none;
        }
        .content {
            padding: 2rem;
        }
        .section {
            margin-bottom: 2rem;
        }
        .section h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 0.5rem;
        }
        .photos img {
            max-width: 100%;
            height: auto;
            margin: 0.5rem 0;
        }
        .footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue au Club de Padel</h1>
    </header>
    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#horaires">Horaires</a>
        <a href="#tarifs">Tarifs</a>
        <a href="#reservation">Réservation en ligne</a>
        <a href="#photos">Photos</a>
        <a href="#evenements">Événements</a>
    </nav>
    <div class="content">
        <div id="accueil" class="section">
            <h2>Accueil</h2>
            <p>Bienvenue au Club de Padel, un lieu convivial et sportif où vous pouvez pratiquer le padel dans une ambiance chaleureuse. Que vous soyez débutant ou joueur confirmé, notre club est ouvert à tous !</p>
        </div>
        <div id="horaires" class="section">
            <h2>Horaires</h2>
            <p>Nous sommes ouverts tous les jours de la semaine :</p>
            <ul>
                <li>Lundi - Vendredi : 8h00 - 22h00</li>
                <li>Samedi : 9h00 - 20h00</li>
                <li>Dimanche : 10h00 - 18h00</li>
            </ul>
        </div>
        <div id="tarifs" class="section">
            <h2>Tarifs</h2>
            <p>Découvrez nos tarifs compétitifs :</p>
            <ul>
                <li>Location de court : 20€ / heure</li>
                <li>Cours particulier : 50€ / heure</li>
                <li>Abonnement mensuel : 100€</li>
            </ul>
        </div>
        <div id="reservation" class="section">
            <h2>Réservation en ligne</h2>
            <p>Réservez votre court directement en ligne :</p>
            <form action="reservation.html" method="post">
                <label for="name">Nom :</label><br>
                <input type="text" id="name" name="name"><br>
                <label for="email">Email :</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="date">Date :</label><br>
                <input type="date" id="date" name="date"><br>
                <label for="time">Heure :</label><br>
                <input type="time" id="time" name="time"><br><br>
                <input type="submit" value="Réserver">
            </form>
        </div>
        <div id="photos" class="section photos">
            <h2>Photos</h2>
            <img src="court1.jpg" alt="Court de padel 1">
            <img src="court2.jpg" alt="Court de padel 2">
            <img src="event1.jpg" alt="Événement au club">
        </div>
        <div id="evenements" class="section">
            <h2>Événements</h2>
            <p>Ne manquez pas nos prochains événements :</p>
            <ul>
                <li>Tournoi de printemps - 25 mars</li>
                <li>Journée portes ouvertes - 15 avril</li>
                <li>Stage intensif de padel - 1er mai</li>
            </ul>
        </div>
    </div>
    <div class="footer">
        <p>&copy; 2024 Club de Padel. Tous droits réservés.</p>
    </div>
</body>
</html>
