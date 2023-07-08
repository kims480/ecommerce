https://github.com/kims480/ecommerce.git

https://rahaal.store
…or create a new repository on the command line
echo "# oo_kpis" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kims480/ecommerce.git

ssh -p 65002 u459353948@194.195.84.224
Ringer!93
cd domains/rahaal.store/public_html/

git pull https://github.com/kims480/ecommerce.git  master

git checkout HEAD package.json public/css/app.css
git checkout HEAD^ app/Http/Controllers/SiteExtraController.php


alias php='/opt/cpanel/ea-php81/root/usr/bin/php'
export PATH="/opt/cpanel/ea-php81/root/usr/bin:$PATH"

php composer.phar ..


nano .env
cat .env


git add .
git commit -m "ecommerce_8"
git push -u origin master



chmod 777 -R ./
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
export NVM_DIR="$HOME/.nvm"

# create policy
php artisan make:policy ConsumableSparePolicy --model=ConsumbaleSpare


# create Seeders
php artisan make:seeder UserSeeder

# run seeders
php artisan db:seed
php artisan db:seed --class=UserSeeder

# fresh seeders
php artisan migrate:fresh --seed
php artisan migrate:fresh --seed --seeder=ConsumableSpareSeeder

# force seeders
php artisan db:seed --force
