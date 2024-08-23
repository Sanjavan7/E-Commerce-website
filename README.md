# E-commerce-websiite

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Sanjavan7/E-Commerce-website.git
   ```
2. Install Composer packages
   ```sh
   composer install
   ```
3. Copy the environment file & edit it accordingly
   ```sh
   cp .env.example .env
   ```

4. Generate application key
   ```sh
   php artisan key:generate
   ```

5. Create Database then migrate and seed
   ```sh
   php artisan migrate --seed


6. Linking Storage folder to public
   ```sh
   php artisan storage:link
   ```


7. Compile all your assets including a source map
   ```sh
   npm install && npm run dev
   ```

8. Serve the application
   ```sh
   php artisan serve
   ```
   
9. Configuration email
   ```sh
   add mail configuration in .env
   ```

## Permission folder
sudo chmod -R 777 settings.json

## Notes
if you need countries, states, cities data (change database in public/ecommerce_world.sql line 22)

## Contact
* [SANJAVAN](https://www.sanjavan7@gmail.com)
