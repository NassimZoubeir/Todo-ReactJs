# Todo List – React + TypeScript

Application de gestion de tâches développée avec **React**, **TypeScript** et **Vite**.

L'application permet de créer et gérer une liste de tâches avec différents niveaux de priorité. Les tâches sont sauvegardées automatiquement dans le navigateur grâce au `localStorage`.

## Fonctionnalités

* Ajouter une tâche
* Modifier une tâche
* Supprimer une tâche
* Définir une priorité :

  * 🔴 Urgente
  * 🟠 Moyenne
  * 🟢 Basse
* Marquer une tâche comme terminée
* Filtrer les tâches
* Sauvegarder les tâches dans le `localStorage`

## Technologies utilisées

* **React**
* **TypeScript**
* **Vite**
* **CSS**
* **LocalStorage**

## Installation

Cloner le repository :

```bash
git clone <URL_DU_REPOSITORY>
```

Se rendre dans le dossier du projet :

```bash
cd todo-reactjs
```

Installer les dépendances :

```bash
npm install
```

Lancer le projet :

```bash
npm run dev
```

L'application sera ensuite accessible à l'adresse indiquée par Vite dans le terminal.

## Structure du projet

```text
src/
├── App.tsx
├── TodoItem.tsx
├── main.tsx
└── ...
```

## Ce que j'ai pratiqué

Ce projet m'a permis de pratiquer plusieurs notions de React et TypeScript :

* Gestion des états avec `useState`
* Gestion des effets avec `useEffect`
* Création et utilisation de composants React
* Gestion des événements et des formulaires
* Gestion des types avec TypeScript
* Filtrage des tâches
* Persistance des données avec `localStorage`

## Objectif

Ce projet a été réalisé dans le but de renforcer mes bases en **React et TypeScript** à travers une application simple et concrète, tout en découvrant progressivement la gestion des composants, des états et des données persistantes.
