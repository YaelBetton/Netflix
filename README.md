# Netflix

# Netflix Clone - Projet d'Études (BUT Informatique)
## À propos de l'auteur
Je suis étudiant en deuxième année de BUT Informatique. Ce projet a été réalisé pour consolider mes connaissances en développement web moderne, en appliquant les concepts d'interactivité et d'architecture logicielle vus en cours.

## Présentation du Projet
Ce projet est une application web (ou "web app") dynamique simulant l'interface de Netflix. Contrairement à un simple site vitrine, il s'agit d'un site web dynamique qui permet d'exécuter des actions et d'interagir avec un catalogue de données.

## Concepts Théoriques Appliqués
Le développement de ce clone repose sur les notions abordées dans les modules R3.01B (JavaScript) et R4.10 (Complément Web).


## Architecture de l'Application (Module R4.10)

Modèle Client-Serveur : L'application utilise une interaction entre le client (le navigateur) et un serveur web distant pour récupérer les ressources.
Client-Side Rendering (CSR) : Le projet utilise le rendu côté client. Le navigateur télécharge le JavaScript qui génère ensuite le contenu, rendant la page consultable et interactive quasi instantanément après le chargement initial.
Interface Responsive : L'ergonomie a été pensée pour être Responsive, s'adaptant à différents formats d'écrans pour éviter une mauvaise expérience utilisateur.


## Logique JavaScript (Module R3.01B)

Manipulation du DOM : Accès et modification des éléments HTML via des sélecteurs comme querySelector() et getElementById().
Programmation Asynchrone (AJAX) : Utilisation de l'API fetch() pour effectuer des appels réseau asynchrones vers une API de films.
Traitement des Données JSON : Les données reçues sont désérialisées depuis le format JSON pour être transformées en objets JavaScript exploitables.


1. La Couche Front-end (Présentation / IHM)
C'est la partie visible de votre projet, celle qui permet à l'utilisateur de communiquer avec le système.


HTML (HyperText Markup Language) : Utilisé pour générer et placer les informations, comme les affiches de films et les menus de navigation.


CSS (Cascading Style Sheets) : Sert à matérialiser le design "Netflix" (couleurs noires et rouges, disposition des vignettes, typographie).


JavaScript : C'est le moteur de l'interactivité. Il gère l'affichage dynamique du catalogue, l'ouverture des fenêtres modales et les appels asynchrones (AJAX/Fetch) vers le serveur.


Frameworks possibles : Vous pourriez utiliser des outils comme React ou Vue.js pour créer des interfaces riches et performantes.

2. La Couche Back-end (Logique métier)
Considérée comme le mécanisme interne, elle travaille "en coulisses" pour répondre aux demandes du front-end.


Le Serveur Web : Reçoit les requêtes HTTP envoyées par le navigateur (ex: "l'utilisateur veut voir les films d'action").


Langages de programmation : Vous utilisez ici des scripts côté serveur comme Node.js, PHP ou Python pour traiter la logique (vérification des abonnements, algorithmes de recommandation).


Middleware : Cette strate cachée fait le lien entre le client et le serveur, facilitant la distribution des opérations en temps réel.

3. La Couche de Données (Stockage)
C'est ici que sont stockées toutes les informations nécessaires au fonctionnement de votre clone Netflix.


Contenu stocké : On y trouve les métadonnées des films (titres, résumés, liens vers les vidéos), les informations des utilisateurs (identifiants, historique de visionnage) et les icônes.

Systèmes de Gestion de Base de Données (SGBD) :


Relationnels : Comme MySQL ou PostgreSQL.


Non-relationnels : Comme MongoDB, souvent utilisé pour sa flexibilité avec les données de type document
