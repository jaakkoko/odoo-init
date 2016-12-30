# odoo-init

This is a bash shell script that creates very basic folder structure for a new [Odoo](https://github.com/odoo/odoo) module.

Run in your Odoo addons folder:

    $ odoo-init my_new_module


Creates new module named my_new_module with following tree structure:

    ./my_new_module
    |-- __init__.py
    |-- __openerp__.py
    |-- controllers/
    |   |-- __init__.py
    |-- data/
    |-- models/
    |   |-- __init__.py
    |-- security/
    |-- static/
    |   |-- img/
    |   |-- lib/
    |   |-- src
    |       |-- js
    |       |-- css
    |       |-- less
    |       |-- xml
    |-- views/
