# Maquette — application de séances vidéo

Prototype cliquable d'une application mobile de vidéos à la demande (étirements, fitness, danse, mobilité, respiration).

Un seul fichier, aucune dépendance : HTML, CSS et JavaScript natif, icônes en SVG inline. Seule la police Poppins est chargée depuis Google Fonts, avec repli sur la police système.

## Voir la maquette

Ouvrir `index.html` dans un navigateur, ou consulter la version en ligne. À regarder sur mobile de préférence : le format est calé sur une largeur de téléphone.

## Ce que la maquette contient

- **Accueil** — objectif du jour en anneau, temps actif, activité de la semaine, accès rapides par catégorie, reprise de la dernière séance.
- **Séances** — recherche, filtres par catégorie, liste des vidéos avec durée, calories et niveau.
- **Lecteur** — surface vidéo avec chronomètre, progression de la séance, déroulé des exercices.
- **Progrès** — anneaux d'activité, temps par jour, série en cours.
- **Profil** — objectif quotidien et règles de comptage du temps.

## Compteur de temps

Le chronomètre démarre à la lecture de la vidéo et s'arrête à la pause. Il se coupe aussi automatiquement quand l'application passe en arrière-plan (`visibilitychange`). Les secondes comptées alimentent en direct le temps actif du jour, le pourcentage d'objectif, les calories estimées, la barre du jour et les anneaux d'activité.

## Contenu de démonstration

Les huit séances, les statistiques de la semaine et les vignettes en dégradé sont des données de démonstration, définies en haut du `<script>`. Les vignettes seront remplacées par les miniatures réelles des vidéos.

## Publier

Le dépôt se publie tel quel avec GitHub Pages : *Settings → Pages → Deploy from a branch → `main` / `root`*.
