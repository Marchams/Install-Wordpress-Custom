Lancer composer update via le terminal dans la racine du projet.

Créer la bdd et dupliquer le wp-config-sample :
- Entrer les données de la bdd
- Mettre en place le salage
- modifier define('WP_CONTENT_URL', 'http://_URLDEWORDPRESS_/content' );  Mettre l'url de la home/content

Gérer les accès des fichiers via le terminal:

sudo chown -R <mon-utilisateur>:www-data .
sudo find . -type f -exec chmod 664 {} +
sudo find . -type d -exec chmod 775 {} +
sudo chmod 644 .htaccess
