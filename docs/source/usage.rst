Usage
=====

.. _installation:

Installation
-------

**Sumo2Unity** is currently available in GitHub. We have plans to soon make it available as a single software.
As of now it is available for Windows, MacOS, and Linux. 

To download and install follow these steps:

- Pre-Requisites

You need to install these Pre-requisite softwares to setup the environment to run **SUMO2Unity**.
   * Download and Install Sumo
      #. Download and the latest version of Sumo from `here <https://eclipse.dev/sumo/>`_.
   * Download and Install Unity.
         #. Download free version of Unity Hub (Unity Personal) from `here <https://unity.com/download>`_.
         #. Once installed, open Unity hub to install the Unity Editor.
         #. You can install the recommended version by Unity or you can choose version 2022.3.16f1.
         #. You can opt out of downloading Microsoft Visual Studio, if you do not plan to modify the code.

- Installing **Sumo2Unity**
#. Go to **Sumo2Unity** `GitHub Repo <https://github.com/SUMO2Unity/SUMO2Unity>`_.
#. Clone the repo: ``git clone https://github.com/SUMO2Unity/SUMO2Unity`` or download it as a zip file.
#. Once downloaded, open the project using Unity on the recommended version.
#. In the editor, go to _Project/Scenes and open SUMO2Unity scene.
#. Click on the play button to start the simulation.


To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

