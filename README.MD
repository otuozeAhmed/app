
# Shop Django App

This is a task project. However, you may use it whichever way you want in your personal project.
## How to set up?

By using docker we can easily set up project.

###### To successfully set up this project ensure you have "Make" and "Docker" installed in your Mac or Linux environment or WSL (Windows users), enter the following commands in your terminal

```bash
  git clone https://github.com/otuozeAhmed/codacty-shop.git
  cd codacty-shop
  sudo make up
  sudo make makemigrations
  sudo make migrate
  sudo make collectstatic
  visit http://0.0.0.0/en/ to view your project
  # look-up the Makefile in the codacty-shop
  # directory for more handy commands with make
```
Note: This project utilizes internationalization, kindly add the spanish version of any products or categories you create. Project specific files, settings, modules are automatically translated.