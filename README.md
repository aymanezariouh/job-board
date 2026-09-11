# Job Board

Projet de création d'une interface de site d'offres d'emploi (Job Board) en HTML et CSS pur.

## Structure du Projet

Le projet respecte l'arborescence requise :
- `index.html` : Page d'accueil listant les offres
- `offre-detail.html` : Page affichant les détails d'une offre spécifique
- `deposer-offre.html` : Formulaire pour créer/déposer une nouvelle offre
- `offres-suivies.html` : Interface listant les offres sauvegardées par l'utilisateur
- `css/style.css` : Fichier de style global pour l'ensemble des pages
- `assets/images/` : Dossier contenant les ressources graphiques
- `docs/` : Dossier contenant la documentation liée à la conception (analyse, export Jira, lien Figma)

## Workflow Git / GitHub

Pour assurer un développement collaboratif propre, nous utilisons le workflow suivant :

1. **Branche Principale (`main`)** : Contient toujours une version stable et fonctionnelle du code.
2. **Branches de Fonctionnalité (`feature/...`)** : Chaque nouvelle page ou grosse modification CSS est développée sur une branche séparée (ex: `feature/page-accueil`, `feature/responsive-design`).
3. **Commits réguliers et explicites** : Les messages de commit décrivent clairement la modification apportée (ex: `feat: ajout du formulaire de dépôt d'offre`, `style: correction de l'alignement du header`).
4. **Pull Requests (PR)** : Une fois la fonctionnalité terminée, une Pull Request est ouverte vers `main` pour revue avant la fusion (merge).
