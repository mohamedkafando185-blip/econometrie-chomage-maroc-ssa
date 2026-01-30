# 🏠 UniLoge Maroc – Système de Gestion Immobilière Étudiant

![Odoo](https://img.shields.io/badge/Platform-Odoo%2017-875A7B?logo=odoo&logoColor=white)
![Status](https://img.shields.io/badge/Status-Version%20Acad%C3%A9mique-success)
![License](https://img.shields.io/badge/License-Éducative-blue)

**UniLoge Maroc** est une plateforme web complète de gestion immobilière, spécialement conçue pour faciliter la recherche et la location de logements étudiants au Maroc. Développée sous **Odoo 17**, cette solution automatise et centralise l’ensemble des processus d’une agence immobilière moderne.



---

## 📋 Présentation du Projet
UniLoge Maroc intègre de manière fluide plusieurs modules métiers (CRM, Site Web, RH, Comptabilité) pour offrir une expérience numérique fluide, depuis la recherche de logement jusqu’au suivi des paiements.

🔗 [Live Demo](https://147066723.hs-sites-eu1.com/unilogemaroc) | 📄 [Documentation détaillée](Rapport_SI.pdf) | 👥 **Équipe : Groupe 7**

### 🎯 Objectifs & Valeurs Ajoutées
* **Centraliser** l’offre et la demande en une seule interface.
* **Automatiser** les leads, contrats, et la facturation.
* **Faciliter** la communication (Étudiants / Propriétaires / Gestionnaires).
* **Traçabilité** totale grâce aux outils RH intégrés.

---

## 🛠️ Architecture Technique

### 📦 Modules Odoo utilisés
| Module | Rôle dans le projet |
| :--- | :--- |
| **CRM** | Gestion des leads, opportunités et pipeline commercial. |
| **Site Web** | Portail client et formulaires interactifs. |
| **Contacts** | Base de données centralisée (Étudiants, Propriétaires). |
| **Calendrier** | Planification et rappels automatiques des visites. |
| **Applicéo** | Gestion locative (biens, contrats, loyers, facturation). |
| **RH** | Gestion des employés, congés, paie et évaluations. |

### 🔄 Flux de données
1. **Acquisition :** Formulaire Web → Création automatique du Contact.
2. **Vente :** Opportunité CRM → Matching automatique Offre/Demande.
3. **Opération :** Planification visites (Calendrier).
4. **Contractualisation :** Signature bail + Facturation (Applicéo).
5. **Back-Office :** Suivi RH + Paie (Module Employés).



---

## ✨ Fonctionnalités Clés

### 🧑‍💻 Espace Public (Site Web)
* Formulaires intelligents pour étudiants et propriétaires.
* Interface responsive et intuitive.

### 📇 Gestion Relation Client (CRM)
* Filtrage et matching par localisation et budget.
* Pipeline de vente structuré par étapes.

### 📑 Gestion Locative (Applicéo)
* Génération automatisée des **contrats de bail en PDF**.
* Facturation récurrente et quittances automatiques.

### 👥 Gestion des Ressources Humaines
* Gestion des salaires, congés et absences.
* Génération automatique des bulletins de paie.

---

## 🧠 Compétences Développées

### 🔧 Techniques
- **Paramétrage Odoo :** Automation des workflows et personnalisation de modèles.
- **Intégration :** Synchronisation CRM ↔ Calendrier ↔ Facturation.
- **Serveur SMTP :** Configuration Gmail pour envois automatisés.
- **Data :** Import/Export et structuration de bases de données Excel.

### 🧩 Fonctionnelles & Soft Skills
- Conception de systèmes intégrés (SI).
- Travail en équipe agile et gestion des délais (cycle de 1 semestre).
- Résolution de problèmes techniques complexes.


## 🚧 Défis Relevés & Solutions

| Défi | Solution |
| :--- | :--- |
| **Synchronisation Web/Contact** | Ajustement des mappings de champs dans Odoo. |
| **Envoi d’e-mails local** | Configuration d'un relais SMTP Gmail externe. |
| **Matching Offres/Demandes** | Mise en place de filtres dynamiques et vues segmentées. |
| **Limites Odoo Community** | Utilisation de champs calculés pour étendre les fonctions. |

---

## 📈 Perspectives d’Évolution
- 🗺️ **Géolocalisation :** Visualisation des logements sur carte.
- 📱 **App Mobile :** Version dédiée Android/iOS.
- 🤖 **Chatbot AI :** Support automatique pour les questions fréquentes.
- ☁️ **Cloud Deployment :** Migration vers Odoo.sh ou AWS.

---

## 👨‍🎓 Équipe du Projet – Groupe 7

| Membre | Rôle | Contribution |
| :--- | :--- | :--- |
| **ABOUBAKAR Abdelaziz** | Formulaires Web | Intégration data et interface publique. |
| **DIN Isaac Kaougahi** | Gestion Locative | Paramétrage Applicéo et facturation. |
| **KAFANDO Mohamed** | RH & Paie | Configuration RH et cycles de paie. |
| **ZOUNGRANA Abdoul G.** | CRM & Automates | Workflow, SMTP et Calendrier. |

---

## 📬 Contact
Si ce projet vous intéresse, n'hésitez pas à nous contacter !

**"Du besoin utilisateur à la solution logicielle intégrée – toute la chaîne de valeur dans un seul projet."**

---
*Ce projet a été réalisé dans un cadre académique (2025–2026) à des fins pédagogiques.*
