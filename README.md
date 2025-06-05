<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# CYBARWIND-CMS
CybarWind admin management CMS

## Steps and Commands to be used:

1. Always use development branch for the work. (for backend)
2. Always use development branch for the work. (for frontend)

3. Once checkout is done use following commands:
    - composer install  // to install vendor dependencies or composer update
    - cp .env.example .env  // to copy env file once copied update DB credentials to match yours
    - php artisan migrate  // to migrate all the DB changes
    - php artisan db:seed  // to run seeder
    - php artisan key:generate  // to generate key for laravel
    - php artisan serve  // to run project
    - login credential to be used (email: admin@example.com, password: password)

4. Please use git [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) with proper message to push your changes to your branch.

5. Once changes are done please follow below points to work with git:
    - Always use development branch to take pull and work with it.
    - Create your branch by the use of [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/). No random branch names are allowed.
    - Once code is done, please push into your branch with proper commit message as per [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) and write down proper commit description.
    - Once commit description is done, please open a PR for development branch and assign it to your lead for review purpose.
    - Once review is done. Merging can only be done by lead side, no other person is allowed to perform code merge.


## Notes for release on staging and live server:

1. Once code arrives in development branch and updates are ready to be deploy. Merge code in staging branch for staging server deployment.

2. Once deployment is done please update a release for the same branch by using `npm run release` to generate release from command line and push release for respective branch by using `git push --follow-tags origin development` where development is the branch for which release is deployed.

3. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit and release guidelines.




