# Invoice Helper

Application Mac pour analyser, renommer et classer les factures PDF de plusieurs sociétés.

[Télécharger la dernière version](https://github.com/jefllm/invoice-helper-updates/releases/latest)

Ouvrir le DMG, glisser Invoice Helper dans Applications, puis renseigner son dossier et sa propre clé API OpenAI. Commencer en mode aperçu / test. Le menu permet de rechercher les mises à jour suivantes sans réinstaller manuellement.

Ce dépôt contient uniquement les fichiers de distribution. Aucune clé API, facture, configuration personnelle ou clé privée de signature n’y est publiée. Le code source de l’application n’est pas publié ici.

Les mises à jour Sparkle et leur flux sont signés Ed25519. La distribution utilise une signature locale ad hoc, sans notarisation Apple ; macOS peut demander une autorisation au premier lancement. Apple Silicon et Intel inclus, macOS 12 minimum déclaré ; les tests sont effectués sur Apple Silicon.

L’accès à l’API OpenAI est facturé sur le compte de chaque utilisateur. L’application transmet les PDF à OpenAI pour analyse et conserve les clés saisies dans le trousseau du Mac.
