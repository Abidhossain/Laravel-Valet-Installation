Laravel Valet & Nginx in UBUNTU OS

1.`sudo apt-get update` 

2.`sudo apt install curl git unzip`

3.`sudo apt install nginx`

4.`sudo apt install net-tools`

5.`ifconfig and check ip`

6.`sudo apt install php-fpm`

7.`sudo apt install php-mbstring php-xml php-zip php-curl`

8.`sudo apt install php-cli php`

9.`php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"`

10.`php -r "if (hash_file('sha384', 'composer-setup.php')==='e0012edf3e80b6978849f5eff0d4b4e4c79ff1609dd1e613307e16318854d24ae64f26d17af3ef0bf7cfb710ca74755a') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"`


11.`sudo php  composer-setup.php --install-dir=/usr/local/bin/ --filename=composer`

12.`composer` (check composer here)

13.`sudo chomd -R 777 ~/.composer` (if directory `not found` don't worry just chill and create a folder into `home` directory named `.composer` )

14.`composer global require cpriego/valet-linux`

15.`nano ~/.bashrc` (inside console after `fi` `PATH="$HOME/.config/composer/vendor/bin:$PATH"`)

16.`source ~/.bashrc`

17.`sudo apt install network-manager libnss3-tools jq xsel`

18.` https://cpriego.github.io/valet-linux/     then run valet install`

19.`mkdir /media/userName/driveName/folderName`

19.`cd /media/userName/driveName/folderName`

20.`pwd`

21.`valet park`
22. `sudo apt install php-mysql mysql-server mysql-client`
23. `sudo ALTER USER 'root'@'localhost' IDENTIFIED WITH caching_sha2_password BY 'password';`
24. `exit`

