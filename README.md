# 📱 Application Calculateur d'IMC

Cette application Android permet de calculer l'Indice de Masse Corporelle (IMC) en fonction du poids et de la taille saisis par l'utilisateur. Elle affiche également une catégorie (Maigreur, Normal, Surpoids, Obésité) avec une image descriptive.

## ✅ Fonctionnalités

- 🧮 Calcul automatique de l’IMC
- 📊 Affichage de la catégorie d’IMC
- 🖼️ Image correspondante à chaque catégorie
- ✅ Vérification de la validité des entrées utilisateur

## 🔧 Technologies utilisées

- Java
- Android SDK
- XML (UI Layouts)

## 🖼️ Interface utilisateur

- `EditText` pour le poids et la taille
- `Button` pour lancer le calcul
- `TextView` pour afficher l’IMC et la catégorie
- `ImageView` pour afficher l’image associée à la catégorie

## 📷 Exemple de catégories affichées

| Catégorie   | IMC               | Image         |
|-------------|-------------------|---------------|
| Maigreur    | < 18.5            | maigre.png    |
| Normal      | 18.5 - 24.9       | normal.png    |
| Surpoids    | 25 - 29.9         | surpoids.png  |
| Obésité     | ≥ 30              | tobese.png    |

## 🧪 Tester l'application

1. Ouvre le projet dans Android Studio.
2. Assure-toi d’avoir les images suivantes dans `res/drawable/` :
  - `maigre.png`
  - `normal.png`
  - `surpoids.png`
  - `tobese.png`
3. Lance l’application sur un émulateur ou un appareil Android réel.
4. Saisis un poids et une taille, puis clique sur le bouton **Calculer**.

## 📂 Structure simplifiée
```` bash
com.example.myapplication/
├── MainActivity.java
├── res/
│ ├── layout/activity_main.xml
│ ├── drawable/
│ │ ├── maigre.png
│ │ ├── normal.png
│ │ ├── surpoids.png
│ │ └── tobese.png
│ └── values/strings.xml
````
## 👨‍💻 Auteur

**Abdelkarim El Hajbi**  
[🔗 LinkedIn](https://www.linkedin.com/in/abdelkarim-el-hajbi) • [💻 GitHub](https://github.com/abdelkarimelhajbi)

---

