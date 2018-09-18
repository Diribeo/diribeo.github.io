# Site vitrine Diribéo

Ce dépôt contient les sources du site vitrine de Diribéo, hébergé via GitHub Pages et accessible à l'adresse http://www.diribeo.fr/

## Instructions d'installation

1. Installer Ruby, si nécessaire
2. Installer Bundle, si nécessaire, via la commande `gem install bundler`
3. Clôner ce dépôt ou le télécharger puis le dézipper, puis `cd` dans le répertoire contenant ce fichier
4. Installer les dépendances de ce dépôt, via la commande `bundle install`
5. Lancer le serveur, via la commande `bundle exec jekyll serve --incremental`

Le serveur se charge de recompiler les fichiers (CSS et HTML) au fur et à mesure des modifications. Les fichiers sont compilés dans le répertoire `_site`.

Par défaut, la version compilée peut être testée à l'adresse http://127.0.0.1:4000/
