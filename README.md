# Simulateurs PLF 2027 pour les collectivités

Deux outils gratuits pour chiffrer l’effet du projet de loi de finances (PLF) 2027 et de la hausse des cotisations CNRACL sur le budget d’une collectivité, avec les données publiques.

| Outil | Fichier | Couverture |
|---|---|---|
| Départements | `departements.html` | 95 départements de métropole |
| Communes et intercommunalités | `communes-intercommunalites.html` | 34 961 communes, 1 230 intercommunalités, budgets annexes compris |

**Utiliser en ligne** : ouvrez la page d’accueil du site (GitHub Pages), puis choisissez l’outil.

**Utiliser hors ligne** : téléchargez le fichier HTML et ouvrez-le dans un navigateur récent (Edge, Chrome, Firefox, Safari). Aucune installation, aucune connexion nécessaire.

## Ce que font les outils

- Effet de chaque mesure du PLF 2027 sur l’épargne brute et le FCTVA, selon la version du texte : texte déposé, votes de l’Assemblée, ordonnance, 49.3.
- Épargne, taux d’épargne, encours, capacité de désendettement ; prospective 2027-2029.
- Perspective BP 2027 : BP 2026, propositions 2027 saisies ou importées (Excel .xlsx, CSV, copier-coller), saisie par chapitres M57, export Excel, enregistrement dans un fichier à transmettre.
- Note de synthèse imprimable, paragraphe pour le rapport d’orientation budgétaire, présentation pour les élus.
- Communes et intercommunalités : budget principal, budgets annexes ou consolidé ; commune et part de l’intercommunalité ; FDPTP et fonds départemental des droits de mutation ; dotations nouvelles (articles 85 et 87) ; mode simplifié pour les petites communes.

## Confidentialité

Tout fonctionne dans le navigateur. Les fichiers importés et les saisies restent sur le poste de l’utilisateur ; rien n’est transmis.

## Sources des données

- Chiffrage du PLF 2027 par collectivité, texte déposé : Bouilland Poilbout Avocats, data.gouv.fr.
- Comptes 2018-2025 des collectivités : OFGL, data.ofgl.fr.
- Balances comptables 2025 des communes : DGFiP, data.economie.gouv.fr.
- Fonds de carte : IGN Admin Express.

Toutes ces données sont publiées sous Licence Ouverte 2.0 (Etalab).

## Limites

- Estimations sur des textes en cours d’examen : elles ne valent pas notification.
- Plusieurs mesures sont réparties faute de clé publiée ; leur fiabilité est indiquée dans les outils.
- Les dotations nouvelles du bloc communal (articles 85 et 87) s’ajoutent sur déclaration : leurs critères ne sont pas applicables avec les données publiques.
- Certaines communes comptabilisent le fonds départemental des droits de mutation avec un an de décalage ou sur un autre compte : elles apparaissent sans montant.

## Retours de test

Chaque outil propose, dans « Prise en main », un compte rendu de test à copier. Ouvrez une *issue* sur ce dépôt ou écrivez à l’auteur.

## Mises à jour

L’état des textes est daté dans chaque outil. Les chiffres seront actualisés après le vote du Sénat et l’adoption définitive.

## Licence

Code sous licence MIT (voir `LICENSE`). Données sous Licence Ouverte 2.0.
