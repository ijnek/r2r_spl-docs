Installation
############

.. warning::

   This package targets **ROS2 Foxy onwards**. It won't compile on all ROS1
   and older ROS2 distros.

Source Installation
*******************

.. note::

   Instructions here assume that you have and are in a ROS2 workspace's
   root directory.

Cloning repositories
====================

In your ROS2 workspace, clone the repository, install dependencies, and build it:

.. code-block:: console

   git clone https://github.com/ijnek/r2r_spl.git src/r2r_spl
   rosdep install --from-paths src -i
   colcon build
