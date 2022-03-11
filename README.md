# School_Management_Timeline_system

project showing how to use roles-permissions (students, teachers, admins), Eloquent Query Scopes and how to build a simple table-based timetable calendar.

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL. 
- Admin's credentials: __admin@admin.com__ - __password__
- Teacher's credentials: __teacher@teacher.com__ - __password__
- Student's credentials: __student@student.com__ - __password__
