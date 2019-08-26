# tas-baseline-grav
Baseline structure. Starting point for our grav sites

## To use
Clone the basic grav repo (https://github.com/getgrav/grav.git) and rename it whatever you want for the project

In that project delete the user folder and clone this repo into the project, renaming this repo "user"

From inside the project folder run `bin/grav install`
then `php -S localhost:8000 system/router.php`

Go to http://localhost:8000/ to view your site!

Only edit within the user folder



When you are ready to create a new repo for your new site, delete the user/.git, initialize a new repo from inside user and follow basic instructions to push to a new repo.
