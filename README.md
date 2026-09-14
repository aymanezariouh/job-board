# DevTalent - Job Board (Stages & Alternances Tech)

DevTalent est une plateforme moderne (UI/UX) conçue pour mettre en relation les étudiants avec les meilleures opportunités technologiques (stages et alternances) proposées par des startups et entreprises du secteur.

Le projet a été réalisé de manière stricte avec **HTML5 et CSS3 pur**, sans recours à JavaScript, pour répondre aux contraintes académiques, tout en conservant un design professionnel, interactif (animations CSS, menus "hack" CSS) et responsive.

##  Fonctionnalités Principales

- **Page d'accueil Étudiant (`index.html`)** : Interface moderne de type "Landing Page" avec hero header, cartes d'avantages, et liste des offres sous forme de cartes (Grid/Flexbox).
- **Détail de l'offre (`offre-detail.html`)** : Page décrivant le poste, l'entreprise, les prérequis, avec des boutons de candidature et de sauvegarde.
- **Offres suivies (`offres-suivies.html`)** : Tableau de bord côté étudiant permettant de visualiser les candidatures sauvegardées ou en cours.
- **Tableau de bord Recruteur (`admin/index.html`)** : Aperçu de l'activité (statistiques) et liste des dernières candidatures reçues.
- **Création d'offre (`deposer-offre.html`)** : Formulaire multi-étapes avancé (avec barre d'outils WYSIWYG factice) pour la publication d'une offre.

##  Design & Technique

- **100% HTML/CSS** : Aucun script JS n'est utilisé. 
- **Responsive Web Design** : Utilisation des Media Queries, Flexbox et CSS Grid pour assurer un affichage parfait sur ordinateur, tablette et smartphone.
- **Composants interactifs (CSS-only)** : 
  - Système d'onglets et de filtres basés sur CSS.
  - Menu latéral mobile (sidebar) fonctionnel via la technique des `<input type="checkbox">`.
  - Transitions douces au survol (hover).
- **Architecture CSS** : Variables CSS (Custom Properties) pour une gestion centralisée du thème (couleurs, bordures, espacements).

##  Structure du Projet

```text
job-board/
├── index.html                # Page d'accueil publique (Étudiants)
├── offre-detail.html         # Fiche détaillée d'une offre
├── deposer-offre.html        # Formulaire de publication (Recruteurs)
├── offres-suivies.html       # Suivi des candidatures (Étudiants)
├── admin/
│   └── index.html            # Tableau de bord d'administration
├── assets/
│   └── images/               # Ressources graphiques et logos
├── css/
│   └── style.css             # Feuille de style principale
└── docs/                     # Documents de conception (Cahier des charges, etc.)
```

##  Comment lancer le projet ?

Ce projet étant statique (uniquement Front-End), aucun serveur ou installation de dépendance n'est requis.

1. Téléchargez ou clonez ce dossier.
2. Double-cliquez simplement sur le fichier **`index.html`** pour l'ouvrir dans le navigateur web de votre choix (Chrome, Firefox, Safari, Edge...).
3. Naviguez entre les pages en utilisant les boutons de l'interface.

##  Auteur
Projet réalisé dans le cadre de la formation (Développement Front-End).
