# Code---page-web---galerie-Lamuse

<html lang "fr">
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


