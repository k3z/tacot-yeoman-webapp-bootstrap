*************************
Tacot yo webapp bootstrap
*************************

This simple bootstrap combine the static site generator `Tacot`_ with `Yeoman`_ webapp scaffolding.
Tacot is a static web site generator based on Mako template engine.
Yeoman webapp scaffolding brings a very nice `Grunt`_ script to automate the process of web assets optmization.
`Yeoman`_ webapp scaffolding includes the powerfull `Bootstrap`_ front-end framework and `Sass`_ compilation.


Install
=======

You need to install `Bower`_, `NodeJs`_ and `Virtualenv`_ on your system.

Download grunt packages and bower components.

::

    $ mkdir <project folder>
    $ git clone git@github.com:k3z/tacot-yeoman-webapp-bootstrap.git ./<project folder>
    $ cd <project folder>
    $ npm install
    $ bower install

Create the virtualenv container and install Tacot.

::

    $ virtualenv ./
    $ bin/pip install -r requirements.txt


Usage
=====

The source code is stored in the app/ folder.
The templates are stored in the app/content/ folder.

The best way to code your project is to run :

::

    $ grunt serve

In this mode a local web server is launched and your browser reloads each time you save some changes.
First it compiles Mako templates and

To build the production files just run :

::

    $ grunt build

A dist/ folder is created with the final project.


.. _Virtualenv: http://www.virtualenv.org/en/latest/
.. _Grunt: http://gruntjs.com/
.. _Bower: http://bower.io/
.. _Yeoman: http://yeoman.io/
.. _Tacot: http://pythonhosted.org/tacot/en/
.. _Bootstrap: http://getbootstrap.com/
.. _Sass: http://sass-lang.com/
.. _NodeJs: http://nodejs.org/