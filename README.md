<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projet SAE 24</title>
  <link rel="stylesheet" href="style.css">
  <script src="fonction.js"></script>
</head>
<body>
  
<header>
    <div class="navbar">
        <ul>
          <li>
            <a><p1>SAE24</p1></a>
          </li>
          <li class="dropdown">
            <a href="Site.html">Présentation</a>
          </li>
          <li class="dropdown">
            <a href="Projet.html">Projet</a>
            
          </li>
          <li class="dropdown">
            <a href="traitement.html">Traitement</a>
            
          </li>
        </ul>
      </div>
    </header>

    <p class="titre"> I / Objectifs attendus </p>
    <p class="texte">L'objectif de ce projet est de concevoir et de mettre en place une infrastructure réseau pour une petite entreprise, composée de plusieurs services tels que la finance, les ressources humaines et la technique. L'infrastructure comprendra quelques postes clients ayant accès à Internet ainsi qu'un serveur centralisant l'ensemble des services réseaux tels que le partage de fichiers FTP, le protocole DHCP (Dynamic Host Configuration Protocol), et le serveur web.<br><br>

      L'un des objectifs clés sera de garantir le bon fonctionnement du service DHCP. Pour cela, il sera nécessaire de mettre en place un suivi des logs permettant de surveiller l'activité du serveur. L'objectif est de détecter et d'empêcher les attaques visant le service DHCP, notamment les attaques de type "rogue DHCP" (DHCP spoofing) et les attaques de type "DHCP starvation".<br><br>
      
      Empêcher les attaques de type "rogue DHCP" implique de mettre en place des mécanismes de détection pour repérer les serveurs DHCP non autorisés et les attaquants tentant de usurper le rôle de serveur DHCP légitime. Cela peut être réalisé en configurant des règles de filtrage et des mécanismes de surveillance appropriés.<br><br>
      
      Empêcher les attaques de type "DHCP starvation" implique de mettre en place des mécanismes de limitation pour empêcher un attaquant de saturer le serveur DHCP en demandant de manière excessive des adresses IP, ce qui pourrait épuiser les ressources du serveur et entraîner des dysfonctionnements pour les clients légitimes. Des politiques de gestion et des mécanismes de contrôle de la bande passante peuvent être mis en place pour prévenir ce type d'attaque.<br><br>
      
      En résumé, l'objectif de ce projet est de concevoir une infrastructure réseau pour une petite entreprise, en mettant l'accent sur la sécurité du service DHCP. Cela inclut le suivi des logs, la détection et la prévention des attaques de type "rogue DHCP" et "DHCP starvation". L'implémentation de ces mesures de sécurité permettra d'assurer un fonctionnement fiable et sécurisé du réseau de l'entreprise.</p>
   
      <p class="titre"> II / Matèriels </p>
    <p class = "texte">La présentation du matériel pour ce projet est la suivante : <br><br>

      Lieu de travail : Les salles de TP C1bis/C5/C7/B8 sont réservées spécifiquement pour les SAE (Situations d'Apprentissage et d'Évaluation). Le matériel nécessaire au projet restera dans ces salles pendant toute la durée de la SAE, et personne d'autre ne devrait y accéder ou y toucher.<br><br>
      
     Chaque groupe disposera du matériel suivant :<br><br>
      
      4 PC (ordinateurs)<br>
      1 switch (commutateur réseau)<br>
      1 routeur<br>
      1 point d'accès WiFi (PA WiFi)<br>
      1 pare-feu (firewall)<br><br>
      Il est important de noter que le switch et le routeur utilisés seront neufs, garantissant ainsi leur bon fonctionnement.<br><br>
      
      Adresses IP disponibles : Les adresses IP utilisables vont de 172.25.0.100 à 172.25.0.150, avec un masque de sous-réseau en /16. La passerelle par défaut sera configurée avec l'adresse 172.25.255.254. Ces adresses IP peuvent être utilisées pour les PC du groupe, ainsi que pour l'adresse de votre lien "opérateur" (connexion Internet).<br><br>
      
      Clés USB : Des clés USB seront mises à disposition pour l'installation initiale des systèmes d'exploitation tels que Windows Server ou Linux.<br><br>
      
      Matériel supplémentaire : Vous pourrez utiliser les claviers, souris et écrans disponibles dans les salles de TP.<br><br>
      
      Utilisation des prises RJ murales : Les postes actuels sont équipés de prises RJ murales qui seront utilisées pour la connexion Internet. Veuillez noter qu'en B8, vous devez utiliser exclusivement les prises des postes administratifs pour accéder à Internet.<br><br>
      
      Les protocoles autorisés pour accéder à Internet via l'adresse de la passerelle sont les suivants : HTTP, HTTPS, DNS, ICMP (ping) et SSH (Secure Shell).<br><br>
      
      Il est essentiel de respecter ces directives concernant l'organisation matérielle afin de garantir le bon déroulement du projet et d'assurer la sécurité et l'intégrité du réseau pendant la durée de la SAE.</p>
    
  </body>
</html>
    
    


  

  
