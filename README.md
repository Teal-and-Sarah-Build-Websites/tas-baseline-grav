# tas-baseline-grav
Baseline structure. Starting point for our grav sites

## To use this Repo
Clone the basic grav repo (https://github.com/getgrav/grav.git) and rename it whatever you want for the project

From inside the project folder:

* delete the user folder
* clone this repo into the project, renaming this repo "user"
* run `bin/grav install`
* run `php -S localhost:8000 system/router.php`

Go to http://localhost:8000/ to view your site!


## Editing the Baseline
Only edit within the user folder

First update all site variables in config/site.yaml

Several page types are included. Delete or duplicate to suit the new project.


## Creating a new Repo for your project
When you are ready to create a new repo for your new site, delete the user/.git.

Initialize a new repo from inside the user folder with `git init` and follow basic instructions to push to a new repo.
