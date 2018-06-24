#Example C++ proeject structure using cmake

 main program executable depends on libraries myFunction declared in myFunction.h and defined in myFunction.cpp. This must then be linked in the CMakeLists.txt.
 
 To make an out-of-source build (recommended) create a new folder at the same level as the project
 
 ```
 mkdir build
 ```
 
 Then change to that build folder
 
 ```
 cd build
 ```
 
 Then run the cmake program from the project that should be just above the build folder
 
 ```
 cmake ../cpp-project-structure
 ```
 
 Then using the output makefile to compile the code
 
 ```
 make
 ```
 
 Then run the output binary which should come out in the same folder as the project is run.
 
 ```
 ./output
 ```
 and voila!
 
 
