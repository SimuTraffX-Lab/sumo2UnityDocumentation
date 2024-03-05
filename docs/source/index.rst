Welcome to Sumo2Unity
===================================

Introduction
-------

**Sumo2Unity** is an open-source project that integrates the capabilities of SUMO (Simulation of Urban MObility) and Unity,
a powerful 3D game engine. This integration bridges the gap between microscopic traffic simulation and real-time 3D visualization,
enabling you to:

* **Visualize**: 
   Immerse yourself in a 3D environment that accurately reflects the
   simulated traffic network created in SUMO.
* **Analyze**: 
   Gain deeper insights into traffic behavior by observing and interacting
   with the simulation in real-time.
* **Develop**: 
   Leverage the combined power of SUMO and Unity to create custom applications for various purposes,
   such as training autonomous vehicles, evaluating traffic management strategies, and designing
   safer and more efficient transportation systems.

**SUMO**, a microscopic and continuous multi-modal traffic simulation package, offers a comprehensive suite of
features for modeling complex transportation systems, including:

* Road vehicles, public transport, and pedestrians
* Route finding, visualization, network import, and emission calculation
* Remote control and customization through various APIs

Unity provides a robust and user-friendly platform for creating interactive 3D experiences. 
By combining the strengths of these two powerful tools, Sumo2Unity empowers you to bridge 
the gap between simulation and visualization, opening doors to innovative research, development, 
and educational applications in the field of transportation.

Installation
-------

**Sumo2Unity** is currently available in GitHub. We have plans to soon make it available as a single software.
As of now it is available for Windows, MacOS, and Linux. 

To download and install follow these steps:

_ Pre-Requisites

You need to install these Pre-requisite softwares to setup the environment to run **SUMO2Unity**.
   * Download and Install Sumo
      #. Download and the latest version of Sumo from `here <https://eclipse.dev/sumo/>`_.
   * Download and Install Unity.
         #. Download free version of Unity Hub (Unity Personal) from `here <https://unity.com/download>`_.
         #. Once installed, open Unity hub to install the Unity Editor.
         #. You can install the recommended version by Unity or you can choose version 2022.3.16f1.
         #. You can opt out of downloading Microsoft Visual Studio, if you do not plan on modify the code.

_ Installing **Sumo2Unity**
#. Go to **Sumo2Unity** `GitHub Repo <https://github.com/SUMO2Unity/SUMO2Unity>`_.
#. Clone the repository or download it as a zip file.
#. Once downloaded, open the project using Unity on the recommended version.
#. In the editor, go to _Project/Scenes and open SUMO2Unity scene.
#. Click on the play button to start the simulation.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
   test
