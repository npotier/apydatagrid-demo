# APYDatagridBundle Demo

This is a simple **Symfony 5** project that allows to test locally the APYDatagridBundle project

it has 2 branches: 

* `main` : Symfony **5.3**
* `sf4` : Symfony **4.4**

# How does it works

The `composer.json` file declares the bundle as a local source.

You need to have this exact directory structure

```bash
# example /Users/rian/www
$ ls 

apydatagrid-demo
APYDataGridBundle
````

# Start the project

```bash
$ git clone https://github.com/npotier/apydatagrid-demo.git
$ cd apydatagrid-demo
$ symfony composer install
$ symfony console doctrine:migrations:migrate  
$ symfony serve
````