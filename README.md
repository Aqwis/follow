# follow

This code implements the object detection and tracking algorithms described in our report for the course [Experts in Teamwork - Instrumentation and Control via Internet](http://www.ntnu.edu/studies/courses/TMM4850/2013) (TMM4850) at the Norwegian University of Science and Technology.

Unfortunately, while object detection should work under any OS, due to time constraints and the operating systems used by most group members, serial communication will only work on Windows.

## How to use

To compile:

```
cd build/<os>
cmake ../..
make
make install
```

OpenCV 2.4.8 or newer is required to compile the project. The code used for communication on the Arduino is given in the
file `ArduinoKode.cpp`.
