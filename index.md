<!DOCTYPE html> 
<html dir="ltr" lang="fr" xml:lang="fr">
   <head>
      <meta charset="utf-8">
      <title>Jardin de Balata</title>
      <link rel="stylesheet" type="text/css" href="assets/css/style.css" />
      <meta name="viewport" content="width=device-width" />
   </head>
   <body>
      <!-- Start header -->
      <header class="header">
         <!-- Start nav -->
         <div class="header-menu">
            <a href="index.html" title="Retour à l'accueil" class="header-logo">
            <img src="assets/images/logo_Balata-blanc.png" alt="Jardin de Balata" class="logo-image"/>
            </a>
            <nav class="header-nav">
               <ul class="nav-list">
                  <li class="nav-item">
                     <a href="#" title="A découvrir" class="nav-link">A découvrir</a>
                  </li>
                  <li class="nav-item">
                     <a href="#" title="Infos pratiques" class="nav-link">Infos pratiques</a>
                  </li>
                  <li class="nav-item">
                     <a href="#" title="Nos boutiques" class="nav-link">Nos boutiques</a>
                  </li>
                  <li class="nav-item">
                     <a href="#" title="Restaurations" class="nav-link">Restaurations</a>
                  </li>
                  <li class="nav-item">
                     <a href="#" title="Contact" class="nav-link">Contact</a>
                  </li>
               </ul>
            </nav>
         </div>
         <!-- Eof .nav --> 
      </header>
      <!-- Eof .header --> 
      <!-- Start main -->
      <main>
         <!-- Start section -->
         <section class="presentation">
            <h2>
               Connu dans le monde entier !<br>
               Entrez dans le Jardin d'un artiste...
            </h2>
            <p>
               <b>La visite incontournable en Martinique</b><br>
               Tous les paradis sont des jardins et ce n’est pas un hasard si, au cours de la visite du Jardin de Balata, la magie des lieux procure aux visiteurs des sentiments étonnants.<br>
               C’est en 1982 que <b>Jean-Philippe Thoze</b>, horticulteur, paysagiste et artiste dans l'âme, revient sur les traces de son enfance dans la maison créole de ses grands-parents. De là, naîtra une passion pour la botanique qui va le mener aux quatre coins du monde.<br>
               Le jardin, organisé autour de l’<b>habitation familiale</b> à l’<b>architecture créole typique</b>, est le fruit d’une alchimie parfaite entre un retour aux sources et un artiste atypique.
            </p>
         </section>
         <!-- Eof section -->
         <!-- Start section -->
         <section class="carousel">
            <div>
               <div class="carousel-container">
                  <div class="mySlides">
                     <img alt="Paysage" src="assets/images/paysage(1).jpg">
                  </div>
                  <div class="mySlides">
                     <img alt="Paysage" src="assets/images/paysage(2).jpg">
                  </div>
                  <div class="mySlides">
                     <img alt="Paysage" src="assets/images/paysage(4).jpg">
                  </div>
                  <div class="mySlides">
                     <img alt="Paysage" src="assets/images/paysage(5).jpg">
                  </div>
                  <div class="mySlides">
                     <img alt="Paysage" src="assets/images/paysage(6).jpg">
                  </div>
                  <a class="prev" onclick="plusSlides(-1)">❮</a>
                  <a class="next" onclick="plusSlides(1)">❯</a>
                  <div class="row">
                     <div class="column">
                        <img alt="Paysage" class="demo cursor" src="assets/images/paysage(1).jpg" onclick="currentSlide(1)">
                     </div>
                     <div class="column">
                        <img alt="Paysage" class="demo cursor" src="assets/images/paysage(2).jpg" onclick="currentSlide(2)">
                     </div>
                     <div class="column">
                        <img alt="Paysage" class="demo cursor" src="assets/images/paysage(4).jpg" onclick="currentSlide(3)">
                     </div>
                     <div class="column">
                        <img alt="Paysage" class="demo cursor" src="assets/images/paysage(5).jpg" onclick="currentSlide(4)">
                     </div>
                     <div class="column">
                        <img alt="Paysage" class="demo cursor" src="assets/images/paysage(6).jpg" onclick="currentSlide(5)">
                     </div>
                  </div>
               </div>
            </div>
         </section>
         <!-- Eof section -->
         <!-- Start section -->
         <section class="acces">
            <div class="acces-title">
               <h2>Venir au jardin</h2>
            </div>
            <div class="acces-section acces-section1">
               <p>Le Jardin de Balata se trouve à seulement quelques minutes du centre ville de Fort-de-France, sur la route incontournable de la Trace qui vous emmène aussi à Saint Pierre et au Carbet, deux lieux historiques de la Martinique.</p>
               <h3>Par la rocade :</h3>
               <p>
                  <strong>En venant de Fort de France</strong> : Prendre la sortie Morne Rouge par la route de la trace.<br><br>
                  <strong>En venant de St Pierre</strong> : Prendre la sortie en bas de la descente, direction Morne Rouge, Route de la trace.
               </p>
               <h3>Par le centre ville de Fort de France :</h3>
               <p><strong>Au niveau du Parc Floral</strong> : Suivre le panneau "Jardin de Balata", garder la route principale pendant environ dix minutes.</p>
            </div>
            <div class="acces-section acces-section2">
               <h3>Accès en bus :</h3>
               <p>
                  Prendre la ligne L25 depuis Fort de France : Aliker - Jardin de Balata<br>
                  L'arrêt se trouve en face de l'entrée du Jardin. La fréquence est environ toutes les 30 minutes sauf le Dimanche et les jours fériés.
               </p>
               <h3>Accès en taxi :</h3>
               <p>La ville de Fort de France possède plusieurs compagnies de Taxi. Il est possible de faire appel à eux 24h/24h.<br>
                  <a href="https://www.fortdefrance.fr/fort-de-france/se-deplacer/#taxis-61696d63ac960" title="Liste des compagnies de Taxi " class="acces-link">Voir la liste des compagnies de Taxi</a> (Site Internet de la Ville de Fort de France)
               </p>
            </div>
            <div class="acces-map">
               <iframe class="map" src="https://maps.google.com/maps?q=jardin%20de%20balata,%20Route%20de%20Balata,%20Fort-de-France%2097234,%20Martinique&t=&z=13&ie=UTF8&iwloc=&output=embed"></iframe>
            </div>
         </section>
         <!-- Eof section -->
         <!-- Start section -->
         <section class="tarif">
            <div>
               <div class="tarif-container">
                  <div class="tarif-section tarif-section1">
                     <h2>Tarif</h2>
                     <ul>
                        <li>Moins de 3 ans : <strong>Gratuit</strong></li>
                        <li>Enfant de 3 à 12 ans : <strong>8,00 €</strong></li>
                        <li>Adulte : <strong>14,00 €</strong></li>
                        <li>Abonnement Enfant : <strong>10,00€</strong></li>
                        <li>Abonnement Adulte : <strong>18,00€</strong></li>
                     </ul>
                     <h3>Les moyens de paiement acceptés :</h3>
                     <ul>
                        <li>Espèces</li>
                        <li>Chèques bancaires</li>
                        <li>Chèques postaux</li>
                        <li>Chèques vacances</li>
                     </ul>
                  </div>
                  <div class="tarif-section tarif-section2">
                     <h2>Horaire</h2>
                     <p>
                        Ouvert du Lundi au Vendredi de <strong>9h à 17h</strong>					
                     </p>
                     <h3>Remarque :</h3>
                     <ul>
                        <li>Le château est ouvert toute l'année à l'exception du <strong>1er Janvier</strong> et du <strong>25 Décembre</strong>.</li>
                        <li>Les dernières admissions au Jardin de Balata se font à <strong>16h</strong>.</li>
                        <li>Le patin à roulettes, la planche à roulettes et les moyens de déplacement similaires sont interdits dans le jardin</li>
                        <li>Les chiens et autres animaux familiers sont interdits dans l'enceinte du Jardin à l'exception des chiens guides d'aveugles.</li>
                     </ul>
                  </div>
               </div>
            </div>
         </section>
         <!-- Eof section -->
         <!-- Start section -->
         <section class="sponsor">
            <img src="assets/images/collectivite.png" alt="Collectivité Territoriale de Martinique" class="sponsor-images"/>
            <img src="assets/images/union-europeenne.png" alt="Union Européenne" class="sponsor-images"/>
            <img src="assets/images/l-europe-s-engage.png" alt="L'Europe s'engage en Martinique" class="sponsor-images"/>
            <img src="assets/images/travellers-choice2020.png" alt="Traveller's Choice 2020" class="sponsor-images"/>
            <img src="assets/images/QualiteTourisme.jpg" alt="Qualité Tourisme" class="sponsor-images"/>
         </section>
         <!-- Eof section -->
      </main>
      <!-- Eof main -->
      <!-- Start footer -->
      <footer class="footer">
         <div>
            <div class="footer-content">
               <div class="footer-column">
                  <h2 class="footer-column-title">Jardin de Balata</h2>
                  <address class="footer-address">
                     Route de Balata, Fort-de-France 97234, Martinique
                  </address>
                  <a class="footer-phone" href="tel:+596596644873">+596 596 64 48 73</a>
               </div>
               <div class="footer-column">
                  <h2 class="footer-column-title">Aide</h2>
                  <ul class="footer-column-menu">
                     <li class="footer-item">
                        <a class="footer-link" href="#">FAQ</a>
                     </li>
                     <li class="footer-item">
                        <a class="footer-link" href="#">Espace Presse</a>
                     </li>
                     <li class="footer-item">
                        <a class="footer-link" href="#">Mentions Légales</a>
                     </li>
                  </ul>
               </div>
               <div class="footer-column">
                  <h2 class="footer-column-title">Liens rapides</h2>
                  <ul class="footer-column-menu">
                     <li class="footer-item">
                        <a class="footer-link" href="#">A découvrir</a>
                     </li>
                     <li class="footer-item">
                        <a class="footer-link" href="#">Infos pratiques</a>
                     </li>
                     <li class="footer-item">
                        <a class="footer-link" href="#">Nos boutiques</a>
                     </li>
                     <li class="footer-item">
                        <a class="footer-link" href="#">Restaurations</a>
                     </li>
                     <li class="footer-item">
                        <a class="footer-link" href="#">Contact</a>
                     </li>
                  </ul>
               </div>
               <div class="footer-column">
                  <ul class="footer-social">
                     <li class="social-item">
                        <a class="social-link social-link-facebook" href="https://www.facebook.com/jardindebalata" target="_blank"></a>
                     </li>
                     <li class="social-item">
                        <a class="social-link social-link-instagram" href="https://www.instagram.com/jardindebalata/?hl=fr" target="_blank"></a>
                     </li>
                     <li class="social-item">
                        <a class="social-link social-link-tripadvisor" href="https://www.tripadvisor.fr/Attraction_Review-g147328-d147828-Reviews-Jardin_de_Balata-Fort_de_France_Arrondissement_of_Fort_de_France_Martinique.html" target="_blank"></a>
                     </li>
                  </ul>
               </div>
            </div>
         </div>
      </footer>
      <!-- Eof footer -->
      <!-- Start Bouton Top -->
      <a href="#top" class="bouton-top"></a>
      <!-- EOf Footer -->
      <script>
         var slideIndex = 1;
         showSlides(slideIndex);
         
         function plusSlides(n) {
           showSlides(slideIndex += n);
         }
         
         function currentSlide(n) {
           showSlides(slideIndex = n);
         }
         
         function showSlides(n) {
           var i;
           var slides = document.getElementsByClassName("mySlides");
           var dots = document.getElementsByClassName("demo");
           var captionText = document.getElementById("caption");
           if (n > slides.length) {slideIndex = 1}
           if (n < 1) {slideIndex = slides.length}
           for (i = 0; i < slides.length; i++) {
         	  slides[i].style.display = "none";
           }
           for (i = 0; i < dots.length; i++) {
         	  dots[i].className = dots[i].className.replace(" active", "");
           }
           slides[slideIndex-1].style.display = "block";
           dots[slideIndex-1].className += " active";
           captionText.innerHTML = dots[slideIndex-1].alt;
         }
      </script>
   </body>
</html>
