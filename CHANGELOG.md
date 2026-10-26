# Journal des modifications

## [0.2.1-beta.1] — 2026-10-26

Version de test (canal bêta) : Slide et trousseau.

### Corrigé
- **Slide** : chaque utilisateur a ses propres clés d'appareil sur une même machine (deux collègues sur un même Mac ne se bloquent plus avec « appareil refusé »), et l'inscription n'est plus retentée en rafale au démarrage.
- **Trousseau** : une seule demande de code au lieu de trois (les secrets sont regroupés dans un seul élément ; les anciens sont repris automatiquement, vous devrez peut-être confirmer une fois).

## [0.2.0] — 2026-10-26

Le CRM complet dans l'application : plus besoin d'aller sur le site.

### Ajouté
- **Le CRM complet dans l'application** : les pages, listes, fiches, tableaux de bord, tickets, projets, prospection, Drive… du CRM web, avec les mêmes droits, ouvertes directement dans l'application (plus besoin d'aller sur le site).
- **Menu du profil** : au survol de votre nom (en bas du menu de gauche) : Mon profil, Hub équipe, Slide, Réglages de l'app et Déconnexion (le bouton du bas du menu de gauche disparaît). La bannière de mise à jour et les offres Slide reçues s'affichent sur toutes les pages.
- **Fichiers** : envoi (documents, pièces jointes), téléchargement et « Enregistrer sous » du système (PDF, exports).
- **Partager** : bouton sur chaque page pour copier le lien web (lisible par tous), copier le lien de l'app (ouvre l'app au bon endroit) ou ouvrir dans le navigateur.
- Flux en direct (chat, agent de prospection), liens `mailto:` et `tel:`, glisser-déposer de fichiers.

### Corrigé
- Le texte se sélectionne et se copie maintenant partout dans l'application.

## [0.1.5] — 2026-10-25

### Modifié
- Version de contrôle de la mise à jour automatique : aucune nouveauté visible.

## [0.1.4] — 2026-10-25

Première version réellement distribuée (les 0.1.0 à 0.1.3 n'ont jamais été publiées : leur compilation automatique a échoué avant publication).

### Corrigé
- Chaîne de publication : les installeurs macOS et Windows se compilent et se publient correctement, avec ou sans certificat de signature.

