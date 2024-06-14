# billing
If your pterodactyl installation is stock or u dont have yarn and node.js do these steps type commands one by one with root permissions
----------------------------------------------------------------------------------------------------
curl -sL [URL]https://deb.nodesource.com/setup_16.x[/URL] | sudo -E bash -
apt install -y nodejs
npm i -g yarn
cd /var/www/pterodactyl
yarn
----------------------------------------------------------------------------------------------------
After you installed yarn and node.js or if you already have it
extract zip to /var/www/pterodactyl
After billing is extracted to path above
Do "cd /var/www/pterodactyl"
And type "php artisan billing:install stable"
When it asks for licence key just type "wemxgay" and proceed with installation
After that type yarn build:production
----------------------------------------------------------------------------------------------------
