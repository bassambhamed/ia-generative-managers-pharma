# IA générative et agentique pour managers, marketing et formation

Parcours de formation pratique à l'intelligence artificielle générative pour les fonctions d'encadrement de l'industrie pharmaceutique :

- managers des ventes ;
- chefs de produit marketing ;
- responsables Formation et Développement humain.

Le parcours compte **trois modules** et **douze ateliers**. Chaque atelier part d'un besoin réel du métier : reporting, segmentation, plan de tournée, réunion de cycle, plan d'action secteur, événements scientifiques, entretiens difficiles, tableau de bord. Tout se fait à l'écran, sur un réseau commercial **entièrement fictif**.

> **Public** : débutants, sans prérequis technique.
> **Format** : apports courts, démonstrations en direct, ateliers en binôme, débriefs.
> **Outils** : Gemini, NotebookLM, Google Antigravity, Microsoft Excel.

---

## Les trois modules

### Module 1 — Comprendre l'IA générative et maîtriser le prompting

**Concepts**

- IA, apprentissage automatique (ML), apprentissage profond (DL) et IA générative.
- IA discriminative ou IA générative, avec des cas d'usage pharmaceutiques pour les ventes, le marketing, la pharmacovigilance, la formation et l'approvisionnement.
- Le fonctionnement d'un grand modèle de langage et quatre notions : jeton, fenêtre de contexte, date de coupure, hallucination.
- La méthode **CADRE** : contexte, action, données, résultat, exigences.
- Dix techniques avancées de prompting :
  - rôle ;
  - exemples ;
  - délimiteurs ;
  - format imposé ;
  - sortie de secours ;
  - étapes ;
  - enchaînement ;
  - autocontrôle ;
  - contradicteur ;
  - demander la méthode.
- Ce que le prompting ne règle pas.

**Ateliers** (Gemini et Excel)

| N° | Atelier | Besoin couvert |
|---|---|---|
| 1 | Du brouillon au prompt cadré | Communiquer avec son équipe ; trier les données selon les trois feux |
| 2 | Reporting et relevé de décisions | Comptes rendus de délégués et notes de réunion |
| 3 | Segmentation, ciblage, profiling | Fiabiliser et segmenter un fichier médecins |
| 4 | Plan de tournée et planning | Planifier un cycle sous contraintes de fréquence et de capacité |

**Gabarits de prompts** : G1 à G8.

### Module 2 — Les systèmes RAG

**Concepts**

- Pourquoi un modèle seul ne suffit pas.
- Le fonctionnement d'un système RAG (*Retrieval-Augmented Generation*) : découpage, recherche par le sens, génération à partir des passages retrouvés.
- Trois façons de donner ses documents au modèle : les coller dans la demande, le RAG, le réentraînement.
- Ce que le RAG règle, ce qu'il ne règle pas, et comment vérifier une citation.
- Des cas d'usage pharmaceutiques, puis NotebookLM comme RAG prêt à l'emploi.

**Ateliers** (NotebookLM, Gemini et Excel)

| N° | Atelier | Besoin couvert |
|---|---|---|
| 5 | Préparer et piloter une réunion | Ordre du jour, dossier, questions attendues, chaque point sourcé |
| 6 | Plan d'action secteur | Diagnostic d'un secteur en sous-performance, actions datées, indicateurs |
| 7 | Sociétés savantes et événements | Contrôler un dossier d'événement au regard d'une charte d'hospitalité |
| 8 | Entretiens difficiles | Préparer un entretien et s'y entraîner en jeu de rôle avec l'IA |

**Gabarits de prompts** : G9 à G14.

### Module 3 — Agents et workflows agentiques

**Concepts**

- Du modèle à l'agent : la boucle objectif, planifier, agir, observer, rendre compte.
- Workflow agentique ou agent autonome.
- Cinq schémas de workflow, avec des exemples pharmaceutiques.
- Ce qui peut mal tourner, et les garde-fous :
  - plan validé avant d'agir ;
  - permissions ;
  - règles écrites ;
  - traces ;
  - humain aux points de sortie.
- Google Antigravity : plan d'implémentation, validation, compte rendu d'exécution, règles et compétences (*skills*).

**Ateliers** (Google Antigravity et Excel)

| N° | Atelier | Besoin couvert |
|---|---|---|
| 9 | Tableau de bord et indicateurs | Écrire un cahier des charges et faire fabriquer un tableau de bord |
| 10 | Auditer et faire évoluer le tableau | Contrôler les chiffres contre Excel, ajouter des filtres |
| 11 | Le rituel du lundi | Une chaîne hebdomadaire de reporting avec points d'arrêt |
| 12 | Votre projet, par métier | Appliquer la méthode à un besoin réel de son poste |

**Gabarits de prompts** : G15 à G17. Le cahier du module 3 se termine par la bibliothèque complète G1 à G17.

---

## Contenu du dépôt

```
.
├── README.md
├── Module 1/
│   ├── Module1_Diaporama.pdf        concepts, prompting, consignes des ateliers 1 à 4
│   ├── Module1_Ateliers.pdf         cahier d'ateliers, à lire
│   ├── Module1_Ateliers.docx        le même cahier, à remplir à l'écran
│   └── Supports/
│       ├── NOVAMED_Reseau.xlsx      réseau commercial fictif
│       ├── M1_Plan_Marketing_Cycle.pdf
│       ├── M2_Comptes_Rendus_Delegues.pdf
│       └── M3_Notes_Reunion_Cycle.pdf
├── Module 2/
│   ├── Module2_Diaporama.pdf
│   ├── Module2_Ateliers.pdf
│   ├── Module2_Ateliers.docx
│   └── Supports/                    classeur, M1 à M5
└── Module 3/
    ├── Module3_Diaporama.pdf
    ├── Module3_Ateliers.pdf
    ├── Module3_Ateliers.docx
    └── Supports/                    classeur
```

Chaque module contient un diaporama, un cahier d'ateliers et un dossier `Supports`.

- Le cahier existe en deux versions :
  - le **PDF** se lit ;
  - le **Word** se remplit pendant les ateliers.
- Le dossier `Supports` contient les documents de travail du module.

### Les documents de travail

| Document | Contenu | Modules |
|---|---|---|
| `NOVAMED_Reseau.xlsx` | Délégués, secteurs, médecins, visites, ventes mensuelles et objectifs d'un réseau fictif | 1, 2, 3 |
| `M1_Plan_Marketing_Cycle` | Plan marketing du cycle : segmentation, fréquences de visite, capacité terrain | 1, 2 |
| `M2_Comptes_Rendus_Delegues` | Comptes rendus hebdomadaires bruts de délégués | 1, 2 |
| `M3_Notes_Reunion_Cycle` | Notes brutes d'une réunion de cycle | 1, 2 |
| `M4_Dossier_EPU_Cardiologie` | Charte d'hospitalité et dossier d'un événement de société savante | 2 |
| `M5_Cas_Entretiens` | Deux cas d'entretien managérial et leurs consignes de jeu de rôle | 2 |

Les documents contiennent des erreurs, des doublons et des contradictions **volontaires**. Les ateliers apprennent à les repérer : l'IA propose, Excel et les sources prouvent.

---

## Utiliser le parcours

1. Ouvrez le diaporama du module.
2. Pour chaque atelier, suivez le cahier Word. Les prompts sont écrits sans accents pour se copier sans erreur.
3. Contrôlez chaque chiffre dans Excel et chaque affirmation dans sa source.

**Avant le module 3**, installez Google Antigravity ([antigravity.google](https://antigravity.google), macOS, Windows ou Linux). Sans installation possible, le mode *Build* de Google AI Studio sert de solution de repli.

## Règle de données : les trois feux

| Feu | Données | Usage |
|---|---|---|
| 🟢 Vert | Le kit fictif NOVAMED, les documents publics, vos gabarits de prompts | Autorisé dans les outils du parcours |
| 🟠 Orange | Chiffres de ventes internes, plans marketing, fichiers de ciblage même anonymisés | Uniquement dans un outil d'entreprise validé |
| 🔴 Rouge | Fichier nominatif de médecins, données sur un salarié, données patient ou de pharmacovigilance | Jamais dans un outil d'IA grand public |

## Avertissement

Le laboratoire NOVAMED, ses produits (TENSIPROL®, GASTRÉVA…), ses délégués, ses médecins et l'ensemble des chiffres sont **fictifs**. Toute ressemblance avec des personnes, des produits ou des données réels serait fortuite. Les supports ne constituent ni une information médicale ni une recommandation de prescription.

Les interfaces des outils cités évoluent rapidement. Les consignes ont été vérifiées en novembre 2026.
