Win95-francejpg-retro-theme

Voici un exemple de fichier `README.md` pour le projet **Win95-francejpg-retro-theme**, fidèle à l’image et à l’esprit rétro Windows 95 :

---

# Win95-francejpg-retro-theme

Un thème Visual Studio Code inspiré de l’esthétique Windows 95 et de la carte de France pixelisée, clin d’œil au réseau cuivre en voie de disparition. Plongez dans une ambiance rétro et vintage, avec des couleurs fidèles à l’image « France.jpg » !

---

## Aperçu

Aperçu du thème

---

## Palette de couleurs

| Élément                   | Couleur    | Description                                 |
|---------------------------|------------|---------------------------------------------|
| Fond global               | #238b8b    | Vert canard rétro                           |
| Fenêtre                   | #c0c0c0    | Gris clair Windows 95                       |
| Barre de titre            | #000080    | Bleu marine                                 |
| Texte barre de titre      | #ffffff    | Blanc                                       |
| Zone principale (carte)   | #0000a0    | Bleu vif                                    |
| Points carte              | #00ff00    | Vert fluo                                   |
| Texte principal           | #222222    | Gris très foncé                             |
| Fond encadré texte        | #f8f8d8    | Jaune pâle (pour notifications/info)         |

---

## Installation

1. **Téléchargez ou clonez ce dépôt :**
   ```bash
   git clone https://github.com/valorisa/Win95-francejpg-retro-theme.git
   ```

2. **Copiez le dossier du thème dans vos extensions VSCode :**
   ```
   C:\Users\<VotreNomUtilisateur>\.vscode\extensions\win95-francejpg-retro-theme\themes\
   ```
   (Remplacez `<VotreNomUtilisateur>` par votre nom d’utilisateur Windows, par exemple `bbrod`.)

3. **Placez le fichier de thème** (ex : `win95-francejpg-retro-color-theme.json`) dans le dossier `themes`.

4. **Ajoutez la déclaration dans le `package.json`** de l’extension locale :

   ```json
   "contributes": {
     "themes": [
       {
         "label": "Win95 FranceJPG Retro",
         "uiTheme": "vs-dark",
         "path": "./themes/win95-francejpg-retro-color-theme.json"
       }
     ]
   }
   ```

5. **Relancez VSCode**, puis sélectionnez le thème dans :  
   `Préférences > Thème de couleurs > Win95 FranceJPG Retro`

---

## Utilisation rapide (sans extension)

Vous pouvez aussi appliquer la palette directement via les paramètres utilisateur VSCode (`settings.json`) :

```json
"workbench.colorCustomizations": {
  "editor.background": "#0000a0",
  "editor.foreground": "#00ff00",
  "activityBar.background": "#000080",
  "sideBar.background": "#238b8b",
  "statusBar.background": "#000080",
  "tab.activeBackground": "#c0c0c0",
  "tab.inactiveBackground": "#c0c0c0",
  "titleBar.activeBackground": "#000080",
  "titleBar.activeForeground": "#ffffff",
  "titleBar.inactiveBackground": "#c0c0c0",
  "titleBar.inactiveForeground": "#222222"
},
"editor.tokenColorCustomizations": {
  "comments": "#222222",
  "keywords": "#00ff00",
  "strings": "#00ff00",
  "numbers": "#00ff00",
  "functions": "#00ff00",
  "variables": "#f8f8d8"
}
```

---

## Inspiration

> Le réseau cuivré d’un million de kilomètres va disparaître petit à petit, pour laisser la place à la fibre.

Ce thème rend hommage à l’ère du cuivre et à l’esthétique Windows 95, pour coder avec une touche de nostalgie française.

---

## Contribution

Suggestions, issues et pull requests sont les bienvenus !

---

## Licence

MIT

---

**Bon voyage rétro dans le code ! 🇫🇷**

Citations :
[1] Screenshot_2025-04-20-00-28-18-71_40deb401b9ffe8e1df2f1cc5ba480b12.jpg https://pplx-res.cloudinary.com/image/upload/v1745102050/user_uploads/HCvrHPfhZolCPxP/Screenshot_2025-04-20-00-28-18-71_40deb401b9ffe8e1df2f1cc5ba480b12.jpg
[2] Windows 95 s'invite sur iOS avec ce thème rétro bluffant - Korben https://korben.info/theme-windows-95-ios-personnalisation-retro.html
[3] Windows 95 icons - Etsy France https://www.etsy.com/fr/market/windows_95_icons
[4] Windows 95 - Etsy France https://www.etsy.com/fr/market/windows_95
[5] Thèmes pour Windows 95 - Win3x.Org http://www.win3x.org/win3board/viewtopic.php?t=18129
[6] Icône Windows-95 dans le style Windows 11 Color - Icons8 https://icones8.fr/icon/mdhenbUr2yHg/windows-95
[7] Windows 95 - Images et vidéos libres de droits - Adobe Stock https://stock.adobe.com/be_fr/search?k=windows+95
[8] Icônes, logos, symboles Windows 95 - Icons8 https://icones8.fr/icons/set/windows-95
[9] GRUB theme based on the classic appearance of Windows 95 https://github.com/a1ive/grub-theme-win95
[10] Des réflexions sur mon ricing KDE sur le thème rétro de Windows https://www.reddit.com/r/kde/comments/17mprbx/thoughts_on_my_retrowindowsthemed_kde_ricing/?tl=fr
[11] Pink Windows 95 Aesthetic - Pinterest https://www.pinterest.com/ideas/pink-windows-95-aesthetic/929878642630/
