# OPENCV-PREBUILT

* This repository provides varieties of pre-built opencv binaries for major platforms, such as 
windows x64, linux arm-32bit(raspian) ... etc

* Users can link their project to desired version of pre-built binary using build tools, such as CMake.

* This saves a lot of time for application designers, programmers, and anyone who don't want to spend time on building binaries from source code.

## HOW TO USE:

1. Main branch is intentionally left blank.
2. Binary files of different version can be recognized by branch name. 
(If detailed build configuration concerns you, please take a look at README of that branch)
3. Clone specific version of binary using 
   
   #### git clone -b [branch-name] --single-branch https://github.com/harry123493/opencv-prebuilt.git
   OR
   #### git clone -branch [brach-name] -- single-branch https://github.com/harry123493/opencv-prebuilt.git

4. (Optional) Fetch binaries using CMake at configuration time, please refer to cmake documentation:
   https://cmake.org/cmake/help/latest/module/ExternalProject.html