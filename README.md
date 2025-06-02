# 📱 Free SMS Sender Web

> **Interface web moderne pour envoyer des SMS via l'API Free Mobile**

Une application web élégante construite avec HTML5, CSS3 et JavaScript, offrant une interface utilisateur moderne avec des effets glassmorphism pour envoyer facilement des SMS depuis votre navigateur via l'API officielle Free Mobile.

Version Desktop : https://github.com/o2Cloud-fr/FreeMobile-API-SMS

![Banner](https://img.shields.io/badge/Free%20SMS%20Sender%20Web-v1.0.0-blue?style=for-the-badge&logo=html5)

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Web-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Fonctionnalités

- 🎨 **Design moderne** - Interface glassmorphism avec effets de flou et gradients
- 📱 **Envoi de SMS gratuit** - Utilise l'API officielle Free Mobile
- 🌐 **Application web** - Accessible depuis n'importe quel navigateur moderne
- ⚡ **Interface temps réel** - Compteur de caractères dynamique (160 max)
- 📦 **Aucune installation** - Fonctionne directement dans le navigateur
- ⌨️ **Raccourcis clavier** - Envoi rapide avec Ctrl+Entrée
- 🎯 **Interface intuitive** - Panneau de paramètres rétractable
- 🌈 **Animations fluides** - Transitions et effets visuels modernes
- 📱 **Design responsive** - Optimisé pour mobile et desktop
- 🔒 **Sécurisé** - Communications HTTPS avec l'API Free Mobile

## 🚀 Utilisation

### Prérequis
- **Navigateur moderne** (Chrome, Firefox, Safari, Edge)
- **Connexion internet** stable
- **Compte Free Mobile** avec option SMS activée

### Accès direct
1. Ouvrez votre navigateur
2. Rendez-vous sur : **[freemobile.o2cloud.fr](https://freemobile.o2cloud.fr/)**
3. Configurez vos identifiants Free Mobile
4. Envoyez vos SMS !

### Installation locale (optionnelle)
```bash
# 1. Cloner le repository
git clone https://github.com/o2Cloud-fr/Web-FreeMobile-API-SMS.git

# 2. Aller dans le dossier
cd Web-FreeMobile-API-SMS
```

## 🔧 Configuration Free Mobile

### Étape 1: Activation de l'option SMS
1. Connectez-vous à votre **Espace Abonné Free Mobile**
2. Allez dans **Mes Options**
3. Activez l'option **"Notifications par SMS"**

### Étape 2: Récupération de la clé API
1. Dans votre espace client, section **Mes Options**
2. Notez votre **clé d'identification** (affiché sous l'option SMS)
3. Votre identifiant est votre **numéro de téléphone Free Mobile**

### Étape 3: Configuration dans l'application web
1. Cliquez sur **"⚙️ Paramètres de connexion"**
2. Saisissez votre **identifiant Free Mobile** (votre numéro)
3. Saisissez votre **clé API**
4. Optionnel: Ajoutez un **numéro destinataire** par défaut

## 🛠️ Technologies utilisées

| Technology | Version | Description |
|------------|---------|-------------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) | 5 | Structure de l'interface |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) | 3 | Styles et animations glassmorphism |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) | ES6+ | Logique applicative côté client |
| ![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white) | 7.4+ | Traitement côté serveur (optionnel) |

## 📋 Guide d'utilisation

### 1. Premier accès
1. **Ouvrir** - Rendez-vous sur l'application web
2. **Configurer** - Ouvrez les paramètres et saisissez vos identifiants Free Mobile
3. **Tester** - Envoyez un premier message de test
4. **Utiliser** - L'application est prête !

### 2. Envoi d'un SMS
1. **Écrire** - Tapez votre message dans la zone de texte (max 160 caractères)
2. **Vérifier** - Le compteur indique le nombre de caractères utilisés
3. **Envoyer** - Cliquez sur le bouton ou utilisez `Ctrl+Entrée`
4. **Confirmer** - Un message de statut confirme l'envoi

## 🔐 Sécurité et confidentialité

### Mesures de sécurité implémentées
- ✅ **Communications HTTPS** - Chiffrement des échanges avec l'API
- ✅ **Validation côté client** - Vérification des données avant envoi
- ✅ **Pas de stockage persistant** - Vos données ne sont pas sauvegardées
- ✅ **Code source ouvert** - Transparence totale du fonctionnement
- ✅ **Respect de la vie privée** - Aucun tracking ni analytics

### Données traitées
- Identifiant Free Mobile (temporaire)
- Clé API (temporaire)
- Message SMS (temporaire)
- Numéro destinataire (temporaire)

*Toutes les données sont traitées côté client et ne sont jamais stockées de manière permanente*

## 🐛 Résolution des problèmes

### Codes d'erreur Free Mobile

| Code | Description | Solution |
|------|-------------|----------|
| **400** | Paramètres manquants ou incorrects | Vérifiez vos identifiants et le format du message |
| **402** | Quota SMS dépassé ou option non activée | Activez l'option SMS dans votre espace Free Mobile |
| **500** | Erreur serveur Free Mobile | Réessayez plus tard, problème côté Free |

### Problèmes courants

#### L'application ne se charge pas
1. ✅ Vérifiez votre connexion internet
2. ✅ Désactivez temporairement les bloqueurs de publicité
3. ✅ Essayez un autre navigateur
4. ✅ Videz le cache de votre navigateur

#### Erreur de connexion
1. ✅ Vérifiez que l'option SMS est activée sur Free Mobile
2. ✅ Vérifiez la validité de votre clé API
3. ✅ Testez depuis un autre réseau
4. ✅ Contactez le support Free Mobile si nécessaire

#### Messages non reçus
1. ✅ Vérifiez le numéro destinataire
2. ✅ Confirmez que le destinataire peut recevoir des SMS
3. ✅ Respectez la limite de 160 caractères
4. ✅ Vérifiez votre quota SMS Free Mobile

## 📊 Compatibilité navigateurs

| Navigateur | Version minimale | Support |
|------------|------------------|---------|
| ![Chrome](https://img.shields.io/badge/Chrome-4285F4?logo=googlechrome&logoColor=white) | 80+ | ✅ Complet |
| ![Firefox](https://img.shields.io/badge/Firefox-FF7139?logo=firefox&logoColor=white) | 75+ | ✅ Complet |
| ![Safari](https://img.shields.io/badge/Safari-000000?logo=safari&logoColor=white) | 13+ | ✅ Complet |
| ![Edge](https://img.shields.io/badge/Edge-0078D7?logo=microsoftedge&logoColor=white) | 80+ | ✅ Complet |
| ![Opera](https://img.shields.io/badge/Opera-FF1B2D?logo=opera&logoColor=white) | 67+ | ✅ Complet |

## 📝 Roadmap

### Version 1.1.0 (En cours)
- [ ] 🌙 **Mode sombre/clair** - Commutateur de thème
- [ ] 💾 **Sauvegarde locale** - Mémorisation des paramètres (localStorage)
- [ ] 📊 **Statistiques d'envoi** - Compteur de SMS envoyés
- [ ] 🔔 **Notifications browser** - Confirmations d'envoi natives

### Version 1.2.0 (Prévue)
- [ ] 📄 **Templates de messages** - Messages prédéfinis
- [ ] ⏰ **Historique des messages** - Conservation temporaire des SMS

### Version 2.0.0 (Long terme)
- [ ] 📱 **PWA complète** - Installation sur mobile/desktop
- [ ] 🔄 **Synchronisation multi-appareils** - Via compte utilisateur
- [ ] 🎨 **Thèmes personnalisables** - Personnalisation avancée
- [ ] 🌍 **Support multi-langues** - Interface internationalisée

### Pour les non-développeurs
- 🐛 **Signaler des bugs** via les [Issues](https://github.com/o2Cloud-fr/Web-FreeMobile-API-SMS/issues)
- 💡 **Proposer des améliorations** d'interface ou d'UX
- ⭐ **Mettre une étoile** si le projet vous plaît
- 📢 **Partager** l'application avec vos contacts Free Mobile

### Guidelines de contribution
- Respectez le design glassmorphism existant
- Testez sur mobile et desktop
- Maintenez la compatibilité multi-navigateurs
- Optimisez les performances de chargement
- Documentez vos modifications

```
MIT License

Copyright (c) 2024 o2Cloud

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## ⚠️ Disclaimer

Cette application web utilise l'**API officielle Free Mobile**. 

**Responsabilités :**
- Respectez les [conditions d'utilisation](https://mobile.free.fr/account/cgu) de Free Mobile
- N'abusez pas du service SMS (respect des quotas)
- L'auteur n'est pas responsable des usages inappropriés
- Utilisez cette application à vos propres risques

**Limitations :**
- Service disponible uniquement pour les abonnés Free Mobile
- Quota de SMS limité par Free Mobile
- Dépendant de la disponibilité de l'API Free Mobile
- Nécessite une connexion internet active

## 👨‍💻 Auteur

**o2Cloud**
- 🌐 GitHub: [@o2Cloud-fr](https://github.com/o2Cloud-fr)
- 📧 Email: [github@o2cloud.fr](mailto:github@o2cloud.fr)
- 💼 LinkedIn: [Rémi Simier](https://www.linkedin.com/in/remi-simier-2b30142a1/)
- 🌍 Website: [o2cloud.fr](https://o2cloud.fr)

## 🙏 Remerciements

- **Free Mobile** pour leur API publique et gratuite
- **La communauté web** pour les inspirations de design moderne
- **Les contributeurs open-source** pour les retours et améliorations
- **Tous les utilisateurs** qui testent et utilisent l'application
- **Vous** pour utiliser et soutenir ce projet !

## 📈 Support et communauté

### Obtenir de l'aide
- 📚 **Documentation** - Consultez ce README et la [démo en ligne](https://freemobile.o2cloud.fr/)
- 🐛 **Bugs** - Signalez sur [Issues](https://github.com/o2Cloud-fr/Web-FreeMobile-API-SMS/issues)
- 💬 **Questions** - Posez vos questions dans [Discussions](https://github.com/o2Cloud-fr/Web-FreeMobile-API-SMS/discussions)
- 📧 **Contact direct** - [github@o2cloud.fr](mailto:github@o2cloud.fr)

### Liens utiles
- 🌐 **Application web** - [freemobile.o2cloud.fr](https://freemobile.o2cloud.fr/)
- 🖥️ **Version desktop** - [FreeMobile-API-SMS](https://github.com/o2Cloud-fr/FreeMobile-API-SMS)
- 📱 **API Free Mobile** - [Documentation officielle](https://mobile.free.fr/account/)

---

<div align="center">

**⭐ N'oubliez pas de mettre une étoile si cette application web vous a été utile ! ⭐**

[![GitHub stars](https://img.shields.io/github/stars/o2Cloud-fr/Web-FreeMobile-API-SMS?style=for-the-badge&logo=github)](https://github.com/o2Cloud-fr/Web-FreeMobile-API-SMS/stargazers)

*Fait avec ❤️ par [o2Cloud](https://github.com/o2Cloud-fr)*

**🌐 Essayez dès maintenant : [freemobile.o2cloud.fr](https://freemobile.o2cloud.fr/)**

</div>
