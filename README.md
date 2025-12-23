# Flutter Styling & Theme App

Application Flutter démontrant l’utilisation correcte des **thèmes**, **styles globaux**, **Drawer avec avatar**, et **navigation multi-pages** selon les bonnes pratiques.

---

## Objectifs du projet

- Centraliser les couleurs et les styles
- Utiliser un **ThemeData global**
- Implémenter un **Drawer personnalisé**
- Navigation entre plusieurs pages
- Organisation professionnelle du projet Flutter

---

## Structure du projet

lib/
├── main.dart
├── theme/
│ ├── app_colors.dart
│ └── app_theme.dart
├── pages/
│ ├── home_page.dart
│ ├── profile_page.dart
│ ├── settings_page.dart
│ └── about_page.dart
├── widgets/
│ └── app_drawer.dart
assets/
└── avatar.jpg


---

## Thème & Couleurs

- **Primary color** : utilisé dans la AppBar
- **Secondary color** : utilisé dans le Drawer
- Couleurs centralisées dans `AppColors`

---

## 📂 Assets

L’image de profil est stockée dans : assets/avatar.jpg

Et déclarée dans `pubspec.yaml` :

```yaml
flutter:
  assets:
    - assets/avatar.jpg
```
## 📸 Captures d’écran
### Page Accueil
Emplacement du fichier :
home_page.png

<img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/9bf6175f-f150-48cf-a993-347cd5227744" />

### Page Profil

Emplacement du fichier :
profile_page.png

<img width="1919" height="904" alt="image" src="https://github.com/user-attachments/assets/3aae2780-3165-42f7-91d5-67f6430c548a" />

### Page Paramètres

Emplacement du fichier :
settings_page.png

<img width="1918" height="910" alt="image" src="https://github.com/user-attachments/assets/c3ee5b19-6e2d-43cd-9302-4ee6e9917eea" />

### Page À propos
Emplacement du fichier :
about_page.png

<img width="1919" height="902" alt="image" src="https://github.com/user-attachments/assets/615df665-fe2f-4289-b09f-1fb665cf44cb" />

### Drawer (Menu latéral)

<img width="1919" height="914" alt="image" src="https://github.com/user-attachments/assets/e280b3a1-a89f-49d0-bbf1-4dca31eb3d8d" />

Lancer le projet
```
flutter pub get
flutter run
```

## Auteur

Nom : Ayoub Faradi

Formation : Licence Développement Logiciel – Mundiapolis

Technologie : Flutter


