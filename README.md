# gendart

Note to users: If using dart null-safety please use the nullsafety branch. Otherwise use the kinetic-devel (works fine on melodic / noetic as well).


This project was heavily inspired and borrowed a lot of code from [gennodejs](https://github.com/RethinkRobotics-opensource/gennodejs)
Credit goes to the authors of that project for the borrowed code and code architecture.
Their license is included in LICENSE_js


TODO:

you change branch vith nullsafety or new_msgs

if you are using catkin build , it change with catkin_make

if you don't make change catkin build with catkin_make

you must be crate new a workspace and you this repository clone for catkin_make and your workspace build with catkin build 
so clone your workspace this repo and you must be change ~/workspace_ws/devel/lib/pythonX/dist-package/gendart/__init__.py file
inside line 9 catkin build file gendart location
and you catkin_make your new repository

you search new reposityoru (with catkin_make) devel/share/gendart/ros/*
 
you find your msgs dart files

Make generated messages follow code standard.
Have package_name/package_name export both srvs and msgs
