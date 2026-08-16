# 📝 Commit Buddy

**Générez des messages de commit conventionnels en 2 clics.**

Commit Buddy est un petit outil Windows qui vous aide à écrire des messages `git commit` propres et professionnels, sans avoir à vous souvenir de la syntaxe.

---

## 🎯 Pourquoi cet outil ?

Quand on code, on a souvent la flemme d'écrire un beau message de commit. Résultat : on tape `"fix"`, `"wip"` ou `"toto"`. 
3 mois plus tard, on ne comprend plus rien dans l'historique du projet.

Commit Buddy vous force à structurer votre message avec la norme **Conventional Commits** :
> `type(scope): sujet`

---

## ✨ Fonctionnalités

- **7 types de commits** : `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`
- **Champ Scope** (optionnel) : pour préciser la partie du projet concernée.
- **Champ Sujet** : décrivez ce que vous avez fait en quelques mots.
- **Aperçu en direct** : voyez le message final avant de le copier.
- **Copie automatique** : le message est copié dans votre presse-papiers (Ctrl+V).
- **Icône dans la barre des tâches** : l'application reste discrète et s'ouvre en un clic.

---

## 🖥️ Installation et utilisation


📥 **Installation (application portable – aucune installation requise)**

1. Téléchargez le fichier `.zip`.
2. Extrayez le contenu du dossier.
3. Double-cliquez sur `CommitBuddy.exe` pour lancer l'application.

**Aucune bibliothèque ou prérequis supplémentaire n'est nécessaire.**
L'application fonctionne directement sur Windows 10 et 11.

**💡 Astuce :** Pour un démarrage automatique, placez un raccourci de l'`.exe` dans le dossier `Démarrage` de Windows (`Win + R` → `shell:startup`).



### Avec Python (si vous avez le code source)

1. Assurez-vous d'avoir Python installé.
2. Installez les dépendances :
   bash
   pip install pyperclip pystray Pillow


 disponible : https://itch.io/dashboard
