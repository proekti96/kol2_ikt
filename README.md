Ова е колоквиум 2 по предметот Методологија на истражувањето во ИКТ, на Даниела Јанушевска, 141151

Употреба на Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/proekti96/kol2_ikt.git/HEAD)

.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/proekti96/kol2_ikt.git/HEAD
 
Употреба на ScriptOfScripts(SOS): 
This notebook shows how you can install a Julia and Python environment side-by-side, and use
both kernels in a Jupyter Notebook, using [SoS](https://vatlab.github.io/sos-docs) as a super kernel.
There are several configuration files in this repository:

* `environment.yml`: an anaconda python environment, also installs SoS and SoS Notebook
* `REQURE`: a Julia environment with recommended packages
* `postBuild`: Post build command to install the SoS Kernel.

All kernels will be available to you in a Binder environment. You can use
Julia or Python kernels separately, or use a SoS kernel to use both kernels
in a single notebook.