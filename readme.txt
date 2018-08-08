Lancer composer update.

Créer la bdd et dupliquer le wp-config sample

Gérer les accès :

sudo chown -R <mon-utilisateur>:www-data .
sudo find . -type f -exec chmod 664 {} +
sudo find . -type d -exec chmod 775 {} +
