^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package flea3
^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.1 (2015-11-06)
------------------
* fix compiler warning of no return
* update
* move strobe setting in front of trigger setting, such that turning off strobe will not set all gpio pin direction to output
* fix stereo launch file
* add a nodelet
* update documentation
* restore strobe
* fix always firing software trigger when what we want is only external trigger, dumb.
* Merge pull request `#4 <https://github.com/clearpathrobotics/flea3/issues/4>`_ from KumarRobotics/catkin_install_targets
  added catkin install targets
* added catkin install targets
* fix typo in StartCapture, get rid of a try/catch block
* Update package.xml
* Update README.md
* Update README.md
* make roi limits bigger
* fix GetShutterTimeSec
* simplifies logic in setting video mode
* update launch file to include new params
* bump version for no reason
* Turn off strobe when node shuts down
* add hacky strobe and trigger control, something was wrong
* replace PgrError with PgrWarn in some non-essential functions
* update launch file
* fix frame rate being set to max when enable trigger is on
* remove some duplicated SetProperty
* fix shutter unit
* add unit to some of the camera parameters
* add image metadata message
* Merge pull request `#3 <https://github.com/clearpathrobotics/flea3/issues/3>`_ from KumarRobotics/refactor/grasshopper3
  Refactor/grasshopper3
* update roi limit
* add more pixel format
* fix exposure, gain, shutter
* fix white balance
* need to fix whitebalance
* fix raw bayer output
* fix frame rate setting
* move frame rate setting out of video mode setting
* working format7 settings
* Remove some one-line function
  Get rid of PGERROR macro
  Add parameter for setting roi, not implemented
  update README
* remove cout
* Merge branch 'refactor/speed-up-compilation' of https://github.com/KumarRobotics/flea3 into refactor/speed-up-compilation
* add raw_bayer_output option for standard video mode
* shit
* Merge branch 'refactor/speed-up-compilation' of https://github.com/KumarRobotics/flea3 into refactor/speed-up-compilation
* exposure compensation should be divided by 2
* add interface type to list_cameras
* add some flycapture examples
* I hope this fucking hack works otherwise I will not use point grey product ever
* add todo
* more moving around
* move more low level functions to flea3_setting
* move some functions to flea3_setting
* move some definition to cpp files
* Merge pull request `#2 <https://github.com/clearpathrobotics/flea3/issues/2>`_ from KumarRobotics/feature/stereo
  Feature/stereo
* better readme
* not throw when read register failed
* sync result is ok
* simple stereo node, same structure as bluefox2
* adding stereo
* Update README.md
* Update README.md
* add software trigger functionality, external trigger is still not supported
* Merge branch 'master' of https://github.com/KumarRobotics/flea3
* remove debug prints in driver
* Update README.md
* Merge branch 'master' of https://github.com/KumarRobotics/flea3
* trivial
* Update README.md
* fix dynamic reconfigure crash because of number exceeds int_t, now frame rate reaches 120 at some setting
* Update README.md
* increase upper range of fps
* small updates and add some comments
* Update README.md
* Update README.md
* Merge branch 'master' of https://github.com/versatran01/flea3
* give zero fuck when camera failes to connect and try again
* Update README.md
* fix logic in AutoWhiteBalance
* Update README.md
* Merge pull request `#1 <https://github.com/clearpathrobotics/flea3/issues/1>`_ from versatran01/devel
  Devel
* one bug remains
* add format 7 support
* rqt work with normal video mode
* create readme
* update launch file
* fix typo
* update launch file
* remove GetCameraInfo from constructor
* remove some print statements
* Delete README.md
* Update README.md
* Create README.md
* add most functionality
* working white balance
* videomode and framerate working with hack
* got image
* copy more stuff from old pointgrey_camera_driver
* add GrabImage
* compiles
* compiles
* copy stuff from bluefox2
* update
* first commit
* Contributors: Chao Qu, Dinesh Thakur
