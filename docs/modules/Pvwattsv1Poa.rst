.. _Pvwattsv1Poa:

Pvwattsv1Poa
***********************************

Wrapper for SAM Simulation Core model: `cmod_pvwattsv1_poa.cpp <https://github.com/NREL/ssc/blob/develop/ssc/cmod_pvwattsv1_poa.cpp>`_

Input Consistency Warning
==================================

As described in :ref:`Possible Problems <possible_problems>`, some input parameters are interdependent but the equations 
that enforce consistency are not available in this PySAM module. Therefore,
the onus is on the PySAM user to check that interdependencies are correctly handled. The variables which may require
additional logic include:


Provided for each of these inputs is a list of other inputs that are potentially interdependent. 

Creating an Instance
===================================

Refer to the :ref:`Initializing a Model <initializing>` page for details on the different ways to create an instance of a PySAM class.

**Pvwattsv1Poa model description**

.. automodule:: PySAM.Pvwattsv1Poa
	:members:

Functions
===================================

.. autoclass:: PySAM.Pvwattsv1Poa.Pvwattsv1Poa
	:members:

Weather Group
======================================================

.. autoclass:: PySAM.Pvwattsv1Poa.Pvwattsv1Poa.Weather
	:members:

PVWatts Group
======================================================

.. autoclass:: PySAM.Pvwattsv1Poa.Pvwattsv1Poa.PVWatts
	:members:

Outputs Group
======================================================

.. autoclass:: PySAM.Pvwattsv1Poa.Pvwattsv1Poa.Outputs
	:members:

