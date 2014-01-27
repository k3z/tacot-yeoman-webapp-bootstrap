*************************
Tacot yo webapp bootstrap
*************************

This simple bootstrap combine the static site generator Tacot with Yeoman webapp scaffolding.
Yeoman webapp scaffolding brings a very nice grunt script to automate the process of web assets optmisation.
Tacot is a static web site generator based on Mako template engine.

Install
=======

You need to install bower, grunt and virtualenv on your system.

Download grunt packages and bower components.

::

    $ mkdir <project folder>
    $ git clone ./<project folder>
    $ grunt
    $ bower install

Create the virtualenv and install Tacot.

::

    $ virtualenv ./
    $ bin/pip install -r requirements.txt