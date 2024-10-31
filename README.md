<!DOCTYPE html>

<html lang="fr">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Panneaux Photovoltaïques - Économisez sur vos Factures</title>

    <link rel="stylesheet" href="style.css">

</head>

<body>

    <!-- En-tête -->

    <header>

        <div class="container">

            <h1>Nom de l'Entreprise</h1>

            <p>Contactez-nous : 01 23 45 67 89</p>

        </div>

    </header>



    <!-- Section Héro -->

    <section class="hero">

        <div class="container">

            <h2>Passez à l’énergie solaire et réduisez vos factures jusqu’à 70 % !</h2>

            <p>Profitez de solutions photovoltaïques clé en main, adaptées à vos besoins, pour des économies durables.</p>

            <a href="#contact" class="cta-button">Obtenez votre devis gratuit</a>

        </div>

    </section>



    <!-- Section Avantages -->

    <section class="benefits">

        <div class="container">

            <h3>Pourquoi choisir l'énergie solaire ?</h3>

            <div class="benefit-items">

                <div class="benefit-item">

                    <h4>Réduction de vos factures</h4>

                    <p>Jusqu’à 70 % d’économie d’énergie.</p>

                </div>

                <div class="benefit-item">

                    <h4>Écologique et durable</h4>

                    <p>Une énergie propre, sans émissions de CO2.</p>

                </div>

                <div class="benefit-item">

                    <h4>Valorisation immobilière</h4>

                    <p>Augmentez la valeur de votre maison.</p>

                </div>

            </div>

        </div>

    </section>



    <!-- Section Témoignages -->

    <section class="testimonials">

        <div class="container">

            <h3>Nos clients sont convaincus</h3>

            <p>“Depuis l’installation, ma facture d’électricité a diminué de moitié ! Merci pour ce service clé en main et pour vos conseils.” - Sophie M., Lyon</p>

        </div>

    </section>



    <!-- Section Fonctionnement -->

    <section class="how-it-works">

        <div class="container">

            <h3>Comment ça marche ?</h3>

            <div class="steps">

                <div class="step">Étude de faisabilité gratuite</div>

                <div class="step">Devis personnalisé</div>

                <div class="step">Installation rapide</div>

                <div class="step">Suivi et maintenance</div>

            </div>

        </div>

    </section>



    <!-- Section Formulaire de Contact -->

    <section id="contact" class="contact">

        <div class="container">

            <h3>Recevez votre étude gratuite et personnalisée</h3>

            <form>

                <input type="text" placeholder="Prénom et Nom" required>

                <input type="email" placeholder="Email" required>

                <input type="tel" placeholder="Numéro de téléphone" required>

                <input type="text" placeholder="Adresse" required>

                <button type="submit">Je veux mon devis gratuit</button>

            </form>

        </div>

    </section>



    <!-- Pied de page -->

    <footer>

        <div class="container">

            <p>&copy; 2024 Nom de l'Entreprise | Mentions légales | Politique de confidentialité</p>

        </div>

    </footer>

</body>

</html>



* {

    margin: 0;

    padding: 0;

    box-sizing: border-box;

}



body {

    font-family: Arial, sans-serif;

    line-height: 1.6;

}



.container {

    width: 80%;

    margin: auto;

    max-width: 1200px;

}



header {

    background: #333;

    color: #fff;

    padding: 1em 0;

    text-align: center;

}



.hero {

    background: url('solar-panels.jpg') no-repeat center center/cover;

    color: #fff;

    padding: 5em 0;

    text-align: center;

}



.hero h2 {

    font-size: 2.5em;

    margin-bottom: 0.5em;

}



.cta-button {

    display: inline-block;

    padding: 0.8em 1.5em;

    color: #fff;

    background-color: #ff6600;

    text-decoration: none;

    font-weight: bold;

    border-radius: 5px;

    margin-top: 1em;

}



.benefits {

    padding: 3em 0;

    background-color: #f9f9f9;

}



.benefit-items {

    display: flex;

    gap: 1em;

    justify-content: space-around;

    text-align: center;

}



.benefit-item h4 {

    color: #ff6600;

    margin-bottom: 0.5em;

}



.testimonials {

    background-color: #333;

    color: #fff;

    padding: 2em 0;

    text-align: center;

}



.how-it-works {

    padding: 3em 0;

    text-align: center;

}



.steps {

    display: flex;

    gap: 1em;

    justify-content: space-around;

}



.step {

    background-color: #eaeaea;

    padding: 1.5em;

    border-radius: 5px;

    width: 23%;

}



.contact {

    padding: 3em 0;

    text-align: center;

    background-color: #f9f9f9;

}



form input, form button {

    width: 100%;

    padding: 1em;

    margin-bottom: 1em;

    border-radius: 5px;

    border: 1px solid #ddd;

}



form button {

    background-color: #ff6600;

    color: #fff;

    font-size: 1em;

    border: none;

    cursor: pointer;

}



footer {

    background: #333;

    color: #fff;

    padding: 1em 0;

    text-align: center;

    font-size: 0.9em;

}
