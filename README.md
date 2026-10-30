# Ma séance — séances de maths construites sur mes manuels

Version « mes manuels » de [Fiches](https://github.com/tom-rougeaud/seance) (programme officiel). Même compte et mêmes données Supabase ; autre façon de préparer :

- **Les 4 manuels sont intégrés au fichier** : « Maths et MCV » 2de, 1re, Terminale et « 3ème Série Pro » — 33 chapitres, 143 notions (avec pages), 202 exercices (numéro, type, page).
- Dans une séance, la section **📘 Manuel** : choix du chapitre, notions et exercices à cocher ; chaque ligne a un lien vers **la bonne page du PDF** et vers l’appli du manuel ; liens du chapitre, des réponses, de « À toi » et de « S’évaluer ».
- Les notions cochées ajoutent les objectifs correspondants du BO : la **progression** de la classe reste à jour.
- **📥 Modèles › Mes manuels** : une séance d’1 h par notion (Je découvre › Je retiens › exercices), une séance de défis et une de contrôle par chapitre.
- **Synthèse Pronote** : chapitre, notions, exercices et pages, lien de l’appli, travail « Revoir… ».
- Fiches exportées (PDF, Word, HTML) avec le bloc Manuel et ses liens.
- Parcours guidé (« Et maintenant ? » en bas de chaque page), version affichée et bandeau de mise à jour.

Adresse : <https://tom-rougeaud.github.io/maseance/> (GitHub Pages, branche `main`, dossier racine).
Le code source est celui du dépôt [seance](https://github.com/tom-rougeaud/seance) : `node build.js maseance` produit les fichiers de ce dépôt (`index.html`, `sw.js`, `manifest.webmanifest`, `icons/`).

Réglage Supabase (une fois) : Authentication › URL Configuration › Redirect URLs › ajouter `https://tom-rougeaud.github.io/maseance/`.

© Tom Rougeaud — licence [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr). Les manuels sont publiés par leur auteur sur leurs propres pages ; ce dépôt ne contient que leurs titres, numéros de page et d’exercice.
