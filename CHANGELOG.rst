^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pcl_catkin_c11
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.8.3 (2018-10-20)
------------------
* Merge pull request `#1 <https://github.com/LCAS/pcl_catkin/issues/1>`_ from LCAS/submodule
  attempt to build as subdir
* attempt to build as subdir
* Contributors: Marc Hanheide, root

1.8.2 (2018-10-19)
------------------

1.8.1 (2018-10-19)
------------------
* global install prefix
* more deps and renaming
* Update package.xml
* added build dependencies
* initial C++11 LCAS version
* make it compatible with boost 1.67
* add complete VTK cmake magic
* fixed library ending to be compatible with linux machines
* replace FILTER with REMOVE_ITEMs pcl_ros libraries specifically
* handle multiple vtk versions
* exclude libpcl_ros* libraries from the export as they are built with pcl_ros
  This is causing issues otherwise, as they are linked against twice, when
  later building pcl_ros and they were built before.
* VTK wiki page says this is the appropriate way to do it when using VTK 6
* another afternoon of fun with @mfehr and @eggerk fixing VTK dependencies
* fix: added boost dependencies
* addressed @ntonci comment -> removed a message
* afternoon of PCL vs pcl_catkin fun with @mfehr
* fix merge from master
* Merge branch 'master' into adding_submodules
* Updated submodules
* Merge branch 'master' into adding_submodules
* added submodules from pcl_conversions and perception_pcl
  not working yet
* Contributors: Fadri Furrer, Kevin Egger, Marc Hanheide, Marius Fehr, Marko Panjek, root
