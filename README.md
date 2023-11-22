# Projet e-Voting avec Blockchain

Ce projet constitue une implémentation d'une application de vote en ligne utilisant la technologie Blockchain Ethereum. Le développement de cette application a été réalisé dans le cadre d'un Travaux Pratiques sous la supervision de M. Yousfi Souheib en Novembre 2023.

## Objectif

L'objectif de ce projet était de créer un système de vote transparent, sécurisé et décentralisé en exploitant les fonctionnalités offertes par la technologie Blockchain. Nous avons utilisé des outils tels que Truffle, Ganache, et MetaMask pour configurer notre environnement de développement et déployer notre contrat intelligent.

## Instructions d'Installation

1. **Prérequis**
   - Node.js et NPM : [https://nodejs.org](https://nodejs.org)
   - Truffle Framework : [https://www.trufflesuite.com](https://www.trufflesuite.com)
   - Ganache : [http://truffleframework.com/ganache/](http://truffleframework.com/ganache/)
   - MetaMask Ethereum Wallet : [https://metamask.io/](https://metamask.io/)

2. **Clonage du Répertoire**
```bash
   git clone https://github.com/fatma-laribi/TP-e-voting-blockchain.git
```


3. **Installation des Dépendances**
```bash

    cd e-voting-blockchain
    npm install
```
4. **Configuration de Ganache**
Lancez Ganache et configurez-le pour utiliser le même port que spécifié dans le projet.

5. **Déploiement du Contrat Intelligent**
```bash
    truffle migrate
```
6. **Lancement de l'Application**
```bash
    npm run dev
```

7. **Importation du Compte dans MetaMask**
Copiez la clé privée d'un compte Ganache.
Importez le compte dans MetaMask sur le réseau configuré.

## Test de l'Application
1. Accédez à l'application via http://localhost:3000
2. Connectez-vous avec MetaMask.
3. Votez pour un candidat.
4. Confirmez la transaction dans MetaMask.

## Structure du Projet
- **contracts/** : Contient le contrat intelligent Election.sol.
- **migrations/** : Fichiers de migration pour déployer le contrat.
- **test/** : Fichiers de test pour le contrat.
- **src/** : Contient le code source de l'interface utilisateur.


## Conclusion
Ce projet a fourni une expérience pratique dans le développement d'une application de vote décentralisée. N'hésitez pas à explorer le code source et à contribuer à son amélioration !

Auteurs : Fatma Laribi, Soulaima Kahla, Raoua Trimech