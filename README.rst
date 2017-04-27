SDI-Portal
===========

SDI-Portal is a GeoNode-2.6 customization based on geonode-project.

Installation
------------

Install geonode with::

    $ sudo add-apt-repository ppa:geonode/stable

    $ sudo apt-get update

    $ sudo apt-get install geonode

Create a new template based on the geonode example project.::
    
    $ django-admin startproject sdiportal --template=https://github.com/GeoNode/geonode-project/archive/2.6.zip -epy,rst 
    $ sudo pip install -e sdiportal

.. note:: You should NOT use the name geonode for your project as it will conflict with the default geonode package name.



