# 🏠 Slack Toolbox - Documentation Wiki

> Bienvenue dans la documentation complète de **Slack Toolbox**, votre suite professionnelle d'outils CLI pour gérer et administrer vos espaces de travail Slack.

---

## 🎯 À propos de Slack Toolbox

**Slack Toolbox** est une plateforme open-source complète pour l'administration d'espaces de travail Slack. Elle offre une suite d'outils en ligne de commande puissants pour :

- 👥 **Gérer les utilisateurs** : Inviter, désactiver, exporter en masse
- 💬 **Administrer les canaux** : Créer, archiver, auditer l'activité
- 🔍 **Auditer la sécurité** : Détecter les anomalies et assurer la conformité
- 💾 **Sauvegarder les données** : Créer des backups complets du workspace
- 📊 **Générer des rapports** : Statistiques détaillées et tableaux de bord

---

## ⚡ Démarrage Rapide

Prêt à commencer ? Suivez ces étapes simples :

```bash
# 1. Cloner le dépôt
git clone https://github.com/GitCroque/slack-toolbox.git
cd slack-toolbox

# 2. Lancer l'assistant de configuration
python3 setup_wizard.py

# 3. Démarrer l'interface interactive
python slack-manager.py
```

Pour une installation détaillée, consultez le **[Guide d'Installation](./INSTALLATION.md)**.

---

## 📚 Documentation

### Guides Essentiels

| Guide | Description |
|-------|-------------|
| 📦 **[Installation](./INSTALLATION.md)** | Guide complet d'installation et de configuration initiale |
| ⚙️ **[Configuration](./CONFIGURATION.md)** | Obtenir un token Slack et configurer l'application |
| 📖 **[Utilisation](./UTILISATION.md)** | Guide complet pour maîtriser toutes les fonctionnalités |

### Documentation Technique

| Guide | Description |
|-------|-------------|
| 🏗️ **[Architecture](./ARCHITECTURE.md)** | Architecture technique, patterns et principes de conception |
| 🛠️ **[Développement](./DEVELOPPEMENT.md)** | Guide pour les développeurs souhaitant contribuer |

### Sécurité & Support

| Guide | Description |
|-------|-------------|
| 🔒 **[Sécurité](./SECURITE.md)** | Bonnes pratiques, protection des tokens et audit |
| ❓ **[FAQ](./FAQ.md)** | Réponses aux questions fréquentes et dépannage |

---

## 🌟 Fonctionnalités Principales

### 👥 Gestion des Utilisateurs
- Lister tous les utilisateurs avec filtres (rôle, statut, département)
- Inviter des utilisateurs en masse depuis un fichier CSV
- Désactiver ou réactiver des comptes
- Exporter les données utilisateurs (CSV, JSON, PDF)
- Détecter les utilisateurs inactifs

### 💬 Gestion des Canaux
- Lister et rechercher des canaux (publics et privés)
- Créer des canaux en masse avec configuration automatique
- Archiver les canaux inactifs
- Gérer les membres des canaux
- Exporter l'historique des conversations

### 🔍 Audit et Conformité
- Audit complet des permissions
- Détection des anomalies de sécurité
- Rapports d'activité détaillés
- Surveillance des changements d'administration
- Alertes intelligentes configurables

### 💾 Sauvegarde et Restauration
- Sauvegarde complète du workspace
- Export sélectif par canal ou période
- Comparaison de sauvegardes
- Formats multiples (JSON, CSV, HTML)

### 📊 Rapports et Analytics
- Statistiques du workspace en temps réel
- Tableaux de bord HTML interactifs
- Rapports PDF professionnels
- Métriques d'utilisation et tendances

---

## 🎮 Interface Interactive

Slack Toolbox propose une interface CLI interactive intuitive :

```
============================================================
  SLACK MANAGEMENT PLATFORM - Interactive CLI
============================================================

MAIN MENU
----------
1. User Management
2. Channel Management
3. Audit & Reports
4. Backup & Recovery
5. Workspace Statistics
6. Tools & Utilities
7. Exit

Enter your choice:
```

Ou utilisez directement les commandes Makefile :

```bash
make help              # Affiche toutes les commandes disponibles
make list-users        # Liste tous les utilisateurs
make list-channels     # Liste tous les canaux
make backup            # Crée une sauvegarde complète
make stats             # Affiche les statistiques du workspace
```

---

## 🔧 Prérequis

- **Python** : 3.8 ou supérieur
- **Token Slack** : Avec les permissions appropriées ([voir Configuration](./CONFIGURATION.md))
- **OS supportés** : Linux, macOS, Windows (WSL recommandé)

---

## 🤝 Contribuer

Nous accueillons les contributions ! Consultez le **[Guide de Développement](./DEVELOPPEMENT.md)** pour :

- Configurer votre environnement de développement
- Comprendre l'architecture du code
- Suivre les standards de code
- Soumettre vos pull requests

---

## 📞 Support et Ressources

- 🐛 **Issues** : [GitHub Issues](https://github.com/GitCroque/slack-toolbox/issues)
- 💬 **Discussions** : [GitHub Discussions](https://github.com/GitCroque/slack-toolbox/discussions)
- 📧 **Contact** : gitcroque@example.com

---

## 📖 Navigation Rapide

| Je veux... | Guide |
|------------|-------|
| Installer Slack Toolbox | [Installation](./INSTALLATION.md) |
| Obtenir un token Slack | [Configuration](./CONFIGURATION.md) |
| Apprendre à utiliser les outils | [Utilisation](./UTILISATION.md) |
| Comprendre l'architecture | [Architecture](./ARCHITECTURE.md) |
| Contribuer au projet | [Développement](./DEVELOPPEMENT.md) |
| Sécuriser mon installation | [Sécurité](./SECURITE.md) |
| Résoudre un problème | [FAQ](./FAQ.md) |

---

**Version** : 1.0
**Dernière mise à jour** : 2025-11-17
**Licence** : MIT
