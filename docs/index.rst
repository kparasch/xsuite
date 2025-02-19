.. Read the Docs Template documentation master file, created by
   sphinx-quickstart on Tue Aug 26 14:19:49 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

======
Xsuite
======

Xsuite is a collection python packages for the simulation of the beam dynamics in particle accelerators. It supports different computing platforms, in particular conventional CPUs and and Graphic Processing Units (GPUs).

Xsuite is composed by the following packages:
 - **Xobjects**: infrastructure to manage the memory, compile and execute code on different computing platforms;
 - **Xpart**: package to generate and manipulate ensembles of particles;
 - **Xtrack**: single-particle tracking library, creation/import of beam line descriptions;
 - **Xfields**: computation of the electromagnetic fields generated by particle ensembles using Particle In Cell (PIC) solvers or analytical distributions.
 - **Xdeps**: management of the dependencies, implementation of deferred expressions.

The implemented physics models are being documented in `this guide <https://github.com/xsuite/xsuite/blob/master/docs/physics_manual/physics_man.pdf>`_.
The source code is available in these `GitHub repositories <https://github.com/xsuite/>`_.

Table of contents
-----------------

.. toctree::
   :maxdepth: 2

   usersguide
   developer
   physicsguide
   apireference

Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

