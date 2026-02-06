# Consigne — Kubernetes : prise en main et déploiement applicatif

Dans cette série d’exercices, vous allez découvrir Kubernetes de manière progressive, en partant des concepts fondamentaux jusqu’au déploiement complet d’une application avec base de données.

Le travail est découpé en **deux exercices complémentaires** :

* le premier se concentre sur la **prise en main de kubectl**, les **Pods** et les **Deployments** ;
* le second vous amène à déployer une **application réelle** avec **PostgreSQL**, en introduisant les notions de **persistance**, **Secrets**, **Services** et **Ingress**.

Chaque exercice dispose de sa **consigne détaillée** à suivre pas à pas.

---

## Exercice 1 — Bases Kubernetes (Pods & Deployments)

Objectif :
Découvrir Kubernetes à travers la manipulation de Pods et de Deployments, comprendre leur rôle et observer leur comportement (cycle de vie, labels, rescheduling, accès via port-forward).

👉 Consigne détaillée : **`k8s_1.md`**

---

## Exercice 2 — Déploiement d’une application complète (Peppermint + PostgreSQL)

Objectif :
Déployer progressivement une application complète en mettant en évidence :

* la différence entre Pod et Deployment,
* la nécessité de la persistance pour une base de données,
* l’utilisation des PVC, Secrets et Services,
* l’exposition d’une application via un Ingress NGINX.

👉 Consigne détaillée : **`k8s_2.md`**

---

### Règles générales

* Exécutez les commandes dans l’ordre indiqué.
* Observez attentivement les sorties (`get`, `describe`, `logs`).
* En cas de doute sur un concept, appuyez-vous sur la documentation Kubernetes associée.
