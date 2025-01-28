# Projet Collaboratif : Landing Page et Documentation

Bienvenue dans ce projet collaboratif ! Vous allez travailler en groupes pour créer et enrichir un projet web. Voici les consignes et outils que vous utiliserez pour organiser et gérer efficacement le projet.

---

## **🚀 Objectif du Projet**

Chaque groupe travaillera sur une **landing page** et une page **documentation.html**, en utilisant un template que je vous ai fourni sur GitHub. Vous devrez collaborer en équipe pour personnaliser et améliorer ce projet tout en respectant les consignes suivantes.

---

## **📋 Méthodologie de Travail**

### 1. **Création du dépôt par le chef de projet**
1. Le **chef de projet** du groupe doit :
   - Accéder au template GitHub que je vous ai partagé.
   - Cliquer sur **"Use this template"** pour créer un dépôt pour le groupe.
   - Donner au dépôt un nom clair (ex. : `projet-groupe-1`).
   - Ajouter les membres du groupe comme **collaborateurs** au dépôt (dans les paramètres GitHub).

2. Une fois le dépôt créé, chaque membre peut cloner le projet sur sa machine.

---

### 2. **Utilisation de Live Share pour collaborer sur VSCode**

Pour collaborer en temps réel, vous utiliserez l’extension **Live Share** sur **Visual Studio Code (VSCode)**. Voici comment procéder :

#### Pour le chef de projet :
1. **Installer Live Share** :
   - Dans VSCode, allez dans l’onglet **Extensions** (icône de carré sur le côté gauche).
   - Recherchez **Live Share** et installez l’extension.

2. **Partager l’accès au projet** :
   - Ouvrez le projet dans VSCode.
   - Cliquez sur l’icône **Live Share** (généralement en bas à gauche).
   - Copiez le lien généré et partagez-le avec les membres du groupe.

3. **Activer le port 5500 pour Live Server** :
   - Ouvrez les paramètres de Live Share.
   - Autorisez l’accès au **port 5500** (port utilisé par l’extension Live Server).

#### Pour les autres membres du groupe :
1. Cliquez sur le lien Live Share partagé par le chef de projet.
2. Vous aurez accès au projet en temps réel, directement dans VSCode.
3. Si vous voulez visualiser le site localement, ouvrez le lien généré par **Live Server** et ajoutez `/<nomDuFichier.html>` dans l’URL pour accéder à d’autres fichiers. Par exemple :
   - `http://localhost:5500/index.html` pour la page d’accueil.
   - `http://localhost:5500/documentation.html` pour la page de documentation.

---

## **📂 Structure des Fichiers**

Voici les fichiers que vous devrez gérer dans ce projet :

```
/project-root
│
├── medias/            # Le dossier contenant toutes les images
├── index.html         # La landing page principale
├── documentation.html # La page dédiée à la documentation
├── style.css          # Le fichier de style principal (CSS)
├── script.js          # Le fichier JavaScript pour les interactions
└── README.md          # Ce fichier d'instructions
```

- **index.html** : La page principale du projet. Elle doit contenir un titre, des visuels attractifs, un appel à l’action, et des liens.
- **documentation.html** : Une page où vous présenterez des informations détaillées sur le projet (voir la partie "Documentation attendue").
- **style.css** : Tous les styles doivent être gérés ici, avec des **variables CSS** pour les couleurs, bordures, marges et espacements.
- **script.js** : Utilisé pour ajouter des fonctionnalités interactives au projet (par exemple : animations ou gestion des formulaires).

---

## **🎨 Utilisation des Variables CSS**

Pour garantir une cohérence dans le design, vous devez utiliser des **variables CSS** dans le fichier `style.css`. Ces variables doivent être définies pour au moins :

- Les couleurs principales (ex. : arrière-plan, texte, boutons).
- Les bordures (ex. : `border-radius` pour les coins arrondis).

### Exemple de déclaration et d’utilisation :

1. **Déclarer les variables CSS** :
   Les variables sont définies dans le sélecteur `:root` pour qu’elles soient accessibles partout dans le fichier CSS.

   ```css
   :root {
     --primary-color: #3498db; /* Couleur principale */
     --secondary-color: #2ecc71; /* Couleur secondaire */
     --border-radius: 10px; /* Rayon des bordures */
   }
   ```

2. **Utiliser les variables CSS** :
   Les variables sont appelées avec la fonction `var()` dans vos règles CSS.

   ```css
   body {
     background-color: var(--primary-color);
     color: var(--secondary-color);
   }

   button {
     border-radius: var(--border-radius);
     background-color: var(--primary-color);
     color: white;
   }
   ```

💡 **Astuce** : Si vous modifiez une variable dans `:root`, tous les éléments qui l’utilisent seront automatiquement mis à jour. Cela facilite grandement les ajustements de design.

---

## **📄 Documentation attendue (documentation.html)**

La page **documentation.html** doit contenir les sections suivantes :

1. **Contexte** : Expliquez pourquoi ce projet a été créé. Quel problème cherche-t-il à résoudre ?
2. **Cible** : Décrivez les utilisateurs visés (âge, profession, besoins, etc.).
3. **Service proposé** : Présentez les fonctionnalités ou services principaux du projet.
4. **Évolution** : Expliquez comment le projet pourrait être amélioré ou étendu à l’avenir.
5. **Avenir** : Parlez des opportunités ou des développements futurs pour ce projet.
6. **Contacter** : Ajoutez des informations de contact fictives pour le projet (ex. : email, réseaux sociaux).


---
## **🕵️‍♀️ Veille sur les Landing Pages**

### 1. **Objectif de la veille**
Vous devez faire des recherches pour comprendre ce qu’est une landing page réussie, quels éléments sont essentiels et quelles bonnes pratiques en design s’appliquent.

### 2. **Recherches à effectuer**
- **Éléments clés d’une landing page** :
  - Titre principal (headline) accrocheur.
  - Sous-titre explicatif.
  - Visuels ou images percutants.
  - Appel à l’action (CTA) clair et visible.
  - Témoignages ou preuves de confiance (facultatif).
  - Structure simple et lisible.
  **Exemple: https://yuka.io/**

- **Designs inspirants** :
  - Allez sur des plateformes comme **Dribbble** ou **Behance**.
  - Recherchez des exemples de landing pages et identifiez ce qui fonctionne bien en termes de design, typographie, couleurs et mise en page.
  **Liens:**
        
    - https://dribbble.com/
    - https://www.awwwards.com/
    - https://www.pinterest.fr/
    - https://www.behance.net/
    - https://www.lapa.ninja/category/app/

### 3. **Rapport de veille**
Après vos recherches, discutez avec votre groupe pour :
- Partager les exemples qui vous ont inspirés.
- Lister les éléments que vous souhaitez intégrer dans votre propre landing page.

---

## **💡 Conseils pour une bonne collaboration**

1. **Planifiez** : Avant de commencer, discutez des tâches à réaliser et attribuez-les à chaque membre du groupe.
2. **Communiquez** : Utilisez un outil comme Discord ou Teams pour rester en contact pendant le projet.
3. **Testez régulièrement** : Vérifiez que tout fonctionne bien sur Live Server à chaque étape.
4. **Respectez les conventions** :
   - Nommez les branches de façon explicite (ex. : `feature-navbar`).
   - Faites des commits clairs et descriptifs (ex. : "Ajout du menu dans le header").

---

## **✅ Checklist pour chaque groupe**

- [ ] Le chef de projet a créé le dépôt GitHub.
- [ ] Live Share est configuré et partagé avec le groupe.
- [ ] Chaque membre a accès au projet via Live Share.
- [ ] Les fichiers index.html, style.css, script.js et documentation.html sont complétés.
- [ ] La page documentation.html contient toutes les sections requises.
- [ ] Le projet est testé sur Live Server.

---


