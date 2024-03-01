<h2>Activité Pratique 2 : Mise en oeuvre d'une architecture micro-services</h2><br>
<h2>Objectifs :</h2>
<p>Créer une application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client.</p><br><br>

<h3>Question 1</h3>
<p>Créer le micro-service customer-service qui permet de gérer les client</p>
<img src="Captures/capture1.jpg" alt=""><br>
<p> - Visualiser la base de données customers-db</p>
<img src="Captures/capture3.jpg" alt=""><br>
<p> - Consultation du web service grace a spring data rest: avec le numéro de port 8081</p>
<img src="Captures/capture2.jpg" alt=""><br><br>

<h3>Question 2</h3>
<p>Créer le micro-service inventory-service qui permet de gérer les produits</p>
<img src="Captures/capture4.jpg" alt=""><br>
<p> - Visualiser la base de données products-db</p>
<img src="Captures/capture5.jpg" alt=""><br>
<p> - Consultation du web service grace a spring data rest: avec le numéro de port 8082</p>
<img src="Captures/capture6.jpg" alt=""><br><br>

<h3>Question 3</h3>
<p>Créer la Gateway Spring cloud Gateway</p>
<img src="Captures/capture11.jpg" alt=""><br><br>

<h3>Question 4</h3>
<p> Configuration statique du système de routage</p>
<p> - Via le fichier application.yml</p>
<img src="Captures/capture10.jpg" alt=""><br>
<p> - Directement depuis le fichier d'exécution "GatewayApplication"</p>
<img src="Captures/capture7.jpg" alt=""><br>
<p> - Test : affichage de la liste des customers depuis la gateway avec le numéro de port 8888</p>
<img src="Captures/capture8.jpg" alt=""><br>
<p> - Test : affichage de la liste des products depuis la gateway avec le numéro de port 8888</p>
<img src="Captures/capture9.jpg" alt=""><br><br>

<h3>Question 5</h3>
<p>Créer l'annuaire Eureka Discrovery Service</p>
<img src="Captures/capture12.jpg" alt=""><br>
<p>Liste des web services crées via le port : 8761</p>
<img src="Captures/capture13.jpg" alt=""><br><br>

<h3>Question 6</h3>
<p> Faire une configuration dynamique des routes de la gateway</p>
<img src="Captures/capture14.jpg" alt=""><br>
<p>Consulter le web service grace a son nom : CUSTOMER-SERVICE</p>
<img src="Captures/capture15.jpg" alt=""><br>
<p>Consulter le web service grace a son nom : INVENTORY-SERVICE</p>
<img src="Captures/capture16.jpg" alt=""><br><br>