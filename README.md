## Laravel docker boiler plate

## Requirements:
###### PHP | 8.1
###### Composer | 2.0.12
###### Node | 16.*

### Laravel | 9.3 

### Follow the instructions to build up docker container for the boiler plate:

1. `cp .env.example .env`
2. Update database credentials
3. `Composer install`
4. `php artisan key:generate`
5. `npm install`
6. `npm run build`
7. `cd docker`
8. `docker compose up --build` ##### Make sure Docker desktop is running


Note: Run `docker compose down` to remove containers.
