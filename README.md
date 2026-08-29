# ⚡ CDM TECH • DARKSEID 👑

> **Banner Tool for Termux — Dark • Hacker • Cyber Tech**

## 🛡️ Présentation

**CDM TECH / DARKSEID** est un outil Bash conçu pour **Termux** afin de personnaliser l'affichage du terminal avec des bannières stylées.

Le script propose plusieurs styles `figlet`, un nom personnalisé, des bannières personnalisées, un mode aléatoire et l'activation automatique de la bannière au démarrage de Termux.

## ✨ Fonctionnalités

- ⚡ Bannière **CDM TECH / DARKSEID**
- 🎨 **20 styles** de bannière
- ✏️ Nom de bannière personnalisable
- 🖥️ Création de bannière personnalisée
- 🎲 Mode aléatoire
- 🔄 Bannière persistante au démarrage de Termux
- 🧹 Activation / désactivation du mode persistant
- 📦 Installation automatique de `figlet`
- 🔴 Interface dark / hacker / cyber-tech
- 🛠️ Fonctionne directement depuis le terminal Termux

## 📂 Structure

```text
CDM-TECH-BANNER/
├── cdm_tech_darkseid_banner.sh
└── README.md
```

## 🚀 Installation rapide

### 1. Installer Git

```bash
pkg update -y
pkg install git -y
```

### 2. Cloner le dépôt

Remplace `TON-PSEUDO` par ton nom d'utilisateur GitHub :

```bash
git clone https://github.com/JAMESPRIME509/CDM-TECH-BANNER.git
```

### 3. Entrer dans le dossier

```bash
cd CDM-TECH-BANNER
```

### 4. Donner les permissions

```bash
chmod +x cdm_tech_darkseid_banner.sh
```

### 5. Lancer l'outil

```bash
./cdm_tech_darkseid_banner.sh
```

> 💡 Le script vérifie automatiquement les dépendances nécessaires et installe `figlet` si nécessaire.

## 🎛️ Menu principal

Une fois le programme lancé, tu peux choisir :

```text
╔══════════════════════════════════════════════════╗
║              ⚡ CDM TECH ⚡                       ║
║                 DARKSEID                          ║
╠══════════════════════════════════════════════════╣
║  [1]  DARKSEID                                  ║
║  [2]  CDM TECH                                  ║
║  [3]  CYBER TECH                                ║
║  [4]  HACKER MODE                               ║
║  [5]  TERMINAL KING                             ║
║  [6]  DARK TECH                                 ║
║  [7]  CDM XMD                                   ║
║  [8]  CDM DEV                                   ║
║  [9]  CDM SECURITY                              ║
║  [10] CDM BOSS                                  ║
║  [11] RANDOM                                    ║
║  [12] CHANGER LE NOM                            ║
║  [13] CRÉER MA PROPRE BANNIÈRE                  ║
║  [14] VOIR LES 20 STYLES                        ║
║  [15] ACTIVER AU DÉMARRAGE DE TERMUX            ║
║  [16] DÉSACTIVER LE MODE PERSISTANT             ║
║  [0]  EXIT                                      ║
╚══════════════════════════════════════════════════╝
```

## 👑 Bannière recommandée

Pour obtenir le style **CDM TECH / DARKSEID**, lance le programme puis choisis :

```text
1
```

Pour personnaliser le nom et le style :

```text
12
```

Pour afficher les différents styles :

```text
14
```

## 🔄 Démarrage automatique

Pour afficher automatiquement la bannière lorsque Termux démarre :

```text
15
```

Le script ajoute sa configuration au fichier `.bashrc` de l'utilisateur.

Pour désactiver cette fonction :

```text
16
```

## 🎨 Bannière personnalisée

Choisis :

```text
13
```

Puis écris ton texte ligne par ligne.

Pour terminer :

```text
END
```

Exemple :

```text
╔════════════════════════════╗
║       CDM TECH             ║
║       DARKSEID             ║
║       CYBER TERMINAL       ║
╚════════════════════════════╝
END
```

## ⚙️ Dépendances

Le projet utilise principalement :

- **Bash**
- **Termux**
- **Figlet**

`figlet` est installé automatiquement lorsqu'il n'est pas disponible.

## 🛠️ Résolution des problèmes

### Permission refusée

Exécute :

```bash
chmod +x cdm_tech_darkseid_banner.sh
```

Puis :

```bash
./cdm_tech_darkseid_banner.sh
```

### `figlet` introuvable

Tu peux l'installer manuellement :

```bash
pkg update -y
pkg install figlet -y
```

Puis relancer :

```bash
./cdm_tech_darkseid_banner.sh
```

### La bannière ne s'affiche plus au démarrage

Lance le script et utilise :

```text
15
```

pour réactiver le mode persistant.

## 🔐 Sécurité

Ce projet est un outil de personnalisation de terminal. Il ne nécessite pas de mot de passe, de clé API ou d'accès à un compte externe pour afficher les bannières.

Avant d'exécuter un script téléchargé depuis Internet, vérifie toujours son contenu et sa provenance.

## 📜 Licence

Tu peux adapter le projet à tes besoins et modifier le design, les textes et les styles.

## ⚡ CDM TECH

```text
╔══════════════════════════════════════════════╗
║                                              ║
║              ⚡ CDM TECH ⚡                   ║
║                 DARKSEID                     ║
║                                              ║
║          CODE • CREATE • CONTROL             ║
║                                              ║
╚══════════════════════════════════════════════╝
```

**© 2026 CDM TECH / DARKSEID**
