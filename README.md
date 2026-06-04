# 🏀 ACA Basket — HoopTrack

Application web de gestion de l'équipe **Alpha Clichy Academy** (Clichy-sous-Bois, 93).  
Gérez l'effectif, les matchs, les feuilles de match et les statistiques de la saison.

---

## ✅ Ce que l'appli permet de faire

- **Joueurs** — ajouter, modifier, suivre les statuts (Actif, Blessé, Suspendu, Absent)
- **Matchs** — planifier les matchs, saisir les scores
- **Feuilles de match** — composer le groupe, titulaires / remplaçants
- **Évaluations** — noter chaque joueur après le match (/10)
- **Statistiques** — bilan de l'équipe et stats individuelles

---

## 🚀 Installation (étape par étape)

### Ce dont tu as besoin
- Un ordinateur (Windows, Mac ou Linux)
- Une connexion internet

---

### Étape 1 — Télécharger le projet

1. Clique sur le bouton vert **"Code"** en haut de cette page GitHub
2. Clique sur **"Download ZIP"**
3. Dézippe le fichier téléchargé sur ton bureau

---

### Étape 2 — Créer un hébergement gratuit

1. Va sur **[infinityfree.com](https://infinityfree.com)**
2. Crée un compte gratuit
3. Note bien :
   - Ton **nom de domaine** (ex: `monsite.infinityfreeapp.com`)
   - Ton **nom d'utilisateur FTP**
   - Ton **mot de passe FTP**
   - Le **serveur FTP** (ex: `ftpupload.net`)

---

### Étape 3 — Créer la base de données

1. Dans ton espace InfinityFree, clique sur **"MySQL Databases"**
2. Crée une nouvelle base de données, note :
   - Le **nom de la base** (ex: `epiz_12345_basketball`)
   - Le **nom d'utilisateur** (ex: `epiz_12345_user`)
   - Le **mot de passe**
   - Le **serveur MySQL** (ex: `sql200.infinityfree.com`)
3. Clique sur **"phpMyAdmin"**
4. Sélectionne ta base à gauche, clique sur **"Importer"**
5. Choisis le fichier `data/basketball.sql` dans le dossier dézippé
6. Clique sur **"Exécuter"**

---

### Étape 4 — Configurer la connexion

1. Dans le dossier dézippé, ouvre le fichier `includes/_linkpdo.php` avec le Bloc-notes
2. Remplace les valeurs par les tiennes :

$host = 'sql200.infinityfree.com';
$dbname = 'epiz_12345_basketball';
$user = 'epiz_12345_user';
$password = 'TON_MOT_DE_PASSE';

3. Enregistre le fichier

---

### Étape 5 — Envoyer les fichiers en ligne

1. Télécharge **FileZilla** (gratuit) : [filezilla-project.org](https://filezilla-project.org)
2. Ouvre FileZilla et connecte-toi :
   - **Hôte** : ton serveur FTP
   - **Identifiant** : ton nom d'utilisateur FTP
   - **Mot de passe** : ton mot de passe FTP
   - **Port** : 21
3. Dans la partie droite (serveur), va dans le dossier `htdocs`
4. Sélectionne tous les fichiers et glisse-les vers la droite

---

### Étape 6 — Se connecter

Ouvre ton navigateur et va sur ton adresse (ex: `monsite.infinityfreeapp.com`)

Identifiants par défaut :
- **Login** : `coach`
- **Mot de passe** : `basket`

> ⚠️ Change le mot de passe dès ta première connexion !

---

## 📄 Licence

Basé sur [HoopTrack v1](https://github.com/Jean-Alet/hooptrack_v1) — Licence CC BY-NC 4.0  
Adapté pour l'Alpha Clichy Academy (ACA Basket)
