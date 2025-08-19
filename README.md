# Supervision réseau avec Centreon

## 📖 Description
Projet de mise en place d’une solution de supervision réseau basée sur Centreon, installée sur Debian 12. Le serveur distant est supervisé via SNMP, permettant la visualisation en temps réel des métriques système et la génération d’alertes en cas de dépassement de seuils.

## 🎯 Objectifs
- Déployer une plateforme de supervision open source.
- Configurer SNMP sur le serveur supervisé.
- Surveiller les services et ressources (CPU, RAM, disque) en temps réel via l’interface web de Centreon.

## 🛠 Étapes techniques
### Installation de Centreon
- Configuration des dépôts et installation des paquets requis.
- Configuration de MariaDB, PHP, Apache2 et dépendances.
- Accès et configuration via le WebInstaller de Centreon.

### Configuration du serveur supervisé
- Installation et configuration de `snmpd`.
- Définition de la communauté SNMP dans `/etc/snmp/snmpd.conf`.
- Tests de connectivité via `snmpwalk`.

### Ajout de l’hôte dans Centreon
- Déclaration de l’hôte supervisé.
- Association des templates SNMP génériques.
- Déploiement et vérification en temps réel.

## 🛠 Outils et protocoles
- Debian 12 (Bookworm)
- Centreon (interface web + moteur)
- SNMP v2c
- Paquets : apache2, mariadb-server, snmpd, rrdtool, centreon-engine, centreon-web

## ✅ Résultat
L’interface Centreon affiche en temps réel les métriques du serveur distant. Les alertes sont générées automatiquement en cas de dépassement de seuils. Ce projet offre une supervision efficace et évolutive, avec possibilité d’intégration future à Grafana.

## 💻 Compétences
- Supervision réseau et services
- Protocoles SNMP et client/serveur
- Gestion des dépendances, diagnostics réseau et résolution d’erreurs

## 📂 Fichiers inclus
| Fichier | Description |
|---------|-------------|
| `Capture d'écran 2025-08-05 111513.png` | Capture d’écran de l’interface Centreon affichant les métriques du serveur supervisé. |
| `TP_autoformation_3107_reseau_ip` | Fichier du TP d’autoformation réseau et IP lié au projet. |
| `README.md` | Documentation et explications du projet |

