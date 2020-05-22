# caramel-storybook
Storybook project for developing caramel

## Steps to start development

* Clone the project
* Go to the root directory and run `git submodule init`.
* After your `.gitmodules` file is created, you can either edit it to use ssh with `perl -i -p -e 's|https://(.*?)/|git@\1:|g' .gitmodules` or you can go ahead with the current setting.
  * Don't forget to run `git submodule sync` if you change the url in `.gitmodules`.
* Run `git submodule update` in the root directory. You will see that the submodule `caramel` will be cloned now.

## Developing caramel
* Make sure you go into `caramel` directory and pull the latest version, otherwise it won't be updated.
* Checkout the branch that you want to use.
* When making a change inside the `caramel` project, make sure you push both `caramel` and `caramel-storybook` separately, otherwise it won't be updated in this repository.
* If you have it, remove `node_modules` from `caramel` directory.
* Run `yarn` at the root of the project.
* Run the project like a regular react native application.
* To open Storybook console, run `yarn storybook`.
