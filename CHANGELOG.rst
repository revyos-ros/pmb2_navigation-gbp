^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pmb2_2dnav
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.2.0 (2024-09-03)
------------------
* Merge branch 'man/feat/docking' into 'humble-devel'
  added docking link
  See merge request robots/pmb2_navigation!97
* added docking link
* Contributors: josegarcia, martinaannicelli

4.1.1 (2024-08-06)
------------------
* Merge branch 'abr/fix/public-sim' into 'humble-devel'
  fix public sim
  See merge request robots/pmb2_navigation!96
* fix public sim
* Contributors: antoniobrandi

4.1.0 (2024-08-06)
------------------
* Merge branch 'air/unify_pkgs' into 'humble-devel'
  restructure pmb2 launch file
  See merge request robots/pmb2_navigation!95
* Unify quotation marks
* Unify quotation marks
* add launch_pal dependency
* restructure pmb2 launch file
* Contributors: Aina, antoniobrandi

4.0.23 (2024-07-12)
-------------------
* Merge branch 'feat/aca/pipeline-substitution' into 'humble-devel'
  using variables laser pipeline
  See merge request robots/pmb2_navigation!91
* reorganized remappings file
* added device number laser
* Contributors: andreacapodacqua

4.0.22 (2024-07-09)
-------------------
* Add warning for pal_module_cmake not found
* Contributors: Noel Jimenez

4.0.21 (2024-07-01)
-------------------
* Merge branch 'abr/feat/advanced-navigation' into 'humble-devel'
  using costmap with filters
  See merge request robots/pmb2_navigation!93
* using costmap with filters
* Contributors: antoniobrandi

4.0.20 (2024-06-25)
-------------------
* Merge branch 'abr/feat/rviz-nav' into 'humble-devel'
  move rviz in nav launch file
  See merge request robots/pmb2_navigation!92
* move rviz in nav launch file
* Contributors: antoniobrandi

4.0.19 (2024-06-18)
-------------------
* fix incorrect map path
* Contributors: David Brown

4.0.18 (2024-06-03)
-------------------

4.0.17 (2024-05-29)
-------------------
* Merge branch 'fix/aca/public-sim' into 'humble-devel'
  fix public sim
  See merge request robots/pmb2_navigation!88
* fix public sim
* Contributors: Noel Jimenez, andreacapodacqua

4.0.16 (2024-05-09)
-------------------
* Merge branch 'fix/aca/module' into 'humble-devel'
  moved module to 00 and fix pal module dep
  See merge request robots/pmb2_navigation!85
* moved module to 00 and fix pal module dep
* Contributors: andreacapodacqua

4.0.15 (2024-04-29)
-------------------
* Merge branch 'abr/feat/deprecate-maps' into 'humble-devel'
  deprecate pmb2_maps
  See merge request robots/pmb2_navigation!84
* deprecated pmb2_maps
* Contributors: antoniobrandi

4.0.14 (2024-04-23)
-------------------
* Merge branch 'feat/variables' into 'humble-devel'
  using variables for pipelines
  See merge request robots/pmb2_navigation!83
* using variables in lifecycle manager
* using new variables names
* using variables
* Contributors: andreacapodacqua, josegarcia

4.0.13 (2024-04-11)
-------------------
* Merge branch 'feat/ros2-pipelines' into 'humble-devel'
  Feat/ros2 pipelines
  See merge request robots/pmb2_navigation!82
* cosmetic and removed unused launch files laser
* public sim launch change and renamed pipeline
* fix public_sim condition
* params laser pipeline and modified slam arg
* linters
* modified params
* linters
* navigation pipeline integration for private sim
* fear navigation pipelines
* navigation pipeline
* Contributors: andreacapodacqua, antoniobrandi

4.0.12 (2024-02-13)
-------------------
* Merge branch 'abr/fix/world-name' into 'humble-devel'
  set default world_name for standalone navigation
  See merge request robots/pmb2_navigation!80
* set default world_name for standalone navigation
* Contributors: antoniobrandi

4.0.11 (2024-02-12)
-------------------
* Merge branch 'fix/pal_nav2_bringup' into 'humble-devel'
  Use pal_nav2_bringup only for private simulation
  See merge request robots/pmb2_navigation!79
* Use pal_nav2_bringup only for private simulation
* Contributors: Noel Jimenez, antoniobrandi

4.0.10 (2024-02-02)
-------------------
* Merge branch 'feat/register-components' into 'humble-devel'
  using components and parameters
  See merge request robots/pmb2_navigation!78
* linters
* removing defaults
* update remappings for real robot
* simplify launch files and adapt for public_sim
* adding nav config for composition and standalone
* using pal_nav2_bringup
* using components and parameters
* Contributors: antoniobrandi

4.0.9 (2023-12-18)
------------------
* Merge branch 'fix/clean' into 'humble-devel'
  Clean old scripts
  See merge request robots/pmb2_navigation!77
* Clean old scripts
* Contributors: Noel Jimenez, antoniobrandi

4.0.8 (2023-11-14)
------------------
* Add website tag
* Contributors: Noel Jimenez

4.0.7 (2023-11-07)
------------------

4.0.6 (2023-09-20)
------------------
* Merge branch 'remove_pal_flags_dependency' into 'humble-devel'
  Remove pal flags dependency
  See merge request robots/pmb2_navigation!72
* Remove pal flags dependency
* Contributors: Jordan Palacios, Noel Jimenez

4.0.5 (2023-06-16)
------------------
* Merge branch 'feat/laser-filters' into 'humble-devel'
  using laser filters in simulation
  See merge request robots/pmb2_navigation!70
* changed is_public_sim arg order
* clarifying remapping file usage
* declaring is_sim before using it
* added private dependencies
* added is_public_sim argument
* added is_public_sim
* updated dependencies and rviz config
* using sim bringup
* fix linter
* start laser filters for simulation
* using laser filters in simulation
* Contributors: antoniobrandi

4.0.4 (2023-04-28)
------------------
* Setting odom topic
* Contributors: antoniobrandi

4.0.3 (2023-04-14)
------------------

4.0.2 (2023-04-05)
------------------
* Merge branch 'laser_migration' into 'humble-devel'
  Migrate laser_sensors
  See merge request robots/pmb2_navigation!66
* removed commented deps
* sick_tim laser migration
* Contributors: antoniobrandi

4.0.1 (2023-04-03)
------------------
* Merge branch 'feat/nav' into 'humble-devel'
  Using pal_navigation_cfg
  See merge request robots/pmb2_navigation!64
* Using pal_navigation_cfg
* Contributors: antoniobrandi

4.0.0 (2022-12-15)
------------------
* Merge pull request #1 from jmguerreroh/humble-devel
  Enhancing Tiago's navigation parameters
* Updating Tiago parameters
* Enhancing Tiago's navigation parameters
* Contributors: Sai Kishor Kothakota, jmguerreroh

3.0.2 (2022-10-21)
------------------
* Merge branch 'missing_dependency' into 'humble-devel'
  add missing dependency
  See merge request robots/pmb2_navigation!58
* add missing dependencies
* Merge branch 'initial_pose' into 'humble-devel'
  Set initial pose automatically
  See merge request robots/pmb2_navigation!57
* set initial pose automatically
* Merge branch 'update_copyright' into 'humble-devel'
  Update copyright
  See merge request robots/pmb2_navigation!56
* update package format
* update copyright
* Merge branch 'update_maintainers' into 'humble-devel'
  Update maintainers
  See merge request robots/pmb2_navigation!55
* update maintainers
* Merge branch 'fix_robot_model_type' into 'humble-devel'
  humble fixes
  See merge request robots/pmb2_navigation!54
* linters
* use args for rviz
* update nav2 params file
* update nav2_bringup arguments
* update robot_model_type for humble
* Merge branch 'fix_bt_navigator' into 'galactic-devel'
  fix  bt_navigator libraries
  See merge request robots/pmb2_navigation!52
* undo change transform_timeout
* add bt_navigator libraries
* Contributors: Jordan Palacios, Noel Jimenez

3.0.1 (2021-07-14)
------------------
* Add missing ament_cmake_auto dependency
* Contributors: Victor Lopez

3.0.0 (2021-07-12)
------------------
* Remove ROS1 launch files
* Comment dependencies pending to be migrated to ROS2
* Fix costmaps and increase max velocity
* Revert "Fix usage of map argument"
  This reverts commit 22d9e4a02b93fa5e9016738312538740a8c7e376.
  Specifying full path is more work but more flexible
* Fix usage of map argument
* Reduce max speeds to avoid crashing into walls
  A similara issue seems to be reported in:
  https://github.com/ros-planning/navigation2/issues/938
  Probably we need more tunning for our robot and/or a different
  controller
* Fixes for slam
* More linter fixes
* Remove hard coded map
* First working pmb2_nav_bringup launch file
* Contributors: Victor Lopez

2.0.8 (2020-07-30)
------------------
* Merge branch 'rename_tf_prefix' into 'erbium-devel'
  Rename tf_prefix to robot_namespace
  See merge request robots/pmb2_navigation!46
* Rename tf_prefix to robot_namespace
* Contributors: davidfernandez, victor

2.0.7 (2020-07-02)
------------------

2.0.6 (2020-04-02)
------------------

2.0.5 (2019-11-22)
------------------
* passing subtype parameter to move_base
* Contributors: federiconardi

2.0.4 (2019-10-01)
------------------

2.0.3 (2019-09-23)
------------------
* use scan_raw for mapping
* Contributors: Procópio Stein

2.0.2 (2019-09-18)
------------------

2.0.1 (2019-07-19)
------------------
* Merge branch 'multi_pmb2' into 'erbium-devel'
  Add multi pmb2 navigation
  See merge request robots/pmb2_navigation!40
* Add multi pmb2 navigation
* Contributors: Adria Roig, Victor Lopez

2.0.0 (2019-06-17)
------------------
* added pal_navigation_cfg_pmb2 dependency
* moved config and launch to pal_navigation_cfg_pmb2
* Contributors: Procópio Stein, Sai Kishor Kothakota

1.0.6 (2019-05-20)
------------------
* Merge branch 'update_adv_nav' into 'erbium-devel'
  Update AdvNav Rviz config
  See merge request robots/pmb2_navigation!38
* Update AdvNav Rviz config
* Contributors: Victor Lopez, davidfernandez

1.0.5 (2019-05-06)
------------------
* updated teb config to match tiago's
* Contributors: Procópio Stein

1.0.4 (2019-03-22)
------------------
* Merge branch 'update-karto-cfg' into 'erbium-devel'
  updated karto params to improve loop closures
  See merge request robots/pmb2_navigation!36
* updated karto params to improve loop closures
* Contributors: Procópio Stein

1.0.3 (2019-01-25)
------------------
* Merge branch 'public_eband_conf' into 'erbium-devel'
  added eband planner config
  See merge request robots/pmb2_navigation!35
* added eband planner config
* Merge branch 'plugin_fix' into 'erbium-devel'
  public simulation plugin fix
  See merge request robots/pmb2_navigation!34
* public simulation plugin fix
* Contributors: Sai Kishor Kothakota, Victor Lopez

1.0.2 (2019-01-17)
------------------
* Merge branch 'public_sim_kinetic' into 'erbium-devel'
  add Kinetic pulbic simulation changes
  See merge request robots/pmb2_navigation!33
* add kinetic public simulation changes
* Contributors: Sai Kishor Kothakota, Victor Lopez

1.0.1 (2019-01-15)
------------------
* Fix typo
* Contributors: Victor Lopez

1.0.0 (2018-12-19)
------------------
* Merge branch 'specifics-refactor' into 'erbium-devel'
  Specifics refactor
  See merge request robots/pmb2_navigation!30
* Cosmetic
* Add parameters for using rgbd
* Specify one karto file per laser model
* Contributors: Victor Lopez

0.13.17 (2018-12-19)
--------------------
* change the param load order to overrite the karto config
* activated latch xy for goals
* Contributors: Procópio Stein

0.13.16 (2018-11-21)
--------------------
* added sonar layer
* added sound feedback for loop closure
* Contributors: Procópio Stein, Sai Kishor Kothakota

0.13.15 (2018-10-20)
--------------------
* Merge branch 'clear-vo-on-recovery' into 'dubnium-devel'
  added vo clearing in recovery behavior
  See merge request robots/pmb2_navigation!25
* added vo clearing in recovery behavior
* Contributors: Procópio Stein

0.13.14 (2018-10-03)
--------------------
* updated costmaps config to correspond to template generation
* Contributors: Procópio Stein

0.13.13 (2018-09-28)
--------------------
* slightly increased max_threshold from 1.5 to 1.8
* Contributors: Procópio Stein

0.13.12 (2018-09-26)
--------------------
* changed param name from threshold to max_threshold
* removed deprecated parameter
* Contributors: Procópio Stein

0.13.11 (2018-09-26)
--------------------
* Merge branch 'adjust-plp-params' into 'dubnium-devel'
  increased max threshold and reduced security
  See merge request robots/pmb2_navigation!23
* increased max threshold and reduced security
* Contributors: Procópio Stein

0.13.10 (2018-09-17)
--------------------
* increased plp threshold
* updated recovery to match cobra, but commented blanking recoveries
* updated rviz config
* enabled search alternative goals
* reduced pub freq of costmaps, cleaned them up
* adjusted default threshold and sec distance
* better visualization
* updated pal_local_planner config
* Contributors: Procópio Stein

0.13.9 (2018-06-22)
-------------------

0.13.8 (2018-05-17)
-------------------
* updated amcl and karto configs for clarity and to match last developments in specifics
* added odom filter config and changed search path to pmb2_2dnav
* Contributors: Procópio Stein

0.13.7 (2018-05-15)
-------------------
* added slippage related launch files
* Contributors: Procópio Stein

0.13.6 (2018-04-24)
-------------------
* Revert "avoid oscillating global path and prefer shorter paths"
  This reverts commit 0d0601e59441e560ffb56ce15d7cb37bce0a9d71.
* Contributors: Procópio Stein

0.13.5 (2018-04-17)
-------------------

0.13.4 (2018-04-12)
-------------------

0.13.3 (2018-04-06)
-------------------
* added TEB config
* disable navigation in unknown
* added dependency on range layer and teb local planner
* avoid oscillating global path and prefer shorter paths
* Contributors: Procópio Stein

0.13.2 (2018-03-08)
-------------------

0.13.1 (2018-02-15)
-------------------
* Merge branch 'respawn-move-base' into 'dubnium-devel'
  added respawn flag to move_base.launch
  See merge request robots/pmb2_navigation!11
* added respawn flag to move_base.launch
* Contributors: Procópio Stein

0.13.0 (2018-02-01)
-------------------

0.12.0 (2017-10-17)
-------------------
* updated parameter due to refactoring in pal-local-planner
* Contributors: Procópio Stein

0.11.10 (2017-09-27)
--------------------
* normalized package.xml for all packages
* Contributors: Procópio Stein

0.11.9 (2017-09-19)
-------------------
* updated parameters to new pal local planner
* Contributors: Procópio Stein

0.11.8 (2017-09-18)
-------------------
* added config base path arg, so it can load params from .pal
* Contributors: Procópio Stein

0.11.7 (2017-08-08)
-------------------
* allow global plan in unkown spaces
* Contributors: Procópio Stein

0.11.6 (2017-07-03)
-------------------

0.11.5 (2017-06-30)
-------------------
* added rotate recovery behavior
* Contributors: Procópio Stein

0.11.4 (2017-06-30)
-------------------

0.11.3 (2017-06-01)
-------------------

0.11.2 (2017-04-25)
-------------------
* updated adv nav rviz config
* Contributors: Procópio Stein

0.11.1 (2017-04-22)
-------------------
* added advanced nav config
* Contributors: Procópio Stein

0.11.0 (2017-02-28)
-------------------
* removed legacy move_base configs
* updated costmap files to match template
* fixed global planner config file
* updated rviz navigation config
* 0.10.4
* changelogs
* updated costmap and recovery params
* fixed robot radius
* Contributors: Procópio Stein

0.10.4 (2017-02-28)
-------------------
* updated costmap and recovery params
* fixed robot radius
* Contributors: Procópio Stein

0.10.3 (2017-02-24)
-------------------
* enhanced navigation config, fixed recovery behaviors
* Contributors: Procópio Stein

0.10.2 (2017-02-23)
-------------------

0.10.1 (2017-02-23)
-------------------
* removed rgbd launches and config, fixed dependencies
* minor changes in mapping and localization config
* better mapping and slam configurations
* updated local_planner config for enhanced version of planner
* updated costmap config based on new tiago files
* add rviz launch file
* Contributors: Jeremie Deray, Procópio Stein

0.10.0 (2016-03-15)
-------------------
* use degree
* Contributors: Jeremie Deray

0.9.15 (2016-03-10)
-------------------
* missing deps maps
* Contributors: Jeremie Deray

0.9.14 (2016-03-02)
-------------------

0.9.13 (2016-02-10)
-------------------

0.9.12 (2016-02-10)
-------------------

0.9.11 (2016-02-09)
-------------------

0.9.10 (2016-02-09)
-------------------
* final review of parameters with jeremie
* restoring plugins in costmaps (but commented)
* correcting errors in pm2_2dnav
  restored amcl laser range to default values, corrected typo in local costmap, removed plugins example
* minor cleaning in pmb2 navigation files
* cleaned generic pmb2_2dnav and improved specific pmb2_5_2dnav
* Contributors: Procopio Stein, procopiostein

0.9.9 (2015-10-26)
------------------
* disable free space mapping for pmb2 & add warning abt it
* Fixing localization amcl jumps
* update rviz conf
* Custom launch file for pmb2-5
* Contributors: Jeremie Deray, Luca Marchionni

0.9.8 (2015-10-01)
------------------
* typo
* add slam graph display to rviz
* amcl laser min/max range
* karto laser max_range
* karto map free space
* reduce global inflation radius
* reduce visualization pub rate
* amcl config add param defaut value + comments
* rviz do not display sonar/rgbd related stuff
* do not launch xtion related stuff
* deactivate rgbd layer for costmaps
* Add laser classification displays
* Sync filter script with ant
* Sync with ant_2dnav
* Add covariance (odometry + pose) displays
  NOTE they are disabled by default because they have some issues yet
  with the 6DOF mode property, which is not disabled properly on startup
* Update layout and add inertia + CoM marker
* Update rviz layout
* Increase the number of sonars from 3 to 5
* Contributors: Enrique Fernandez, Jeremie Deray

0.9.7 (2015-02-02)
------------------
* Replace ant -> pmb2
* Rename files
* Contributors: Enrique Fernandez
