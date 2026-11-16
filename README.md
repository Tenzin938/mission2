# SAE S3 26-27 – Association Marfans (Mission 2 : Refonte Front-End)

Prototype Front-End (HTML5, CSS3, JavaScript) réalisé dans le cadre de la **Mission 2** de la SAE S3, en cohérence avec :
- **Mission 1 :** Audit d'accessibilité et d'ergonomie du site de l'Association Marfans.
- **Mission 3 :** Modélisation du système d'information (MCD, dictionnaire de données et catalogue d'API REST).

## Aperçu rapide

Ouvrir directement `index.html` dans un navigateur ou lancer un serveur local :

```bash
python3 -m http.server 8080
```

Puis accéder à `http://localhost:8080/index.html`.

## Structure du projet

- `index.html` : Page d'accueil refondue (explication immédiate de la maladie, CTAs unifiés, aperçu dynamique des activités).
- `la-genetique.html` : Vulgarisation génétique, schéma FBN1, vidéos sous-titrées avec transcriptions, carte interactive des centres.
- `contact-adhesion.html` : Formulaires Contact, Adhésion et Don 100 % clavier avec messages d'erreur explicites par champ.
- `login.html` : Connexion simulée au SI (`F10`) avec comptes de démonstration pour les profils Mission 3.
- `espace-benevole.html` : Espace personnel bénévole (`F4`, `F7`) avec filtres, gestion de disponibilités et validité des formations.
- `responsable-ateliers.html` : Synthèse et alertes (`F3`, `F5`, `F8`), création/modification/annulation d'activité, gestion des inscriptions et liste d'attente.
- `css/` : Design System (`variables.css`), base accessible (`base.css`), composants (`components.css`) et mises en page (`pages.css`).
- `js/` : Couche données & règles métier (`data.js`) + scripts par page.
- `data/mock.json` : Jeu de données conforme au dictionnaire de données de la Mission 3.
- `NOTE_ACCOMPAGNEMENT.md` : Note d'accompagnement attendue sur Moodle.
