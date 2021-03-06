pycsw README
============

.. image:: https://travis-ci.org/geopython/pycsw.svg?branch=master
    :target: https://travis-ci.org/geopython/pycsw

pycsw is an OGC CSW server implementation written in Python.

pycsw fully implements the OpenGIS Catalogue Service Implementation 
Specification (Catalogue Service for the Web). Initial development started in 
2010 (more formally announced in 2011). The project is certified OGC 
Compliant, and is an OGC Reference Implementation.  Since 2015, pycsw is an 
official OSGeo Project.

pycsw allows for the publishing and discovery of geospatial metadata via 
numerous APIs (CSW 2/CSW 3, OpenSearch, OAI-PMH, SRU). Existing repositories 
of geospatial metadata can also be exposed, providing a standards-based 
metadata and catalogue component of spatial data infrastructures.

pycsw is Open Source, released under an MIT license, and runs on all major 
platforms (Windows, Linux, Mac OS X).

Please read the docs at http://pycsw.org/docs for more information.


Installation
_________________

.. code:: python 

  virtualenv pycswVirtEnv && cd pycswVirtEnv && . bin/activate
  git clone https://github.com/bennidietz/pycsw_fork.git && cd pycsw
  pip install -e . && pip install -r requirements-standalone.txt
  python pycsw/wsgi.py

    
    
Start virtenv and pycsw again
___________________

Run in folder where the pycswVirtEnv folder is in:

.. code:: python

 virtualenv pycswVirtEnv && cd pycswVirtEnv && . bin/activate
 cd pycsw
 pip install -e . && pip install -r requirements-standalone.txt  
 python pycsw/wsgi.py

