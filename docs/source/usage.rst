.. _installation:

Installation
=====

**Sumo2Unity** is currently offered through GitHub. We are planning to transition to a 
single-software distribution model in the near future. The software is currently compatible with Windows, macOS, and Linux operating systems.
To download and install follow these steps:

Pre-Requisites
-------

You need to install these Pre-requisite softwares to setup the environment to run **SUMO2Unity**.
   * Download and Install Sumo
      #. Download and the latest version of Sumo from `here <https://eclipse.dev/sumo/>`_.
   * Download and Install Unity.
         #. Download free version of Unity Hub (Unity Personal) from `here <https://unity.com/download>`_.
         #. Once installed, open Unity hub to install the Unity Editor.
         #. You can install the recommended version by Unity or you can choose version 2022.3.16f1.
         #. You can opt out of downloading Microsoft Visual Studio, if you do not plan to modify the code.

Installing **Sumo2Unity**
-------
#. Go to **Sumo2Unity** `GitHub Repo <https://github.com/SUMO2Unity/SUMO2Unity>`_.
#. Clone the repo: ``git clone https://github.com/SUMO2Unity/SUMO2Unity`` or download it as a zip file.
#. Once downloaded, open the project using Unity on the recommended version.
#. In the editor, go to ``_Project/Scenes`` and open SUMO2Unity scene.
#. Click on the play button to start the simulation.


.. _How to Use:

How To Use?
===========

Play Mode
----------

**Controlling the Simulation**
   Once the simulation is started, users can navigate the environment through the "Simulator Car." 
   Control the Simulator Car using either the arrow keys or the "WASD" keys on your keyboard.

**Viewing the Environment**
   To freely move the camera and explore the environment from different perspectives, switch to "Scene Mode." 
   The simulation can be paused at any time by pressing the pause button located at the top of the interface. 

Simulation Settings
-------------------

To change the simulation settings follow the steps:

   #. In File Explorer, go to ``Assets/_Project/Sumo_Data``
   #. Open Sumo2Unity file to see the simulation.
   #. To modify, Click on ``Edit > Open network in netedit`` or press ``ctrl + T``.

- Change Vehicle Settings
Inside Netedit, you can change vehicle settings by following these steps:

   #. Go to ``Demand`` tab on top middle of the interface
   #. Click on ``Create Vehicle Mode`` which is a vehicle icon, just below the ``Demand`` button.
   #. Here you can customise the vehicle and add new routes.
   #. To add a new route, simply start selecting routes in the network.
   #. Once route is designed, click on ``Finish route creation`` on the bottom left of the screen.

.. note::

   When adjusting the vehicle settings, please make sure to create a single vehicle with ID 0. 
   This will serve as the designated location for your simulator car.

   The id has to follow a strict naming convention, that is ``PrefabName_id``.
   The following prefab names are available as of now:
      - AlmaBlue
      - AlmaGrey
      - ElkaGrey
      - ElkaRed
      - EloraBlue
      - EloraWhite

   For example, ``AlmaBlue_01`` id will instantiate an Alma Blue color npc vehicle.



****Change Traffic Signal Settings
Inside Netedit, you can change traffic signal settings by following these steps:

   #. Go to ``Network`` mode on the top middle of the interface
   #. Click on ``Set traffic light mode`` which is a traffic light icon.
   #. Select a junction you want to modify.
   #. Click on Create button.







