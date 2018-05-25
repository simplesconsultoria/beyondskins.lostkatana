=========================
Raider of the lost katana
=========================

.. contents:: Table of Contents
   :depth: 2

Introduction
============

Beyondskins Raiders of lost katana Theme is an installable Plone Theme developed by 
`Simples Consultoria`_ using the **theming** and **packaging** 
features available in `plone.app.theming`_.

You could use this theme in your project or as a start for you own Diazo themes -- but send us a
postcard, ok ;-)

Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest versión (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://github.com/simplesconsultoria/beyondskins.lostkatana/raw/master/beyondskins/lostkatana/theme/preview.jpg


Features
========

- It's an installable Plone Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple Diazo package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Zip file
--------

If you are an end user, you might enjoy installation via zip file import.

1. Download a `zip file <https://github.com/simplesconsultoria/beyondskins.lostkatana/raw/master/beyondskins.lostkatana.zip>`_.
2. Import the theme from the Diazo theme control panel.

Enabling the theme
^^^^^^^^^^^^^^^^^^

Select and enable the theme from the Diazo control panel. That's it!


Buildout
--------

If you are a developer, you might enjoy installing it via buildout.

For install ``beyondskins.lostkatana`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        beyondskins.lostkatana


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'beyondskins.lostkatana',
    ],


Contribute
==========

- Issue Tracker: https://github.com/simplesconsultoria/beyondskins.lostkatana/issues
- Source Code: https://github.com/simplesconsultoria/beyondskins.lostkatana


License
=======

The project is licensed under the GPLv2.

Credits
-------

- Andre Nogueira (agnogueira at gmail dot com) - Conception and prototype.

.. _`Simples Consultoria`: http://www.simplesconsultoria.com.br/
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
