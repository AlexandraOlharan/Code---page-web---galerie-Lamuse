<!doctype html>
<html lang ="fr">

<header>
    <nav>
        <ul>
          <li><a href="Contacts">Contacts</a></li>  
          <li><a href="Informations">Informations</a></li>
        </ul>
    </nav>
    <nav>
        <ul>
            <li><a href="Présentations">Présentation</a></li>
            <li><a href="Artistes">Artistes</a></li>
            <li><a href="Oeuvres">Oeuvres</a></li>
        </ul>
    </nav>
</header>

<body>
    <h1>Galerie Lamuse</h1>
    <img src="Images" alt="Galerie.jpg">    

    <section class="presentation">
    <h2>Présentation</h2>
    <p>
        <img src="Images/portrait.png" alt="portrait" style="float:right;width:180px;height:210px;">
        Gilles François a fondé la galerie Lamuse en 1975. Né dans une 
        famille d’artistes, il a très tôt développé un goût pour la matière, 
        la lumière et la forme. Après des études aux Beaux-Arts, et à l’occasion 
        de nombreux voyages, il aiguise sa vision artistique et sa créativité. Il 
        décide de créer un espace qui lui ressemble : un lieu de découverte, 
        d’échanges et de rencontres ou la créativité se vit au présent. 
        Toujours en quête d’innovation, il collabore avec des artistes aux 
        créations variées, mélant photographie, peinture, et arts numérique. </p>
   
     <p>La galerie Laamuse célèbre aujourd’hui l’audace de la femme. Elle offre 
        une scène vibrante aux artistes émergentes et confirmées, dans un mélange 
        de créativité, d’émotions et de réflexions.</p>
     </section>
    
    <section class="artistes">
    <h2>Nos artistes</h2>

    <div class="grille">

    <div class="carte1">
             <img src="Images/dégradé.jpg" alt="dégradé" style="width:180px;height:180px;">
             <p>Eva Lautier</p>
    </div>
    <div class="carte2">
             <img src="Images/bain.jpg" alt="bain" style="width:180px;height:180px;">
             <p>Anne-Sophie Paris</p>
    </div>
    <div class="carte3">
             <img src="images/tag.jpg" alt="tag" style="width: 180px;height: 180px;">
             <p>Jeanne Fostner</p>
    </div>
    <div class="carte4">
             <img src="Images/paysage.jpg" alt="paysage" style="width: 180px;height: 180px;">
             <p>Josiane Lucas</p>
    </div>
    <div class="carte5">
             <img src="Images/main.jpg" alt="main" style="width: 180px;height: 180px;">
             <p>France Chevalier</p>
    </div>
    <div class="carte6">
             <img src="Images/coulis.jpg" alt="coulis" style="width: 180px;height: 180px;">
             <p>Marie Rose</p>
    </div>
   
    </div class="grille">
    </section> 

    <section class="oeuvres">
        <h2>Oeuvres</h2>
        <div class="grille">
            <img src="Images/temple.png" alt="temple">
            <img src="Images/danseuse.png" alt="danseuse">
            <img src="Images/arbre.png" alt="arbre">
            <img src="Images/table.jpg" alt="table">
            <img src="Images/femme.jpg" alt="femme">
            <img src="Images/vague.png" alt="vague">
            <img src="Images/tapisserie.png" alt="tapisserie">
        </div>
    </section>

    <section class="informations">
        <h2>Nous contacter</h2>
        <p>06 76 54 30 00</p>
        <p>lamuse.galeriedart@gmail.com</p>
        <h2>Où nous trouver ?</h2>
        <p>51 rue des fleurs, Nice, 06000</p>
        <p>9h - 12h et 14h - 17h</p>
    </section>

    <img src="Images" alt="tableau">

    <section class="news-letter">
        <h2>Abonnez-vous gratuitement à notre News-Letter</h2>
        <label for="pénom">Prénom:</label><br>
        <input type="text" id="Prénom" name="Prénom"><br>
        <label for="nom">Nom:</label><br>
        <input type="text" id="Nom" name="Nom"><br>
        <label for="email">E-mail:</label><br>
        <input type="text" id="e-mail" name="E-mail"><br>
        <button type="button">Soumettre</button>
    </section>
</body>


<style type="text/css>
    <!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lamuse Galerie</title>

    <style>
        body {
            margin: 0;
            font-family: "Times New Roman", serif;
            background-color: #f7f7f7;
        }

        /* ----------- Style de l'index ----------- */
        nav {
            width: 100%;
            background-color: white;
            padding: 15px 0;
            border-bottom: 3px solid #b47bd2;
            display: flex;
            justify-content: center;
            gap: 50px;
            font-size: 18px;
        }

        nav a {
            text-decoration: none;
            color: black;
        }

        /* ----------- Style titre ----------- */
        h1 {
            text-align: center;
            font-size: 48px;
            margin-top: 30px;
            margin-bottom: 20px;
        }

        /* ----------- Style image principale ----------- */
        .hero img {
            width: 80%;
            display: block;
            margin: 0 auto;
            border-radius: 5px;
        }

        /* ----------- Style de la premiere section ----------- */
        .presentation {
            width: 85%;
            margin: 40px auto;
        }

        .presentation h2 {
            font-size: 32px;
            margin-bottom: 20px;
        }

        .presentation-content {
            display: flex;
            gap: 20px;
        }

        .presentation img {
            width: 220px;
            border-radius: 5px;
        }

        .presentation p {
            font-size: 17px;
            line-height: 1.5;
            text-align: justify;
        }
    </style>
</head>

<body>

    <!-- ----------- Index ----------- -->
    <nav>
        <a href="#contacts">Contacts</a>
        <a href="#informations">Informations</a>
        <a href="#presentation">Présentation</a>
        <a href="#artistes">Artistes</a>
        <a href="#oeuvres">Oeuvres</a>
    </nav>

    <!-- ----------- Titre ----------- -->
    <h1>Lamuse Galerie</h1>

    <!-- ----------- Main Image ----------- -->
    <div class="hero">
        <img src="IMAGE1.png" alt="Galerie">
    </div>

    <!-- ----------- Presentation ----------- -->
    <!-- Assurez que chacune de vos sections sont encadre par cette ligne en bas -->

    <section id="presentation" class="presentation">
        <h2>Présentation</h2>

        <div class="presentation-content">

            <img src="FONDATEUR.png" alt="Fondateur">
            <!-- Remplacez FONDATEUR.jpg par l’image du fondateur -->

            <p>
                Gilles François a fondé la galerie Lamuse en 1975. Né dans une famille d’artistes, 
                il a très tôt développé un goût pour la matière, la lumière et la forme. Après des 
                études aux Beaux-Arts, et à l’occasion de nombreux voyages, il aiguise sa vision 
                artistique et sa créativité. Il décide de créer un espace qui lui ressemble : un lieu 
                de découverte, d’échanges et de rencontres où la créativité se vit au présent. Toujours 
                en quête d’innovation, il collabore avec des artistes aux créations variées, mêlant 
                photographie, peinture, et arts numérique. <br><br>
                La galerie Laamuse célèbre aujourd’hui l’audace de la femme. Elle offre une scène 
                vibrante aux artistes émergentes et confirmées, dans un mélange de créativité, 
                d’émotions et de réflexions.
            </p>

        </div>
    </section>
    <section class="news-letter">
    <div class="news-container">
        <img class="news-bg" src="tableau pam.png" alt="Newsletter Background">
        <div class="news-content">
            <h2>Abonnez-vous gratuitement à notre News Letter</h2>
            <form id="newsletterForm" onsubmit="return validateForm()">
                <div class="form-row">
                    <div class="form-group">
                        <label for="prenom">Prénom :</label>
                        <input type="text" id="prenom" name="prenom" placeholder="Prénom">
                    </div>
                    <div class="form-group">
                        <label for="nom">Nom :</label>
                        <input type="text" id="nom" name="nom" placeholder="Nom">
                    </div>
                </div>

                <label for="email">Email :</label>
                <input type="email" id="email" name="email" placeholder="Email">

                <button type="submit">Soumettre</button>
            </form>
        </div>
    </div>
</section>
<script>
function validateForm() {
    const prenom = document.getElementById('prenom').value.trim();
    const nom = document.getElementById('nom').value.trim();
    const email = document.getElementById('email').value.trim();

    if(prenom === '' || nom === '' || email === '') {
        alert('Veuillez remplir tous les champs.');
        return false;
    }

    const emailPattern = /^[^ ]+@[^ ]+\.[a-z]{2,3}$/;
    if(!emailPattern.test(email)) {
        alert('Veuillez entrer une adresse e-mail valide.');
        return false;
    }

    alert('Merci pour votre inscription !');
    return true;
}
</script>


</body>
</html>



