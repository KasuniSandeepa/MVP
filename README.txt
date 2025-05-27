Factory data creation.
App\Models\Job::factory(100)->create();

Database seeder.
1. Create seeder folder -> php artisan migrate:fresh --seed
2. Trigger --> php artisan db:seed
3. Regresh the db and seed --> php artisan migrate:fresh --seed
4. To run only the relavant class --> php artisan db:seed --class=JobSeeder (JobSeeder is the class name)