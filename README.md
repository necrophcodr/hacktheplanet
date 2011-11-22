Hack The Planet
===============
1. Introduction
2. Instructions
	* Windows
	* Linux
3. [License][1]
[1]: https://github.com/mastersrp/hacktheplanet/blob/master/COPYING.txt "COPYING.txt"

1- Introduction
---------------
The HackThePlanet project is NOT distributed in binary form, and therefore you must follow the instructions in section 2 in order to run the application.
The project is first, and foremost, an attempt to promote education and learning. Hence the entire application in it's source code form is released under the license mentioned here: [License][1].

2- Instructions
---------------
* Global requirements
* Windows
* Linux

*Global requirements*  
To build the application in any environment, you'll need the following software installed.  
You'll also need to make sure that it's accessible in the include and linker directories.  
[lua][]  (v 5.1)  
[boost][]  (v 1.47.0)  
  
*Windows*  
To build the application in Windows, you will need the following tools.  
[CMake][]  (v 2.8)  
[Visual Studio 2010][] or [MinGW][]  
  
*Linux*  
To build the application in Linux, you will need the following tools  
[gcc][]  (v 4.5 or better)  
[CMake][]  (v 2.8)  
  
Both should be available in your package manager, or already installed.
Run ./build.sh to build the files.
Then run HackThePlanet in the bin directory.

[CMake]: www.cmake.org "CMake"
[gcc]: gcc.gnu.org "GCC"
[Visual Studio 2010]: www.microsoft.com/visualstudio/ "Visual Studio 2010"
[MinGW]: www.mingw.org "MinGW"
[lua]: www.lua.org "Lua"
[boost]: www.boost.org "Boost"
