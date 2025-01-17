pymodaq_plugins_physical_measurements (Physical Measurements Hardware)
######################################################################

.. image:: https://img.shields.io/pypi/v/pymodaq_plugins_physical_measurements.svg
   :target: https://pypi.org/project/pymodaq_plugins_physical_measurements/
   :alt: Latest Version

.. image:: https://readthedocs.org/projects/pymodaq/badge/?version=latest
   :target: https://pymodaq.readthedocs.io/en/stable/?badge=latest
   :alt: Documentation Status

.. image:: https://github.com/CEMES-CNRS/pymodaq_plugins_physical_measurements/workflows/Upload%20Python%20Package/badge.svg
    :target: https://github.com/CEMES-CNRS/pymodaq_plugins_physical_measurements

Set of PyMoDAQ plugins for various physical measurements: multimeter, lockin, oscilloscope,
indus cameras...


Authors
=======

* Sebastien J. Weber

Contributors
============

* David Bresteau
* Nicolas Bruyant
* Romain Geneaux

Instruments
===========
Below is the list of instruments included in this plugin


Actuator
++++++++

* **Keithley2400**: Sourcemeter Keithley  2400 (using pymeasure intermediate package)

Viewer0D
++++++++

* **Keithley_Pico**: Pico-Amperemeter Keithley 648X Series, 6430 and 6514
* **Keithley2110**: Multimeter Keithley  2110
* **Lockin7270**: Lockin Amplifier Ametek 7270
* **LockinSR830**: LockIn Amplifier SR830

Viewer1D
++++++++

* **LecroyWaveRunner6Zi**: Oscilloscope LecroyWaveRunner 6Zi
* **Tektronix**: Oscilloscope Tektronix MDO Series
* **Picoscope**: Picoscope from Picotechnology

Viewer2D
++++++++

* **OpenCVCam**: Webcams control using the opencv library
* **GenICam**: GeniCam compliant cameras suing the harvester libary
* **TIS**: The Imaging Source TIS cameras

Installation instructions for the Lecroy plugin
===============================================

You will also need to install the following softwares.
Follow the link to get the installers.

Lecroy ActiveDSO: https://teledynelecroy.com/support/softwaredownload/activedso.aspx?capid=106&mid=533&smid=

NI-VISA: https://www.ni.com/fr-fr/support/downloads/drivers/download.ni-visa.html#305862


