# 🚀 CKILFO Token Dashboard - Interface Web BSC Testnet

Bienvenue sur le **tableau de bord public du token CKILFO**, déployé sur la Binance Smart Chain Testnet. Cette application permet de surveiller, gérer et interagir en toute simplicité avec le **smart contract CKF**.

---

## 🔎 Description complète

**CKILFO Token Dashboard** est une interface web intuitive permettant d'interagir avec le smart contract CKILFO déployé sur la Binance Smart Chain Testnet.  
Elle offre aux utilisateurs les fonctionnalités essentielles pour surveiller et gérer le token **CKF** :

### ⚙️ Fonctionnalités principales :
- 📊 **Affichage en temps réel du Total Supply**
- 👛 **Vérification du solde** d’un portefeuille en quelques secondes
- 🔐 **Connexion sécurisée via Metamask**
- 🎁 **Fonction de mint** (création de tokens vers une adresse choisie)
- 💸 **Fonction de transfert** entre portefeuilles
- 🎯 **Redirection automatique** vers le dashboard premium si le solde est suffisant (≥ 1000 CKF)
- 💎 **Zone Premium débloquée** en fonction du solde du wallet connecté
- 🧪 **Page de test des fonctions CKF** : balanceOf, transfer, mint disponibles via `tester.html`

### 🔗 Informations intégrées :
- 🔄 Adresse **Proxy (UUPS)** du contrat
- 🔧 Adresse **d’implémentation vérifiée**
- ✅ Lien vers le **code source vérifié sur BscScan**
- 🛡️ Badge de vérification BscScan

### 🔐 Sécurité :
- Vérification d'adresse avant toute transaction
- Signature obligatoire via Metamask pour les fonctions sensibles
- Appels blockchain via **Ethers.js**
- 🧭 Vérification automatique du réseau (BSC Testnet uniquement)

### 🧰 Technologies utilisées :
- HTML / CSS
- JavaScript + [ethers.js](https://docs.ethers.org/)
- Metamask (Web3 Provider)

---

## 📦 Détails du jeton

| Propriété         | Valeur                            |
|-------------------|------------------------------------|
| Nom du jeton      | Jeton CKILFO                      |
| Symbole           | CKF                               |
| Réseau            | Binance Smart Chain - Testnet     |
| Offre totale      | Affiché en live dans le dashboard |

---

## 📄 Pages disponibles

| Page              | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `index.html`       | Page d'accueil – connexion wallet + redirection premium                    |
| `premium.html`     | Dashboard réservé aux détenteurs de ≥ 1000 CKF                             |
| `tester.html`      | Interface pour tester manuellement les fonctions du contrat                |

---

## 🔗 Liens utiles

- 🔍 [Contrat Proxy (CKILFO) sur BscScan](https://testnet.bscscan.com/address/0xABEa3d1c6BE1692d6559a59Ff3d9C4A17C012EfD)
- 🔧 [Implémentation vérifiée](https://testnet.bscscan.com/address/0x3D4fec067a565966294f7df0E415C828ec2Cc2C9)
- 🌐 [Dashboard CKILFO en ligne (GitHub Pages)](https://ckilfo.github.io/ckilfo-dashboard/index.html)
- 📘 [Code source complet du dashboard](./index.html)

---

## ✨ Fonctionnalités prévues

- ✅ Affichage dynamique de `totalSupply()`
- ✅ Vérification de `balanceOf()` par wallet
- 🛠️ Mint contrôlé via la fonction `mint()` réservée à l'owner
- ✅ Accès conditionné à la zone premium basé sur le solde CKF
- ✅ Redirection automatique si solde ≥ 1000 CKF
- ✅ Interface de test directe pour balance, transfert, mint
- 📄 Ajout d’un **livre blanc** (whitepaper PDF)
- 🔒 Intégration future avec outils de sécurité (audit, multisig...)

---

## 📜 Licence

Ce projet est open source, publié sous licence **MIT**.
