^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package hector_quadrotor_gazebo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.3.1 (2013-12-26)
------------------
* also check if a target exists when searching available plugins
* enables aerodynamics plugin in default configuration
* limit controlPeriod to 100Hz
* a few fixes for RTT integration in hector_quadrotor. Added urdf macro for rtt_gazebo_plugin macro.
* deprecated quadrotor_simple_controller.gazebo.xacro
* fixed node type for static_transform_publisher in spawn_quadrotor.launch
* changed frame_id for gazebo fixed frame to /world and added a static_transform_publisher for world->nav
* increased drift for the barometric pressure sensor
* added some command input ports to quadrotor_controller.gazebo.xacro
* Contributors: Johannes Meyer

0.3.0 (2013-09-11)
------------------
* Catkinized stack hector_quadrotor and integrated hector_quadrotor_demo package from former hector_quadrotor_apps stack
* increased drift for the barometric pressure sensor
* added some command input ports to quadrotor_controller.gazebo.xacro
* added launch file for two quadrotors
