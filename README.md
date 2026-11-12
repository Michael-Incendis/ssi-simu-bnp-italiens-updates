# SSI SIMU BNP — Italien — Mises à jour

Ce dépôt public distribue exclusivement les installateurs et mises à jour de **SSI SIMU BNP — Italien** pour Windows 11 x64. Il est distinct de SSI SIMU classique.

## Version de production 0.2.9

- [Télécharger le setup 0.2.9](https://github.com/Michael-Incendis/ssi-simu-bnp-italiens-updates/releases/download/production-v0.2.9/ssi-simu-bnp-italien-production_0.2.9_x64-setup.exe)
- [Notes, signature et empreintes SHA-256](https://github.com/Michael-Incendis/ssi-simu-bnp-italiens-updates/releases/tag/production-v0.2.9)
- [Manifeste du canal production](channels/production/latest.json)

La version 0.2.9 ouvre directement l'Accueil et conserve les vérifications de licence en arrière-plan.

**Depuis 0.2.8 :** recherchez la mise à jour dans l'application et confirmez son installation hors exercice en cours. L'installation reste propre à la session Windows quotidienne.

**Ancienne installation pour tous les comptes, jusqu'à 0.2.7 :** une migration préalable avec un administrateur est nécessaire. Désinstallez l'ancienne installation **sans effacer les données**, puis lancez normalement le nouveau setup depuis la session habituelle. Le setup refuse une ancienne installation machine encore enregistrée. Ne supprimez pas le cache de licence.

La signature .sig est vérifiée par l'updater BNP ; elle est distincte d'une signature Authenticode Windows. Une erreur réseau ou un manifeste absent reste une vérification impossible, pas un résultat « À jour ». L'installation nécessite une confirmation utilisateur.

Ce dépôt ne contient aucune source privée de l'application, clé privée de signature ou donnée de licence. Aucun workflow de publication automatique n'est configuré.
