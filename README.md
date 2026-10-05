# Prototype cliquable PRESSIAT

Prototype statique autonome du parcours KEYZz PRESSIAT.

## Lancer en local sur macOS

1. Double-cliquer sur `Lancer prototype.command`.
2. Si macOS bloque le fichier : clic droit → **Ouvrir** → confirmer.

## Parcours

Landing → Connexion → Code → Nom → Paiement → Traitement → Révélation → Partage.

La barre inférieure permet également de tester les branches suivantes :

- salle d’attente ;
- paiement refusé ;
- édition épuisée.

## Déployer sur Vercel

1. Placer le contenu de ce dossier à la racine d’un dépôt GitHub.
2. Importer le dépôt dans Vercel.
3. Framework Preset : **Other**.
4. Ne renseigner aucune commande de build.
5. Conserver le dossier de sortie vide ou `.`.
6. Déployer.

Vercel sert automatiquement `index.html`.

## Déployer sur GitHub Pages

Dans le dépôt GitHub : **Settings → Pages → Deploy from a branch**, puis sélectionner la branche principale et le dossier `/ (root)`.

## Ressources

Les images sont intégrées directement dans `index.html`. Aucun dossier d’assets ni installation npm n’est nécessaire. Les polices Google disposent de polices système de secours si le réseau les bloque.
