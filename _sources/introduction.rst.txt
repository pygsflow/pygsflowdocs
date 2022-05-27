What is pyGSFLOW?
=================
The pyGSFLOW package is a library of Python modules to load, edit, and run the GSFLOW integrated hydrologic model program.
pyGSFLOW enables the user to programatically change their model inputs and run the updated model with a set of scripts. 
The pyGSFLOW project was started in 2016 and has been refined into a fully featured package. pyGSFLOW is now on version 1.1.0.

Return to the Github `pyGSFLOW <https://github.com/pygsflow/pygsflow>`_ website

pyGSFLOW installation
=====================
To install pyGSFLOW from a command line, terminal, or anaconda prompt run the command:

pip install pygsflow
	
or
	
pip install https://github.com/pygsflow/pygsflow/zipball/master

To install the development version with the most recent updates run:

pip install https://github.com/pygsflow/pygsflow/zipball/develop

pyGSFLOW dependencies
=====================
pyGSFLOW relies heavily on FloPy for modflow IO capabilities. `FloPy <https://github.com/modflowpy/flopy>`_ .
pyGSFLOW also extends these capabilities for working with GSFLOW models and input challenges specific to GSFLOW.

flopy can be installed by typing:
    pip install flopy
	
Tutorial Examples
=================

Contents:

.. toctree::
   :maxdepth: 2
   
   tutorials

Example Notebooks
=================

Jupyter Notebook examples can be found in the pyGSFLOW repository in the `examples <https://github.com/pygsflow/pygsflow/tree/master/examples>`_ directory

pyGSFLOW Development Team
=========================
pyGSFLOW is currently being developed by

* Joshua Larsen
* Ayman Alzraiee
* Donald Martin
* Rich Niswonger

How to Cite pyGSFLOW
====================
Larsen, J. D., Alzraiee, A., Niswonger, R., 2022, Integrated hydrologic model development and postprocessing for GSFLOW using pyGSFLOW. Journal of Open Source Software, 7(72), 3852. `https://doi.org/10.21105/joss.03852 <https://doi.org/10.21105/joss.03852>`_

Larsen, J. D., Alzraiee, A., Niswonger, R., 2021, pyGSFLOW v1.0.0: U.S. Geological Survey Software Release, 2 July 2021, `https://doi.org/10.5066/P9NPZ5AD <https://doi.org/10.5066/P9NPZ5AD>`_
