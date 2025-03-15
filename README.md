## Introduction au Material Flow Analysis

Ce module est présenté dans le cadre de *l'UC6 - Economie Ecologique* du diplôme de deuxième année d'ingénieur d'AgroParisTech. Plus précisément, ce module pratique vient illustrer et concrétiser le [cours relatif] au **métabolisme social**, assuré par [Simon Jean](https://sim-jean.github.io/)

Dans le cadre de ce module, vous apprendrez à:

1\. Télécharger les données d'Eurostat

2\. Calculer les variables clés de l'analyse MFA

3. Visualiser des séries de moyen terme

4\. Opérer une analyse initiale du phénomène de découplage

### Fonctionnement

-   Télécharger le fichier compressé de ce dossier

-   Ouvrez le fichier `intro_mfa.Rproj`qui lancera le projet sur votre machine

-   Ensuite, restaurez l'environnement (qui gère toutes les dépendances de packages) avec `renv::restore()`

-   Les scripts `01_utilities.qmd` et `02_analysis.qmd`:

    -   Permettent de construire l'architecture technique et de mettre l'analyse en oeuvre

    -   Et exportent des fichiers `.html`dans le dossier `docs`, pour servir de rapports
