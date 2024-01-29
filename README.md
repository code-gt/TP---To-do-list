# TP - To-Do List interactive avec Tailwind CSS et JavaScript

![image](https://github.com/code-gt/TP---To-do-list/assets/120173004/20e9c58c-f629-4b2f-9c25-4b1c0676302c)

## **Objectif** :

- Créer un site web interactif permettant de gérer vos tâches (to-do list).
- Maîtriser les classes de style tailwindcss.
- Rendre votre site interactif grâce à javascript, notamment grâce à la gestion des évènements.

### **Étape 1 : Mise en place du projet**

1. Créez un nouveau dossier pour le projet.
2. Initialisez un fichier HTML (**`index.html`**) avec les balises de base.
3. Liez le fichier CSS de Tailwind CSS à votre fichier HTML.
4. Ajoutez les classes de base de Tailwind à votre fichier HTML.

### **Étape 2 : Structure HTML de base**

1. Ajoutez une zone pour la To-Do List.
2. Ajoutez un formulaire avec un champ de texte et un bouton pour ajouter des tâches.
3. Ajoutez une liste (**`<ul>`**) pour afficher les tâches.

### **Étape 3 : Stylisation avec Tailwind CSS**

1. Utilisez les classes Tailwind pour styliser la page de manière attrayante.
2. Faites en sorte que la liste des tâches ait une apparence agréable.

### **Étape 4 : JavaScript - Manipulation du DOM**

1. Récupérez les éléments du DOM nécessaires dans votre fichier JavaScript. (**QuerySelector**, **getElementById** etc …).

```jsx
const form = document.getElementById('todo-form');
const inputTask = document.getElementById('task');
const taskList = document.getElementById('task-list');
```

1. Créez une **fonction** pour ajouter une nouvelle tâche à la liste lorsque le formulaire est soumis.

### **Étape 5 : JavaScript - Gestion des événements**

1. Ajoutez un gestionnaire d'événements pour détecter le clic sur le bouton "Ajouter".

```jsx
form.addEventListener('submit', function (event){
// Exemple
```

1. Apprenez à récupérer la valeur du champ de texte et à l'ajouter à la liste des tâches.

### **Étape 6 : JavaScript - Ajout de fonctionnalités**

1. Ajoutez des fonctionnalités telles que la suppression d'une tâche et le marquage comme terminée.

```jsx
function removeTask(taskItem) {
  // Supprimez l'élément li de la liste des tâches
  taskList.removeChild(taskItem);
}
```

```jsx
function toggleTaskDone(taskItem) {
  // Ajoutez ou supprimez une classe pour indiquer que la tâche est terminée
  taskItem.classList.toggle('line-through');
}
```

1. Explorez des animations ou des transitions simples pour rendre l'interface plus attrayante.

## **Ressources** :

- [https://tailwindcss.com/docs/](https://tailwindcss.com/docs/installation)
- [https://developer.mozilla.org/fr/docs/Learn/JavaScript/Building_blocks/Events](https://developer.mozilla.org/fr/docs/Learn/JavaScript/Building_blocks/Events)

Et surtout, amusez-vous les codeurs ! 🚀
