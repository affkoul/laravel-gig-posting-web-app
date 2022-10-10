# laravel-gig-posting-web-app

A Laravel framework based gig posting Web App.

Mac Users Guide (for I am on developing on a Mac)

1. Clone this repository.

2. Install Laravel Valet (which you can google: laravel valet ) and start the valet server on your machine.

3. Install composer on your machine.

4. cd to valet's "Sites" folder and run composer global require laravel/installer to install laravel.

5. Copy the cloned repository to valet's "Sites" folder.

6. Stay in valet's "Sites" folder directory and run valet park to link to valet's server.

7. cd to cloned repository root inside valet's "Sites" folder and run composer install (&& composer update) to get going.

8. Configure your .env file properly as shown in .env.example.

9. Run php artisan migrate to create the database and all data tables needed.

10. Run php artisan db:seed to create dummy data to start.

11. Run php artisan storage:link to get all uploads to storage/app/public.

12. Open your browser and type laravel-gig-posting-web-app.test (since our cloned repository's folder name is laravel-gig-posting-web-app) to run the app locally.

13. To deploy on your server, go through steps 2 to 11 on your server, next copy the cloned repository folder to your web server's root directory, then configure properly as you usually do with other apps.

14. Here you go!

## In Action

![GAC Logo](https://geniusandcourage.com/favicon.ico)

Laravel Gig Posting Web App by [GAC DEV](https://geniusandcourage.com)

![Laravel Gig Posting Web App](https://hlwsdtech.com/jobboard/laravel-job-board.png)
