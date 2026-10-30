# Ma séance — séances de maths construites sur mes manuels

Version « mes manuels » de [Fiches](https://github.com/tom-rougeaud/seance) (programme officiel). Même compte et mêmes données Supabase ; autre façon de préparer :

- **Les 4 manuels sont intégrés au fichier** : « Maths et MCV » 2de, 1re, Terminale et « 3ème Série Pro » — 33 chapitres, 143 notions (avec pages), 202 exercices (numéro, type, page).
- Dans une séance, la section **📘 Manuel** : choix du chapitre, notions et exercices à cocher ; chaque ligne a un lien vers **la bonne page du PDF** et vers l’appli du manuel ; liens du chapitre, des réponses, de « À toi » et de « S’évaluer ».
- Les notions cochées ajoutent les objectifs correspondants du BO : la **progression** de la classe reste à jour.
- **Mon année** : toutes les semaines regroupées par période entre les vacances, une pastille par semaine ; on touche une semaine, son emploi du temps s’affiche, on touche un cours et l’éditeur de séance s’ouvre à la bonne date (durée et matière du créneau) ; « Valider » ramène à la semaine pour choisir le cours suivant. Séquences prévues en glissant sur plusieurs semaines.
- **📥 Modèles › Mes manuels** : une séance d’1 h par notion (Je découvre › Je retiens › exercices), une séance de défis et une de contrôle par chapitre.
- **Synthèse Pronote** en lignes courtes : Objectif · Notion abordée · Exercice traité (avec pages), lien de l’appli, travail « Revoir… ».
- **Manuel CAP** intégré (10 chapitres, 40 notions, 150 exercices) : 5 manuels au total.
- **Bibliothèque › Mes manuels** : accordéon niveau › chapitre › liens (PDF, page, appli, réponses, notions, exercices) ; on coche, ils rejoignent la bibliothèque ou la fiche.
- **Fiche séance simplifiée** : boutons en couleurs, « Par où commencer ? », phases en un clic, « Plus d’options » repliées.
- Fiches exportées (PDF, Word, HTML) avec le bloc Manuel et ses liens.
- Parcours guidé (« Et maintenant ? » en bas de chaque page), version affichée et bandeau de mise à jour.

Adresse : <https://tom-rougeaud.github.io/maseance/> (GitHub Pages, branche `main`, dossier racine).
Le code source est celui du dépôt [seance](https://github.com/tom-rougeaud/seance) : `node build.js maseance` produit les fichiers de ce dépôt (`index.html`, `sw.js`, `manifest.webmanifest`, `icons/`).

Réglage Supabase (une fois) : Authentication › URL Configuration › Redirect URLs › ajouter `https://tom-rougeaud.github.io/maseance/`.

© Tom Rougeaud — licence [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr). Les manuels sont publiés par leur auteur sur leurs propres pages ; ce dépôt ne contient que leurs titres, numéros de page et d’exercice.
