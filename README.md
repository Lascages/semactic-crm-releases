<div align="center">

# Semactic CRM — application de bureau

**Le CRM Semactic, en application pour Mac et Windows.**

[![Télécharger pour Mac](https://img.shields.io/badge/T%C3%A9l%C3%A9charger-macOS-7d6bb0?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Lascages/semactic-crm-releases/releases/latest/download/Semactic-CRM-macOS.dmg)
[![Télécharger pour Windows](https://img.shields.io/badge/T%C3%A9l%C3%A9charger-Windows-698dbe?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Lascages/semactic-crm-releases/releases/latest/download/Semactic-CRM-Windows-x64-setup.exe)

[Toutes les versions](https://github.com/Lascages/semactic-crm-releases/releases) · [Journal des modifications](CHANGELOG.md) · [Installation](#installation) · [Mises à jour](#mises-à-jour) · [Aide](#aide)

</div>

---

> [!NOTE]
> Ce dépôt est **public** et ne contient que les **programmes à télécharger**, le journal des modifications et ce guide. Le code est dans un dépôt privé.
> L'accès au CRM reste réservé aux personnes invitées chez Semactic.

## Téléchargements

| Système | Fichier | Remarque |
|---|---|---|
| **macOS** 11 ou plus (Apple Silicon et Intel) | [`Semactic-CRM-macOS.dmg`](https://github.com/Lascages/semactic-crm-releases/releases/latest/download/Semactic-CRM-macOS.dmg) | un seul fichier pour tous les Mac |
| **Windows** 10/11 x64 — installeur | [`Semactic-CRM-Windows-x64-setup.exe`](https://github.com/Lascages/semactic-crm-releases/releases/latest/download/Semactic-CRM-Windows-x64-setup.exe) | installation pour l'utilisateur, sans droits administrateur |
| **Windows** 10/11 x64 — MSI | [`Semactic-CRM-Windows-x64.msi`](https://github.com/Lascages/semactic-crm-releases/releases/latest/download/Semactic-CRM-Windows-x64.msi) | pour le déploiement par l'IT |
| **Windows** ARM64 | [`Semactic-CRM-Windows-ARM64-setup.exe`](https://github.com/Lascages/semactic-crm-releases/releases/latest/download/Semactic-CRM-Windows-ARM64-setup.exe) | expérimental |

## Versions

<!-- VERSIONS:START -->
| Version | Canal | Date |
|---|---|---|
| [0.2.0](https://github.com/Lascages/semactic-crm-releases/releases/tag/v0.2.0) | Stable | 2026-10-26 |
| [0.1.5](https://github.com/Lascages/semactic-crm-releases/releases/tag/v0.1.5) | Stable | 2026-10-25 |
| [0.1.4](https://github.com/Lascages/semactic-crm-releases/releases/tag/v0.1.4) | Stable | 2026-10-25 |
<!-- VERSIONS:END -->

Détail de chaque version : [CHANGELOG.md](CHANGELOG.md).

## Installation

**Mac** : ouvrez le `.dmg`, glissez *Semactic CRM* dans *Applications*, lancez-le.
**Windows** : lancez le `.exe` et suivez l'assistant.

> Tant que les certificats de signature ne sont pas en place (version interne), votre système peut afficher un avertissement :
> sur Mac, clic droit sur l'app › *Ouvrir* ; sur Windows, *Informations complémentaires › Exécuter quand même*.
> Les versions publiées ensuite seront signées et notarisées.

## Connexion

Cliquez sur **Se connecter avec Google** et utilisez votre compte Semactic. Votre navigateur s'ouvre, puis vous revenez dans l'application.
Un mot de passe CRM fonctionne aussi. Si l'accès est refusé : vous n'avez pas encore été invité(e), contactez un administrateur.

## Mises à jour

L'application vérifie toute seule s'il existe une nouvelle version (au démarrage, puis toutes les 4 heures). Un bandeau propose
**Mettre à jour** (avec les nouveautés) ou **Plus tard**. Les mises à jour sont **signées** : l'application refuse tout fichier non signé par Semactic.
*Réglages › Mises à jour* permet de vérifier à la main et de choisir le canal **Stable** (par défaut) ou **Bêta** (en avance, moins testé).

## Aide

* L'application ne démarre plus ou la connexion échoue : *Réglages › Se déconnecter*, puis relancez.
* Un doute sur la sécurité : n'ouvrez pas de ticket public ; écrivez à l'équipe Dev de Semactic.
* Besoin d'une version précédente : [toutes les versions](https://github.com/Lascages/semactic-crm-releases/releases).

<sub>© Semactic. Les binaires de ce dépôt sont destinés aux collaborateurs et clients autorisés de Semactic.</sub>
