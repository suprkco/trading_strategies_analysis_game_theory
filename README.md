# Projet d'analyse des stratégies de trading algorithmique - tradingStrategiesAnalysis

Ce projet consiste à analyser l'impact des stratégies de trading algorithmique sur la liquidité des marchés financiers en utilisant la théorie des jeux appliquée à la finance.

## Introduction

L'objectif de ce projet est d'analyser l'impact des stratégies de trading algorithmique sur la liquidité des marchés financiers en utilisant les principes de la théorie des jeux. Les marchés financiers modernes sont de plus en plus dominés par les algorithmes de trading, qui sont capables d'exécuter des transactions à une vitesse bien supérieure à celle des traders humains. Les algorithmes peuvent entraîner des conséquences négatives pour les investisseurs et les entreprises, car ils peuvent provoquer une baisse de la liquidité sur les marchés financiers.

Pour comprendre comment les stratégies de trading algorithmique affectent la liquidité des marchés financiers, nous allons utiliser la théorie des jeux, qui est une branche des mathématiques qui étudie les interactions stratégiques entre les acteurs dans un environnement concurrentiel. En appliquant la théorie des jeux à l'analyse des marchés financiers, nous pourrons mieux comprendre comment les algorithmes de trading interagissent les uns avec les autres et avec les traders humains.

Nous allons également étudier différentes stratégies de trading algorithmique, telles que la stratégie de liquidité élevée, la stratégie de suivi de tendance et la stratégie de prise de risque élevé, pour évaluer leur impact sur la liquidité des marchés financiers. En utilisant des données réelles de marché, nous allons simuler l'interaction entre ces différentes stratégies pour comprendre comment elles se comportent dans des scénarios différents.

L'analyse des stratégies de trading algorithmique et de leur impact sur la liquidité des marchés financiers est un sujet important et d'actualité dans le monde de la finance. Les résultats de cette étude pourront aider les entreprises et les investisseurs à mieux comprendre les risques associés aux différentes stratégies de trading algorithmique et à prendre des décisions plus éclairées en matière d'investissement.

## Analyse théorique

### Stratégies et profil existants :
1. La stratégie de liquidité élevée vise à améliorer la liquidité des marchés financiers en fournissant des offres et des demandes à des prix compétitifs. Les algorithmes qui l'utilisent cherchent à réduire l'écart entre l'offre et la demande pour attirer les transactions. Cela peut se faire en achetant ou vendant une quantité importante d'actifs à un prix limité, en utilisant des ordres limites pour contrôler l'exécution des transactions ou encore en maximisant la liquidité disponible sur le marché.
- Acheter ou vendre une quantité importante d'actifs à un prix limité
- Utiliser des ordres limites pour contrôler l'exécution des transactions
- Maximiser la liquidité disponible sur le marché

2. Stratégie de liquidité faible : Cette stratégie vise à maximiser les profits en utilisant des offres et des demandes qui ne sont pas compétitives. Les algorithmes qui utilisent cette stratégie peuvent chercher à tirer profit de l'écart entre l'offre et la demande ou à profiter d'autres inefficacités du marché. Pour ce faire, ils peuvent adopter différentes tactiques telles que : acheter ou vendre une quantité limitée d'actifs à un prix déterminé à l'avance, utiliser des ordres au marché pour exécuter rapidement les transactions et minimiser l'impact sur le marché en évitant de perturber la liquidité.
- Acheter ou vendre une quantité limitée d'actifs à un prix déterminé à l'avance
- Utiliser des ordres au marché pour exécuter rapidement les transactions
- Minimiser l'impact sur le marché en évitant de perturber la liquidité


3. La stratégie de suivi de tendance a pour but de profiter des tendances du marché en utilisant des algorithmes qui suivent les tendances de prix à long terme. Ces algorithmes ont des modèles de trading qui cherchent à identifier les tendances à long terme et à effectuer des transactions en conséquence. Pour cela, ils peuvent se baser sur des indicateurs techniques tels que les moyennes mobiles pour déterminer la direction de la tendance.
- Analyser les tendances du marché et prendre position en fonction de ces tendances
- Acheter lorsque la tendance est à la hausse et vendre lorsque la tendance est à la baisse
- Utiliser des indicateurs techniques pour identifier les tendances

4. La stratégie de prise de risque élevé a pour objectif de maximiser les profits en prenant des risques plus élevés que la normale. Les algorithmes qui l'utilisent ont recours à des stratégies de trading plus agressives pour exploiter l'écart entre l'offre et la demande. Ces stratégies peuvent inclure le trading sur marge ou le trading de produits dérivés. En outre, les algorithmes peuvent placer des ordres à des prix très éloignés du marché afin de profiter de mouvements extrêmes de prix.
- Prendre des positions agressives pour maximiser les gains potentiels
- Utiliser des ordres au marché pour exécuter rapidement les transactions
- Prendre des positions contraires aux tendances du marché pour profiter des mouvements de prix à court terme.

5. La stratégie de prise de risque faible a pour but de minimiser les risques en ayant recours à des stratégies de trading plus conservatrices. Les algorithmes qui l'utilisent ont pour objectif de réduire les pertes en utilisant des ordres limites et d'autres stratégies qui réduisent le risque de perte. Ils peuvent également mettre en place des stratégies de trading à faible fréquence qui exécutent des transactions moins souvent pour limiter l'exposition au risque.
- Prendre des positions conservatrices pour minimiser les pertes potentielles
- Utiliser des ordres limites pour contrôler l'exécution des transactions
- Éviter les positions contraires aux tendances du marché pour minimiser les risques.

## Collecte des données

Les données sont récupérées via l'API `yfinance` et sont mises à jour très rapidement de sorte à ce qu'un court laps de temps soit suffisant pour faire des simulations. De plus, pour diversifier les données on récupères plusieurs marché à des moments différents pour une génération fixée

## Analyse des données

## Interprétation des résultats

## Conclusion

## Fonctionnement du projet

Le projet est divisé en deux fichiers :
* `tradingStrategies.py` : contient les stratégies de trading algorithmique.
* `tradingStrategiesAnalysis.py` : contient les fonctions d'initialisation des traders, de calcul des commissions et de sélection des stratégies les plus viables au cours du temps.

Les données sont récupérées via l'API `yfinance` et sont mises à jour très rapidement de sorte à ce qu'un court laps de temps soit suffisant pour faire des simulations.

Le projet utilise également du multithreading pour accélérer les calculs.

## Dépendances du projet

Les dépendances du projet sont listées dans le fichier `requirements.txt`.

## Installation

- Clonez le projet depuis GitHub : `git clone https://github.com/votre_nom/projet-trading.git`
- Installez les dépendances : `pip install -r requirements.txt`

## Utilisation

- Ouvrez le fichier `tradingEnvironment.py` et modifiez les paramètres si nécessaire.
- Exécutez le fichier `tradingEnvironment.py` : python tradingEnvironment.py