# Analyse des Températures et Catastrophes Naturelles aux États-Unis (2003–2022)

## I. Présentation du projet

Ce projet a pour objectif d’analyser l’évolution des températures et des catastrophes naturelles survenues aux États-Unis entre 2003 et 2022. Pour cela, deux jeux de données ont été utilisés :

1. **Jeu de données météorologiques sur les températures aux États-Unis**  
   **Source** : [Kaggle](https://www.kaggle.com/datasets/justinrwong/average-monthly-temperature-by-us-state?resource=download)

2. **Jeu de données sur les catastrophes naturelles à l’échelle mondiale**  
   **Source** : [EM-DAT](https://public.emdat.be/data)

---

### Étape 1 : Intégration des données

- Le jeu de données sur les températures contenait à l’origine des valeurs mensuelles par État.
- Agrégation des données par année pour obtenir une moyenne nationale annuelle.
- Filtrage du jeu de catastrophes pour ne conserver que les événements dont le code ISO correspond aux États-Unis.
- Fusion des deux jeux de données sur les années communes.
- Suppression des lignes sans température disponible.

---

### Étape 2 : Nettoyage des données

- Suppression des colonnes avec valeurs manquantes (températures absentes).
- Remplacement des localisations manquantes par `unknown`.

---

### Étape 3 : Calcul des anomalies de température

Référence utilisée : moyenne des températures enregistrées entre 1901 et 2000.

- **Anomalie = Température annuelle - Moyenne historique**
  - Anomalie positive → température supérieure à la moyenne historique.
  - Anomalie négative → température inférieure à la moyenne historique.

---

---

## II. Propositions de Solutions

### 1. Scénarios de Réduction des Émissions

| Scénario | Description                                           | Objectif climatique                                       |
| -------- | ----------------------------------------------------- | --------------------------------------------------------- |
| +1.5°C   | Scénario ambitieux avec neutralité carbone d’ici 2050 | Limite critique fixée par l’Accord de Paris               |
| +2°C     | Réduction progressive                                 | Risque d’impacts sévères mais gérables                    |
| +3°C     | Aucune action supplémentaire                          | Dérèglements majeurs : sécheresses, montée des eaux, etc. |

➡️ Ces scénarios permettent d’estimer l’impact des politiques climatiques sur les températures futures.

---

### 2. Propositions d’Actions Locales

| Domaine              | Action proposée                       | Impact attendu                             |
| -------------------- | ------------------------------------- | ------------------------------------------ |
| Mobilité             | Pistes cyclables, covoiturage         | Réduction des émissions liées au transport |
| Reforestation        | Planter des haies, arbres urbains     | Absorption du CO₂, biodiversité            |
| Sobriété énergétique | Réduction éclairage public, isolation | Réduction consommation et émissions        |
| Éducation            | Sensibilisation scolaire/associative  | Changements comportementaux durables       |

---

### 3. Impacts Potentiels des Actions

| Action               | Réduction estimée d’émissions (tonnes de CO₂/an) |
| -------------------- | ------------------------------------------------ |
| Mobilité douce       | 1 200                                            |
| Reforestation        | 800                                              |
| Sobriété énergétique | 1 500                                            |

➡️ Ces actions combinées peuvent réduire significativement les émissions à l’échelle locale.

---

## III. Solutions de Prévention pour le Changement Climatique

### 1. Synthèse des Observations Climatiques

| Observation                            | Explication                                    |
| -------------------------------------- | ---------------------------------------------- |
| Hausse des anomalies de température    | Températures récentes supérieures à la normale |
| Fréquence accrue d’événements extrêmes | Tornades, inondations plus fréquentes          |
| Variabilité interannuelle élevée       | Écarts marqués d’une année à l’autre           |
| Zones les plus touchées                | Sud et Midwest des USA                         |

➡️ Montre une intensification des phénomènes météorologiques liés au réchauffement.

---

### 2. Classification des Mesures : Atténuation vs Adaptation

| Type de mesure | Exemple concret                            | Objectif principal                            |
| -------------- | ------------------------------------------ | --------------------------------------------- |
| Atténuation    | Transition vers les énergies renouvelables | Réduire les émissions de gaz à effet de serre |
| Atténuation    | Efficacité énergétique des bâtiments       | Réduction de la consommation                  |
| Adaptation     | Création de digues, zones inondables       | Protection contre la montée des eaux          |
| Adaptation     | Changement de culture agricole             | Répondre aux nouvelles conditions climatiques |
| Adaptation     | Urbanisme résilient (ombrage, ventilation) | Réduction des effets des canicules            |

---

### 3. Propositions de Politiques de Prévention (par zone)

| Zone concernée        | Risques principaux               | Politiques recommandées                                    |
| --------------------- | -------------------------------- | ---------------------------------------------------------- |
| Sud des USA           | Tornades, vagues de chaleur      | Logements résistants, alertes, sensibilisation             |
| Midwest               | Inondations fluviales            | Aménagement berges, zones tampons, reforestation           |
| Zones urbaines denses | Îlots de chaleur                 | Espaces verts, toits végétalisés, réduction circulation    |
| Zones agricoles       | Sécheresse, rendements instables | Cultures résistantes, irrigation efficace, diversification |

---

## Conclusion

Ce projet met en lumière une augmentation notable des anomalies de température aux États-Unis sur la période étudiée, accompagnée d’une hausse des événements climatiques extrêmes. Les données révèlent l’urgence de politiques climatiques combinant **atténuation** et **adaptation**, ciblées selon les spécificités régionales.

Des actions locales concrètes — en matière de mobilité, d’efficacité énergétique ou de reforestation — peuvent jouer un rôle significatif. En croisant données climatiques et stratégies d’action, il est possible de proposer une réponse territorialisée au changement climatique, plus efficace et plus durable.
