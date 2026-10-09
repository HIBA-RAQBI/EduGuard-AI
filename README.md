
# EduGuard AI – Hybrid RAG

## 1. Présentation du projet

EduGuard AI est une solution basée sur l'intelligence artificielle
qui permet aux utilisateurs de rechercher des informations éducatives
et d'obtenir des réponses à partir d'une base documentaire.

Le projet utilise une approche Hybrid RAG (Retrieval-Augmented
Generation) afin d'améliorer la pertinence des informations récupérées
et de générer des réponses contextualisées.

Le workflow est développé sur Fusion AI.

## 2. Problématique

Les utilisateurs rencontrent parfois des difficultés pour retrouver
rapidement des informations précises dans des documents éducatifs.
Les assistants IA classiques peuvent également produire des réponses
inexactes lorsqu'ils ne disposent pas d'un contexte documentaire fiable.

EduGuard AI vise à répondre à cette problématique en combinant
la recherche documentaire et la génération de réponses par IA.

## 3. Objectifs du projet

- Faciliter l'accès aux informations éducatives.
- Rechercher les passages les plus pertinents dans les documents.
- Combiner la recherche sémantique et la recherche lexicale.
- Générer des réponses à partir du contexte récupéré.
- Réduire les réponses non justifiées par les documents.
- Renforcer la sécurité et la fiabilité du système.

## 4. Use Case

### Acteur principal
Utilisateur recherchant une information éducative.

### Scénario principal
1. L'utilisateur pose une question sur un sujet éducatif.
2. Le système analyse la question.
3. Le module Hybrid RAG recherche les passages pertinents
   dans la base documentaire.
4. Les résultats sont classés afin de sélectionner le contexte utile.
5. Le modèle d'intelligence artificielle utilise ce contexte
   pour préparer une réponse.
6. La réponse est présentée à l'utilisateur.

### Résultat attendu
L'utilisateur reçoit une réponse claire et pertinente, fondée
sur les informations disponibles dans la base documentaire.

## 5. Architecture technique

Le workflow EduGuard AI est développé sur Fusion AI.

Architecture logique prévue :

Question utilisateur
        ↓
Analyse de la question
        ↓
Recherche documentaire hybride
        ↓
Fusion et classement des résultats
        ↓
Sélection du contexte pertinent
        ↓
Génération de la réponse par l'IA
        ↓
Réponse à l'utilisateur

Les composants exacts dépendent de la configuration finale
du workflow.

## 6. Principe du Hybrid RAG

Le Hybrid RAG combine deux approches de recherche :

- Recherche sémantique : recherche des passages proches du sens
  de la question.
- Recherche lexicale : recherche des mots-clés présents dans
  la question et les documents.

Les résultats peuvent ensuite être fusionnés et classés afin
de sélectionner les passages les plus utiles pour la génération
de la réponse.

## 7. Technologies utilisées

- Fusion AI : conception et exécution du workflow.
- Retrieval-Augmented Generation (RAG) : recherche augmentée
  par génération.
- Recherche hybride : recherche sémantique et lexicale.
- Modèle de langage (LLM) : génération des réponses.
- Base documentaire et système de stockage : à préciser selon
  la configuration réelle du projet.

## 8. Tests et validation

Les tests doivent vérifier :

- La compréhension des questions utilisateur.
- La pertinence des documents récupérés.
- La qualité de la réponse générée.
- La cohérence entre la réponse et les sources disponibles.
- Le comportement du système lorsqu'aucune information pertinente
  n'est trouvée.
- La protection des informations confidentielles.

## 9. Sécurité

- Ne pas exposer les clés API ou les identifiants.
- Limiter l'accès aux documents selon les autorisations.
- Éviter l'utilisation de données personnelles dans les tests.
- Vérifier que les réponses sont fondées sur le contexte récupéré.
- Prévoir une réponse de refus ou d'incertitude lorsque
  les informations disponibles sont insuffisantes.

## 10. Limites et perspectives

### Limites
La qualité des réponses dépend de la qualité des documents,
de la pertinence de la recherche et de la configuration du modèle.

### Perspectives
- Améliorer le classement des passages récupérés.
- Ajouter des références aux documents sources.
- Développer des tests automatiques de qualité.
- Renforcer les mécanismes de sécurité.
- Améliorer la gestion des questions sans réponse.

## 11. Environnement du projet

Le workflow principal est actuellement disponible sur Fusion AI.
Ce dépôt GitHub centralise la documentation du projet EduGuard AI.

Les fichiers exportés, les instructions de configuration et les
résultats de test pourront être ajoutés après vérification
de leur contenu et suppression des informations confidentielles.

## 12. Auteur et équipe

Projet : EduGuard AI
Formation : Agentic AI
Plateforme : Fusion AI
Équipe : Ayoub Abdelmoughit, Hiba Raqbi, Driss Larhrissi
Date : Octobre 2026
