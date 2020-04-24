# caramel-storybook
Storybook project for developing caramel

Steps to start development

* Clone the project
* Go to the root directory and run `git submodule init`.
* After your `.gitmodules` file is created, you can either edit it to use ssh `perl -i -p -e 's|https://(.*?)/|git@\1:|g' .gitmodules` or you can go ahead with the current setting.
  * Don't forget to `git submodule sync` if you change the url in `.gitmodules`.
* Run `git submodule update` in the root directory. You will see that the submodule `caramel` will be there now.
