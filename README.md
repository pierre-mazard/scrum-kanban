# 🔎 Étude de cas Agile Scrum sur AstroVision AI 🔭📷

## 💫 Contexte du projet

Ce repository présente une **étude de cas complète** de gestion de projet Agile Scrum et Kanban autour d’un projet fictif nommé **AstroVision AI**.

**AstroVision AI** est une **suite d’outils d’intelligence artificielle dédiée à l’astrophotographie**,
regroupant **9 fonctionnalités principales** (*passez la souris sur chacunes des fonctionnalités pour en apprendre un peu plus*) :


<b title="Cette fonctionnalité sert à retirer le “bruit” présent sur les photos du ciel, c’est‑à‑dire les petits points parasites ou grains qui apparaissent à cause du capteur ou de la faible luminosité. L’IA utilise des modèles physiques pour reconstruire l’image comme si elle avait été prise dans des conditions idéales.">
1. 🧹 Débruitage physique-inversé des images astronomiques
</b>
<br><br>


<b title="La PSF représente la manière dont un télescope “diffuse” la lumière d’un point lumineux. En l’utilisant, l’IA peut recréer une image plus nette et plus détaillée que l’originale, comme si le télescope avait une résolution supérieure.">
2. 🔝 Super-résolution astronomique guidée par la PSF
</b>
<br><br>


<b title="Les images brutes contiennent des défauts liés au matériel (poussières, pixels défectueux, variations de luminosité). Cette fonctionnalité corrige automatiquement ces problèmes en analysant les images de calibration et en détectant les anomalies du capteur.">
3. ⚙️ Calibration intelligente (darks, flats, bias, défauts capteur)
</b>
<br><br>


<b title="L’IA identifie automatiquement les différents éléments présents dans l’image : étoiles, galaxies, nébuleuses, amas, etc. Elle peut aussi les classer pour aider l’utilisateur à comprendre ce qu’il observe.">
4. 🌌 Segmentation et classification des objets célestes
</b>
<br><br>


<b title="L’atmosphère déforme la lumière, ce qui rend les images floues ou instables. Cette fonctionnalité analyse des milliers de petites poses rapides pour reconstruire une image stable et nette, comme si l’atmosphère était parfaitement calme.">
5. 〰️ Correction de la turbulence atmosphérique (poses rapides / lucky imaging)
</b>
<br><br>


<b title="Les villes et l'activité humaine produisent une lumière diffuse qui crée des zones plus claires sur les photos du ciel. L’IA détecte ces gradients et les supprime pour révéler les véritables couleurs et structures des objets astronomiques.">
6. 🔆 Détection et correction des gradients et de la pollution lumineuse
</b>
<br><br>


<b title="Les objet émettent des couleurs spécifiques selon leur composition chimique. Cette fonctionnalité reconstruit les couleurs à partir des filtres utilisés, pour obtenir une image fidèle ou esthétiquement cohérente.">
7. 🌈 Reconstruction des couleurs physiques (Hα, OIII, SII, palettes SHO/HOO...)
</b>
<br><br>


<b title="L’IA aide l’utilisateur à choisir quoi photographier, quand le faire, comment orienter son matétiel, et quelles conditions météo ou astronomiques sont optimales. C’est un guide intelligent pour préparer une session d’observation ou d'acquisition.">
8. 🤖 Assistant IA de cadrage et de planification des sessions d’astrophotographie
</b>
<br><br>


<b title="Plusieurs personnes peuvent photographier le même objet avec du matériels différents. L’IA combine toutes ces images pour créer une version beaucoup plus détaillée, comme si elles provenaient d’un seul instrument très puissant.">
9. 🔭➕🔭 Fusion collaborative multi-observateurs (images provenant de plusieurs observateurs)
</b>
<br><br>


---

> ⚠️ Il s’agit d’un **projet pédagogique** : aucun code de production n’est actuellement fourni,
le focus est mis sur la **méthodologie Scrum/Kanban** et la gestion de projet.

---

## 🎯 Objectifs du repository

Ce repository a pour objectifs :

- d' **illustrer l’application de Scrum** sur un projet IA complexe,
- de **mettre en scène les événements Scrum** (Sprint Planning, Daily, Review, Rétrospective),
- de **présenter les artefacts** (Product Backlog, Kanban, User Stories, Burndown Chart, Gantt),
- de fournir une **documentation structurée** pour un rendu académique.

---

## 🗂️ Structure du repository

La structure cible du repository est la suivante :

```text
scrum-kanban/
├── README.md
├── docs/
│   └── scrum_guide.pdf
├── slides/
│   └── presentation_scrum_astrovision.pdf
├── artefacts/
│   ├── kanban_board.md
│   ├── user_stories.md
│   ├── burndown_chart.md
│   └── gantt_diagram.md
└── case-study/
    └── astrovision_case_study.md
```

`docs/` 📖
*   `Scrum_guide.pdf` : guide complet sur la méthode Agile Scrum, appliquée au projet AstroVision AI (rôles, événements, artefacts, étude de cas).

`slides/` 👨🏼‍🏫
*   `presentation_scrum_astrovision.pdf` : diaporama de présentation.

`artefacts/` ↪️
*   `kanban_board.md` : représentation du tableau kanban.

*   `user_stories.md` : liste des user stories pour les 9 fonctionnalités IA.

*   `burndown_chart.md` : burndown chart factice pour un sprint type.

*   `gant_diagram.md` : diagramme de Gantt simplifié du projet. 

`case-study/` 🧠💭
*   `astrovision_case_study.md` : description détaillée de l'étude de cas : 
Contexte, fonctionnalités, mise en scène des spints, dialogues simulés, priorisation des user stories, feedbacks des parties prenantes. 

## ⤵️ Méthodologie utilisée

Le projet s'appuie sur : 
*   **Scrum** pour la gestion des sprints : 
    *   Rôles : Product Owner, Scrum Mater, Dev Team (Data Scientists, ML Engineers, Dev, QA, experts métier)
    *   Événements : Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospetive
    *   Artefacts : Product Backlog, Sprint Backlog, Increment
*   **Kanban** pour la visualisation du flux de travail : 
    *   Colonnes : Backlog, À faire, En cours, En test, Terminé
    *   Cartes : modules IA et user stories associées

## ⁉️ Comment lire ce projet

**1️⃣. Commencer par le PDF** `docs/scrum_guide.pdf` pour comprendre la structure gloable de Scrum appliquée à AstroVision AI.

**2️⃣. Explorer les artefacts** dans `artefacts/` pour observer la matérialisation des soncepts (Kanban, user stories, burndown, Gantt)

**3️⃣. Consulter l'étude de cas** dans `case-study/astrovision_case_study.md` pour suivre la mise en scène des sprints et des décisions de l'équipe. 

**4️⃣. Utiliser les slides** dans `slides/` comme support de présentation. 

## ✍🏻 Auteur
*   **Pierre Mazard**

👨🏼‍🎓 *étudiant en Master 1 Expert Intelligence Artificielle / Data*

Projet réalisé dans le cadre d'une étude de cas sur la gesiton de proget Agile Scrum/Kanban.