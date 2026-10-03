# Guide d'utilisation de GitHub Codespaces

Ce tutoriel vous explique comment réaliser et tester le TP C++ directement dans votre navigateur grâce à **GitHub Codespaces**, sans rien installer sur votre machine.

---

## 1. Lancer un Codespace depuis votre dépôt

1. Rendez-vous sur la page de votre dépôt GitHub (tp_voiture).
2. Cliquez sur le bouton vert **`<> Code`**.
3. Sélectionnez l'onglet **Codespaces**.
4. Cliquez sur **Create codespace on main**.
5. Patientez quelques secondes : un environnement VS Code complet s'ouvre directement dans votre navigateur.

---

## 2. Explorer l'environnement

L'interface se divise en trois parties principales :
* **À gauche :** L'explorateur de fichiers (pour créer `CVoiture.h`, `CVoiture.cpp`, `main.cpp`, `.gitignore`).
* **Au centre :** L'éditeur de code.
* **En bas :** Le **Terminal Bash** sous Linux (utilisable exactement comme sur les postes de travail physiques).

---

## 3. Créer vos fichiers et compiler

1. Créez vos fichiers sources via l'explorateur à gauche ou directement dans le terminal :
   ```bash
   touch voiture.h voiture.cpp main.cpp .gitignore
