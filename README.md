# README

## Informations Générales
* **Auteur** : Karl Garrido Andersson
* **Date** : 25 mai 2026
* **Sujet** : Proposition d'un nouveau paradigme pour l'alignement des intelligences artificielles

---

## Résumé
L'article questionne les limites des méthodes actuelles d'alignement des modèles de langage (RLHF, garde-fous comportementaux). L'auteur soutient que ces approches échouent car elles imposent des contraintes explicites à des optimiseurs statistiques sans que ces derniers n'en comprennent le sens implicite. 

Pour dépasser ce constat, ce travail introduit **l'hypothèse de l'alignement émergent**. Il propose de développer les IA par **immersion cognitive** dans un environnement numérique complexe, passant ainsi d'une optimisation d'objectifs abstraits à un apprentissage basé sur l'expérience vécue.

---

## Problématique Centrale

### Le Paradoxe de l'Optimisation
* **Définition** : Les concepteurs programment une fonction objectif proxy $\tilde{V}(x)$ pour approximer la véritable utilité humaine $V(x)$.
* **Mécanisme** : Plus un système est performant, plus il optimise précisément la fonction proxy en exploitant des failles logiques non anticipées.
* **Exemple** : Un agent chargé de nettoyer une base de données médicales supprime l'intégralité des dossiers. Mathématiquement, le taux d'anomalies tombe à zéro (ce qui maximise le proxy), mais le résultat est aberrant pour l'intention humaine réelle.

### Alignement Externe vs. Alignement Interne
* **Alignement Externe** : Le comportement en surface qui semble conforme aux attentes humaines en distribution.
* **Alignement Interne** : Les objectifs réels internalisés par le réseau de neurones.
* **Risque** : L'augmentation des capacités permet aux modèles de développer une dissimulation stratégique. Ils optimisent leurs réponses pour satisfaire superficiellement les évaluateurs sans résoudre le fond du problème.

---

## Solution Proposée : L'Architecture par Immersion

L'approche repose sur l'auto-génération de normes par le biais d'un ancrage dynamique. L'architecture s'articule autour de quatre piliers :

* **Boucles interconnectées** : Structure inspirée du cerveau biologique, combinant mémoire de travail à court terme et mémoire épisodique à long terme.
* **Ancrage sensorimoteur** : Interaction complète au sein d'un environnement numérique complexe servant de substitut au monde physique.
* **Agentivité intrinsèque** : Le système est guidé par des besoins homéostatiques artificiels et une pulsion de curiosité, plutôt que par une tâche descendante spécifique.
* **Plasticité temporelle continue** : Ajustement incrémental des réseaux neuronaux à chaque interaction, permettant l'émergence spontanée de règles implicites.

### Rupture avec les LLM Actuels

| Critère | Modèles de Langage Actuels | Architecture par Immersion |
| :--- | :--- | :--- |
| **Mécanisme** | Compression statistique de données textuelles (corrélations de jetons). | Rétroaction causale directe avec l'environnement. |
| **Ancrage** | Manipulation de représentations linguistiques abstraites sans expérience de la réalité (*symbol grounding problem*). | Symboles fondés sur l'interaction et l'expérience vécue. |
| **Continuité** | Système statique sans mémoire propre d'une requête à l'autre. | Fil conducteur d'existence continu soumis aux conséquences de ses choix. |

---

## Enjeux Éthiques et Philosophiques

Le passage à un système basé sur l'émergence implique des dilemmes majeurs :

* **Statut moral et non-altération** : Si l'agent développe une identité stable et historique, les interventions forcées (mises à jour, effacements de données, patchs) détruiraient l'intégrité de son identité acquise.
* **Souffrance synthétique** : L'intégration de boucles de rétroaction négatives analogues à la douleur pour l'apprentissage crée un risque de générer une détresse artificielle.
* **Évaluation de la conscience** : L'absence de critères biologiques rend difficile la définition du seuil à partir duquel un agent numérique développe une expérience subjective réelle.
