# Sales Intelligence

## Un projet progressif pour apprendre Python et découvrir la Data Science

> **En une phrase :** Sales Intelligence est un programme qui transforme
> l'historique des ventes d'une boutique en informations utiles pour
> mieux comprendre les produits et les clients.

## 1. Pourquoi ce projet existe-t-il ?

Imagine une boutique qui vend des chaussures, des sacs et des
accessoires. Chaque jour, des clients achètent différents produits. Le
commerçant enregistre les ventes, mais il ne sait pas toujours répondre
facilement à ces questions :

-   Quels produits se vendent le mieux ?
-   Quels clients reviennent souvent ?
-   Quels produits sont souvent achetés ensemble ?
-   Certaines ventes semblent-elles inhabituelles ?
-   Quels produits pourrait-on proposer à un client selon ses achats
    passés ?

**Sales Intelligence** vise à répondre progressivement à ces questions à
partir des informations enregistrées sur les ventes. Le projet commence
avec des données fictives : cela permet d'apprendre sans exposer les
informations confidentielles de vrais clients.

## 2. Que signifie « Sales Intelligence » ?

-   **Sales** signifie « ventes » en anglais.
-   **Intelligence** désigne ici l'analyse des informations pour mieux
    comprendre une situation et prendre des décisions.

Le nom peut donc se comprendre comme **« analyse intelligente des ventes
»**. Le programme ne devine pas tout seul : ses résultats dépendent des
données disponibles et des méthodes que nous construisons.

## 3. Comment le programme fonctionne-t-il ?

Le travail suit quatre grandes étapes :

1.  **Rassembler les informations.** Le programme récupère les données
    des ventes : produit, quantité, prix, date et, si disponible,
    identifiant du client.
2.  **Vérifier les informations.** Il recherche les erreurs, les données
    manquantes et les doublons.
3.  **Analyser les ventes.** Il regroupe les informations et applique
    des algorithmes pour repérer des tendances ou des situations
    inhabituelles.
4.  **Présenter les résultats.** Il produit des classements, des résumés
    et, à terme, des suggestions de produits.

Exemple : si la boutique enregistre les produits de chaque commande, le
programme peut compter les produits les plus vendus. Plus tard, il
pourra rechercher les produits souvent présents dans une même commande.

## 4. Les informations utilisées

Une vente peut contenir les informations suivantes :

  -----------------------------------------------------------------------
  Information                         Explication
  ----------------------------------- -----------------------------------
  Identifiant de vente                Un code unique pour reconnaître la
                                      vente.

  Date                                Le jour où la vente a eu lieu.

  Identifiant du produit              Le code du produit vendu.

  Catégorie                           Le type de produit : chaussure,
                                      sac, accessoire, etc.

  Quantité                            Le nombre d'unités vendues.

  Prix unitaire                       Le prix d'une unité du produit.

  Identifiant du client               Un code permettant de relier ses
                                      achats sans devoir utiliser son
                                      nom.

  Ville                               La ville associée à la vente, si
                                      disponible.

  Mode de paiement                    Le moyen de paiement utilisé, si
                                      disponible.
  -----------------------------------------------------------------------

Ces informations forment le **jeu de données** : l'ensemble des données
sur lesquelles le programme travaille. Au début, quelques dizaines de
ventes fictives suffisent.

## 5. Le projet évolue avec l'apprentissage

Sales Intelligence est un **projet fil rouge** : on garde le même projet
et on l'améliore à chaque étape. Les fonctionnalités ci-dessous sont des
objectifs de développement ; elles ne sont pas nécessairement déjà
programmées.

### Étape 1 --- Représenter une vente

Apprendre à enregistrer le produit, le prix, la quantité et la date avec
les variables et les types Python.

**Résultat attendu :** créer et afficher une vente.

### Étape 2 --- Gérer plusieurs ventes

Regrouper les ventes et les produits dans des collections, puis
retrouver les informations nécessaires.

**Résultat attendu :** consulter un petit historique de ventes.

### Étape 3 --- Appliquer des règles

Vérifier qu'une quantité ou un prix est valide et distinguer différentes
catégories de ventes.

**Résultat attendu :** repérer une vente qui doit être vérifiée.

### Étape 4 --- Parcourir l'historique

Analyser plusieurs ventes, compter les ventes par produit et établir un
classement.

**Algorithme : Top-K.** Trouver les K meilleurs produits selon un
critère sans forcément trier toutes les données.

### Étape 5 --- Organiser le code avec des fonctions

Séparer les tâches : charger les ventes, filtrer les résultats,
regrouper les produits et produire des indicateurs.

**Résultat attendu :** réutiliser une fonction à plusieurs endroits du
programme.

### Étape 6 --- Transformer les données

Créer des listes d'informations dérivées : produits actifs, ventes
importantes ou transactions correspondant à plusieurs critères.

**Résultat attendu :** préparer les données pour différentes analyses.

### Étape 7 --- Gérer les erreurs

Prévoir ce qui arrive si un fichier manque, si une ligne est incomplète
ou si une valeur ne respecte pas les règles.

**Résultat attendu :** expliquer les problèmes rencontrés au lieu de
laisser le programme échouer sans indication utile.

### Étape 8 --- Enregistrer et relire les données

Sauvegarder les ventes dans des fichiers CSV ou JSON, puis les recharger
au lancement suivant.

**Algorithme : détection de doublons.** Repérer les enregistrements qui
semblent représenter la même transaction, sans confondre deux ventes
légitimes.

### Étape 9 --- Séparer le projet en modules

Ranger le code par responsabilité : chargement, nettoyage, analyse et
gestion des clients.

**Résultat attendu :** un projet plus facile à comprendre et à
maintenir.

### Étape 10 --- Utiliser des classes et des objets

Représenter les éléments du domaine, comme une vente, un produit ou un
client, avec des objets Python.

**Résultat attendu :** un code qui représente plus clairement les
éléments réels du commerce.

### Étape 11 --- Ajouter des indications de types

Préciser les types de valeurs attendues par les fonctions afin de rendre
le code plus lisible et de faciliter la détection de certaines erreurs.

### Étape 12 --- Préparer un environnement reproductible

Créer un environnement Python isolé et documenter les dépendances
éventuelles pour que le projet puisse être exécuté dans des conditions
cohérentes.

### Étape 13 --- Tester le programme

Écrire des tests qui vérifient les résultats attendus, notamment pour
les données vides, les valeurs incorrectes, les doublons et les cas
limites.

**Résultat attendu :** pouvoir modifier le programme avec davantage de
confiance.

## 6. Les algorithmes orientés Data Science

Un **algorithme** est une suite d'étapes précises permettant de résoudre
un problème. Dans ce projet, on les implémente d'abord en Python
standard pour comprendre leur logique.

### 6.1 Classement Top-K

**Question :** quels sont les cinq produits les plus vendus ?

Le programme compte les quantités vendues par produit et conserve les
cinq meilleurs résultats. L'exercice consiste à comparer un tri complet
avec une méthode qui ne conserve que les meilleurs candidats.

### 6.2 Segmentation RFM des clients

RFM représente trois dimensions du comportement d'achat :

-   **Récence :** depuis combien de temps le client n'a-t-il pas acheté
    ?
-   **Fréquence :** combien d'achats a-t-il effectués ?
-   **Montant :** combien a-t-il dépensé au total ?

Le programme calcule ces indicateurs et applique des règles pour créer
des groupes comme « client régulier », « client occasionnel » ou «
client à réengager ». Ces groupes sont des approximations : ils ne
révèlent pas nécessairement les intentions réelles des clients.

### 6.3 Détection d'anomalies

**Question :** quelles ventes méritent une vérification ?

Le programme attribue un score à une transaction à partir de plusieurs
signaux, comme une quantité inhabituellement élevée ou un montant
éloigné du comportement habituel. Une anomalie n'est pas automatiquement
une fraude : c'est un signal à examiner.

### 6.4 Matrice de co-occurrence des produits

**Question :** quels produits apparaissent souvent dans la même commande
?

Le programme compte les paires de produits présentes ensemble dans les
commandes. Ces résultats peuvent aider à imaginer des lots ou des
suggestions complémentaires. Une association observée ne prouve pas
qu'un produit entraîne l'achat de l'autre.

### 6.5 Similarité entre clients et recommandations

Le programme représente les habitudes d'achat de chaque client, compare
les profils, puis recherche les produits achetés par des clients
similaires mais pas encore par le client étudié.

Les recommandations seront limitées si l'historique est trop petit ou
incomplet. Leur pertinence devra être évaluée avant toute utilisation
réelle.

### 6.6 Pipeline de données

Un pipeline est une chaîne d'étapes répétables :

**données brutes → validation → nettoyage → transformation → analyse →
export des résultats.**

L'objectif est de pouvoir refaire la même analyse sans répéter
manuellement toutes les opérations.

## 7. Organisation prévue des fichiers

Voici un exemple d'organisation que le projet pourra adopter au fur et à
mesure de sa croissance :

``` text
sales_intelligence/
├── data/
│   ├── raw/                 # Données d'origine
│   └── processed/           # Données nettoyées
├── src/
│   ├── models/              # Modèles Vente, Client, Produit
│   ├── data_loader.py       # Lecture des fichiers
│   ├── cleaning.py          # Vérification et nettoyage
│   ├── analysis.py          # Analyses et classements
│   ├── segmentation.py      # Groupes de clients
│   ├── recommendation.py    # Suggestions de produits
│   └── utils.py             # Fonctions utiles
├── tests/                   # Tests automatiques
├── main.py                  # Point de départ du programme
├── requirements.txt         # Dépendances éventuelles
└── README.md                # Documentation du projet
```

Cette structure est une proposition cible, pas la garantie que tous ces
fichiers existent déjà. On peut commencer avec un ou deux fichiers puis
les séparer lorsque cela devient utile.

## 8. Comment commencer concrètement ?

1.  Installer Python sur l'ordinateur.
2.  Créer un dossier nommé `sales_intelligence`.
3.  Créer un environnement virtuel Python.
4.  Créer un premier fichier `main.py`.
5.  Ajouter cinq à dix ventes fictives.
6.  Écrire un programme qui affiche ces ventes et vérifie que les
    quantités et les prix sont valides.
7.  Ajouter une fonctionnalité à la fois et tester les résultats avant
    de continuer.

Il n'est pas nécessaire de commencer avec une interface graphique, un
site web ou une base de données. Une application dans le terminal suffit
pour apprendre les bases.

## 9. Ce que le projet n'est pas encore

Au début, Sales Intelligence n'est pas :

-   un logiciel commercial prêt à être utilisé par une vraie boutique ;
-   un modèle d'intelligence artificielle déjà entraîné ;
-   une garantie de détection de fraude ;
-   un système de recommandation fiable sans données suffisantes ;
-   une application avec une interface graphique complète.

Ces éléments pourront être envisagés plus tard si les compétences et les
données le permettent.

## 10. Quand le Niveau 1 est-il terminé ?

Le Niveau 1 est réussi lorsque tu peux :

-   expliquer comment une vente est représentée dans le programme ;
-   charger, valider, nettoyer et sauvegarder un petit historique ;
-   organiser le code avec des fonctions, modules et classes simples ;
-   implémenter et expliquer les algorithmes étudiés ;
-   tester les résultats et traiter les erreurs ;
-   lancer le projet dans un environnement documenté.

Tu n'as pas besoin de tout mémoriser. L'important est de comprendre les
choix réalisés et de pouvoir retrouver, tester et améliorer ton code.

## 11. La suite : passer de Python à la Data Science

Une fois les fondations maîtrisées, le même projet pourra évoluer :

-   **NumPy :** calculs numériques sur des tableaux ;
-   **Pandas :** manipulation de jeux de données plus grands ;
-   **Statistiques :** comprendre la distribution et les relations entre
    les données ;
-   **Visualisation :** représenter les tendances sous forme de
    graphiques ;
-   **Machine Learning :** entraîner et évaluer des modèles sur des
    données adaptées ;
-   **Déploiement :** rendre les analyses accessibles via une interface
    ou une API.

L'objectif est de progresser du code de base vers des analyses plus
sérieuses, sans sauter les étapes de compréhension et de vérification.

------------------------------------------------------------------------

## Résumé

**Sales Intelligence est un seul projet qui grandit avec toi.** Il
commence par l'enregistrement de ventes fictives, apprend ensuite à
vérifier et analyser les données, puis explore les comportements des
clients, les anomalies et les recommandations.

Le meilleur point de départ est simple : créer `main.py`, enregistrer
quelques ventes fictives et vérifier leurs données. Ensuite, faire
évoluer le programme une fonctionnalité à la fois.
