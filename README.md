# Projet-2
Début de l'html du projet numéro deux.
<html lang="fr">

    <head>
        <meta charset="utf-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Reservia</title>
        <link rel="stylesheet" href="style.css" />
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.1/css/all.css" />
    </head>

<body>
    <!-- Header -->
    <header class="header-area w1440p">
        <a class="logo" href="reservia.html"><img src="images/logo/reservia.svg" alt="logo de la société reservia" /></a>
        <nav class="navbar flex">
            <a class="nav-link active" href="#hebergements">Hébergements</a>
            <a class="nav-link" href="#activites">Activités</a>
            <a class="nav-link" href="#">S'inscrire</a>
        </nav>
            
    </header>
    <!--Barre de recherche, et filtre de recherche-->
    <section class="search-area w1440p">
        <h1>Trouvez votre hébergement pour des vacances de rêve</h1>
        <p>En plein centre ville ou en pleine nature</p>
        <form class="search-form flex">
            <div class="search-icon bg--grey">
                <i class="fas fa-map-marker-alt"></i>
            </div>
            <input class="search-input" type="search" name="place" id="place" placeholder="Marseille, France" />
            <button class="search-button bg--blue-primary" type="submit">
                Rechercher
            </button>
        </form>
        <!--les filtres-->
        <section class="filters-area flex">
            <h2>Filtres</h2>
            <div class="filters-choice flex">
                <i class="fas fa-money-bill-wave filters-icon flex bg--blue-secondary blue-primary"></i>
                <h3 class="flex">Économique</h3>
            </div>
            <div class="filters-choice flex">
                <i class="fas fa-child filters-icon flex bg--blue-secondary blue-primary"></i>
                <h3 class="flex">Familial</h3>
            </div>
            <div class="filters-choice flex">
                <i class="fas fa-heart filters-icon flex bg--blue-secondary blue-primary"></i>
                <h3 class="flex">Romantique</h3>
            </div>
            <div class="filters-choice flex">
                <i class="fas fa-dog filters-icon flex bg--blue-secondary blue-primary"></i>
                <h3 class="flex">Animaux autorisés</h3>
            </div>
            <div class="filters-info flex">
                <i class="fas fa-info filters-info-icon blue-primary"></i>
                <p class="filters-info-text">
                    Plus de 500 logements sont disponibles dans cette ville
                </p>
            </div>
        </section>
    </section>
    <!-- Hébergements -->
    <section class="hebergements grid w1440p" id="hebergements">
        <div class="hebergements-area grid">
            <h2>Hébergements à Marseille</h2>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/canne.jpg"
                        alt="Une chambre de l'auberge cannebière, lit superposé avec vu sur cour " />
                    <figcaption class="hebergements-card-img-caption">
                        <h3>Aubèrge la Cannebière</h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>25€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star grey-star"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/port.jpg"
                        alt="Une chambre de l'hôtel du port, avec deux lits " />
                    <figcaption class="hebergements-card-img-caption">
                        <h3> hôtel du port </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>52€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/mouettes.jpg"
                        alt="Une chambre de l'hôtel les mouettes, avec une penderie " />
                    <figcaption class="hebergements-card-img-caption">
                       <h3> Hôtel Les Mouettes </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>76€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star grey-star"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/mer.jpg"
                        alt="Lit auberge de la mer, tableau océan au dessus du lit" />
                    <figcaption class="hebergements-card-img-caption">
                       <h3> Aubèrge de la mer </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>46€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star grey-star"></i>
                    <i class="fas fa-star grey-star"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/panier.jpg"
                        alt="Une chambre de l'auberge cannebière, lit superposé avec vu sur cour " />
                    <figcaption class="hebergements-card-img-caption">
                      <h3> Aubèrge Le Panier </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>23€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star grey-star"></i>
                </div>
            </a>
            <a class="hebergements-card bg--white" href="#">
                <figure class="m0">
                    <img class="hebergements-card-img" src="./images/hebergements/small/amina.jpg"
                        alt="Une chambre de l'auberge cannebière, lit superposé avec vu sur cour " />
                    <figcaption class="hebergements-card-img-caption">
                       <h3> Hôtel chez Amina </h3>
                    </figcaption>
                </figure>
                <p class="hebergements-card-price">
                    Nuit à partir de <strong>96€</strong>
                </p>
                <div class="hebergements-card-description flex">
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                    <i class="fas fa-star blue-primary"></i>
                </div>
            </a>
            <a class="hebergements-link-more" href="#">Afficher plus</a>
        </div>
        <aside class="hebergements-popular grid">
            <div class="hebergements-popular-title flex m0">
                <h2 class="flex">Les plus populaires</h2>
                <i class="fas fa-chart-line hebergements-popular-title-icon"></i>
            </div>
            <a class="hebergements-popular-card bg--white flex">
                <figure class="hebergements-popular-card-img m0">
                    <img src="./images/hebergements/small/soleil.jpg"
                        alt="une chambre de l'hotel du soleil, avec un style arabesque" />
                </figure>
                <div class="hebergements-popular-card-img-caption">
                    Hôtel Le soleil du matin
                    <p class="hebergements-popular-car-price">
                        Nuit à partir de <strong>128€</strong>
                    </p>
                    <div class="hebergements-popular-card-description flex">
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                    </div>
                </div>
            </a>
            <a class="hebergements-popular-card bg--white flex">
                <figure class="hebergements-popular-card-img m0">
                    <img src="./images/hebergements/small/eau.jpg"
                        alt="une chambre de l'hotel du soleil, avec un style arabesque" />
                </figure>
                <div class="hebergements-popular-card-img-caption">
                    Au coeur de l'eau Chambres d'hôtes
                    <p class="hebergements-popular-car-price">
                        Nuit à partir de <strong>71€</strong>
                    </p>
                    <div class="hebergements-popular-card-description flex">
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star grey-star"></i>
                    </div>
                </div>
            </a>
            <a class="hebergements-popular-card bg--white flex">
                <figure class="hebergements-popular-card-img m0">
                    <img src="./images/hebergements/small/bleu.jpg"
                        alt="une chambre de l'hotel du soleil, avec un style arabesque" />
                </figure>
                <div class="hebergements-popular-card-img-caption">
                    Hôtel Tout bleu et Blanc
                    <p class="hebergements-popular-car-price">
                        Nuit à partir de <strong>68€</strong>
                    </p>
                    <div class="hebergements-popular-card-description flex">
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star blue-primary"></i>
                        <i class="fas fa-star grey-star"></i>
                    </div>
                </div>
            </a>
        </aside>
    </section>
    <!-- Activité -->
    <section class="activites-area w1440p" id="activites">
        <h1>Activités à Marseille</h1>
        <a class="activites-area-card activites-area-card1" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/medium/vieux.jpg"
                    alt="Vu du vieux port et ses bateaux à quai, avec la ville en arrière-plan" />
            </figure>
            <h3 class="activites-card-img-caption">Vieux Port</h3>
        </a>
        <a class="activites-area-card activites-area-card2" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/small/pormegues.jpg"
                    alt="Vue du fort entre deux rochers" />
            </figure>
            <h3 class="activites-card-img-caption">Fort de Pomègues</h3>
        </a>
        <a class="activites-area-card activites-area-card3" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/small/frioul.jpg"
                    alt="Vue lointaine de l'île de frioul depuis un point d'observation" />
            </figure>
            <h3 class="activites-card-img-caption">Île du Frioul</h3>
        </a>
        <a class="activites-area-card activites-area-card4" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img"
                    src="./images/activites/medium/calanques.jpg"
                    alt="Vue en plongée sur le parc national de Calanques" />
            </figure>
            <h3 class="activites-card-img-caption">Parc National de Calanques</h3>
        </a>
        <a class="activites-area-card activites-area-card5" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/small/garde.jpg"
                    alt="Vue lointaine de Notre-Dame-de-la-Garde et ses alentours" />
            </figure>
            <h3 class="activites-card-img-caption">Notre-Dame-de-la-Garde</h3>
        </a>
        <a class="activites-area-card activites-area-card6" href="#">
            <figure class="activites-area-card-figure m0">
                <img class="activites-area-card-figure-img" src="./images/activites/small/Long.jpg"
                    alt="Vue de la facade extérieur du parc Longchamp" />
            </figure>
            <h3 class="activites-card-img-caption">Parc Longchamp</h3>
        </a>
    </section>
    <!-- Footer -->
    <footer class="bg--grey">
        <div class="footer-area grid">
            <nav class="flex footer-nav">
                <h3>À propos</h3>
                <a href="#">Fonctionnement du site</a>
                <a href="#">Conditions générales de vente</a>
                <a href="#">Données et confidentialités</a>
            </nav>
            <nav class="flex footer-nav">
                <h3>Nos hébergements</h3>
                <a href="#">Charte de qualité</a>
                <a href="#">Soumettre votre hôtel</a>
            </nav>
            <nav class="flex footer-nav">
                <h3>Assistance</h3>
                <a href="#">Centre d'aide</a>
                <a href="#">Nous contacter</a>
            </nav>
        </div>
    </footer>
</body>

</html>

@import url("https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

html {
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  }
  
body {
    margin: 0;
    padding: 0;
    height: 3500px;
  }
  
* {
  box-sizing: border-box;
}
  
h1,
h2,
h3,
h4 {
  font-weight: 700;
}
 
h1 {
  font-size: 1.375rem;
}

h2 {
  font-size: 1.25rem;
}

h3 {
  font-size: 1.125rem;
}

.w1440p {
  max-width: 77.5rem;
  width: 100%;
  margin-right: auto;
  margin-left: auto;
}

.flex {
  display: flex;
}

.grid {
  display: grid;
}

.m0 {
  margin: 0;
}

ul {
  list-style: none;
}

/* Couleurs charte  */
.blue-primary {
  color: #0065fc;
}

.blue-secondary {
  color: #DEEBFF;
}

.grey {
  color: #f2f2f2;
}

.grey-star {
  color: #d9d9d9;
}

/* background charte  */
.bg--blue-primary {
  background-color: #0065fc;
}

.bg--blue-secondary {
  background-color: #deebff;
}

.bg--grey {
  background-color: #f2f2f2;
}

.bg--white {
  background-color: white;
}
/* Header */
.header-area {
  display: grid;
  align-items: center;
  margin: auto;
  grid-template-columns: auto 1fr auto auto;
  grid-template-areas: "logo . navbar signup";
}

.logo {
  padding: 0;
  grid-area: logo;
}

.navbar {
  align-items: center;
  grid-area: navbar;
}

.nav-link {
  border-top: 0.125rem solid transparent;
  padding: 2rem;
  text-decoration: none;
  text-align: center;
  font-weight: 400;
  color: black;
}

.signup {
  border-top: 0.125rem solid transparent;
  padding: 2rem;
  text-decoration: none;
  align-items: center;
  font-weight: 600;
  grid-area: signup;
}

.active,
.nav-link:hover,
.signup:hover {
  color: #0065fc;
  border-top: 0.125rem solid #0065fc;
}

/* Recherche & Filtres*/
/* Recherche */
.search-area h1,
.search-area p {
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
}

.search-form {
  width: 100%;
  align-items: center;
  padding: 0.75rem 0;
}

.search-icon,
.search-input,
.search-button {
  height: 3.125rem;
  display: flex;
  align-items: center;
}

.search-input,
.search-button {
  padding: 1.25rem;
  border-width: 0.0625rem 0;
  border-style: solid none;
}

.search-icon {
  font-size: 1.25rem;
  padding: 1.25rem;
  border-radius: 1rem 0 0 1rem;
}

.search-input {
  width: 100%;
  max-width: 20%;
  border-color: #f2f2f2;
}

#place::placeholder {
  font-family: "Raleway", sans-serif;
  font-size: 1.125rem;
  font-weight: 700;
  color: black;
  opacity: 1;
}

.search-button {
  color: white;
  font-family: "Raleway", sans-serif;
  font-size: 1rem;
  font-weight: 700;
  border-radius: 0 1rem 1rem 0;
  border-color: #0065fc;
  cursor: pointer;
}

/* Filtres*/

.filters-area {
  margin-top: 0.75rem;
  flex-wrap: wrap;
  align-items: center;
}

.filters-area h2 {
  align-items: center;
  margin-right: 1.25rem;
  margin-top: 0;
}

.filters-choice {
  align-items: center;
  margin-right: 1.25rem;
  margin-bottom: 1rem;
  border: 0.125rem solid #f2f2f2;
  border-radius: 2rem;
  cursor: pointer;
}

.filters-choice:hover {
  background: rgba(0, 101, 252, .2);
}

.filters-choice i,
.filters-info i {
  display: flex;
  align-items: center;
  justify-content: center;
}

.filters-icon {
  height: 3rem;
  width: 3rem;
  border-radius: 100%;
  margin: -0.125rem;
  font-size: 1.25rem;
}

.filters-area h3 {
  margin: 0 1rem;
}

.filters-info,
.filters-info-text {
  align-items: center;
}

.filters-info-icon {
  height: 2rem;
  width: 2rem;
  border: 0.125rem solid #f2f2f2;
  border-radius: 100%;
  align-items: center;
  justify-content: center;
  margin-right: 1rem;
}

/* Hébergements */
.hebergements {
  margin-top: 1.5rem;
  column-gap: 2rem;
  grid-template-columns: 6fr 3fr;
  grid-template-areas: "hebergements-area hebergements-popular";
}

.hebergements-area,
.hebergements-popular {
  background-color: #f2f2f2;
  border-radius: 1.5rem;
  padding: 1.5rem;
}

.hebergements-area {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  column-gap: 1.5rem;
  row-gap: 1.5rem;
  grid-area: hebergements-area;
}

.hebergements-area a {
  text-decoration: none;
  color: black;
}

.hebergements-area h2,
.hebergements-popular h2 {
  grid-column: 1/-1;
  margin: 0;
}

.hebergements-card {
  padding: 0.375rem;
  border-radius: 1.25rem;
  box-shadow: 0 0 1rem rgba(0, 0, 0, 0.2);
  height: 100%;
  overflow: hidden;
  cursor: pointer;
}

.hebergements-card-img {
  height: 7rem;
  max-height: 100%;
  object-fit: cover;
  width: 100%;
  max-width: 100%;
  border-radius: 1rem 1rem 0 0;
}

.hebergements-card-img-caption h3 {
  font-size: 1rem;
  margin: 0.15rem 0.15rem 0 0.75rem;
}

.hebergements-card-description {
  padding-left: 0;
  margin: 0.25rem 0.75rem;
}

.hebergements-card-description li {
  margin-left: 0;
}

.hebergements-card-price {
  margin: 0.25rem 0.75rem;
}

.hebergements-link-more {
  font-size: 1.25rem;
  font-weight: 700;
}
/* les plus populaires*/
.hebergements-popular-title {
  display: flex;
  justify-content: space-between;
}

.hebergements-popular {
  row-gap: 2rem;
  align-items: start;
  grid-template-rows: auto repeat(3, 1fr);
  grid-area: hebergements-popular;
}

.hebergements-popular-title-icon {
  font-size: 1.6rem;
}

.hebergements-popular-card {
  padding: 0.375rem;
  border-radius: 1.5rem;
  box-shadow: 0 0 1rem rgba(0, 0, 0, 0.2);
  align-items: stretch;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
}

.hebergements-popular-card-img {
  position: relative;
  min-height: 100%;
  width: 33%;
  min-width: 33%;
  max-width: 33%;
}

.hebergements-popular-card-img img {
  border-radius: 1.5rem 0 0 1.5rem;
  position: absolute;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.hebergements-popular-card-img-caption {
  flex-direction: column;
}

.hebergements-popular-card-img-caption h3,
.hebergements-popular-card-img-caption p {
  margin: 0.25rem 1rem;
}

.hebergements-popular-card-description {
  padding-left: 1rem;
  margin-top: 1.5rem;
  margin-bottom: 0.25rem;
}

/* Activités */
.activites-area  {
  display: grid;
  column-gap: 2rem;
  margin: 2rem auto;
}

.activites-area h1 {
  grid-column: 1/-1;
}

.activites-area-card {
  display: flex;
  border-radius: 1rem;
  flex-direction: column;
  box-shadow: 0 0 1.25rem rgba(0, 0, 0, 0.2);
  overflow: hidden;
  text-decoration: none;
  color: black;
}

.activites-area-card-figure {
  position: relative;
  flex: 1;
}

.activites-area-card-figure-img {
  position: absolute;
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.activites-card-img-caption {
  margin: 1.2rem;
}
