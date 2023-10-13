Laravel Valet & Nginx in UBUNTU OS

`sudo apt-get update` 

`sudo apt install curl git unzip`

`sudo apt install nginx`

`sudo apt install net-tools`

`ifconfig and check ip`

`sudo apt install php-fpm`

`sudo apt install php-mbstring php-xml php-zip php-curl`

`sudo apt install php-cli php`

`php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"`

`php -r "if (hash_file('sha384', 'composer-setup.php')==='e0012edf3e80b6978849f5eff0d4b4e4c79ff1609dd1e613307e16318854d24ae64f26d17af3ef0bf7cfb710ca74755a') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"`


`sudo php  composer-setup.php --install-dir=/usr/local/bin/ --filename=composer`

`composer` (check composer here)

`sudo chmod -R 777 ~/.composer` (if directory `not found` don't worry just chill and create a folder into `home` directory named `.composer` )

`composer global require cpriego/valet-linux`

`nano ~/.bashrc` (inside console after `fi` `PATH="$HOME/.config/composer/vendor/bin:$PATH"`)

`source ~/.bashrc`

`sudo apt install network-manager libnss3-tools jq xsel`

`https://cpriego.github.io/valet-linux/     then run valet install`

`mkdir /media/userName/driveName/folderName`

`cd /media/userName/driveName/folderName`

`pwd`

`valet park`

`sudo apt install php-mysql mysql-server mysql-client`

`sudo mysql`
 
`ALTER USER 'root'@'localhost' IDENTIFIED WITH caching_sha2_password BY 'password';`

`exit`
