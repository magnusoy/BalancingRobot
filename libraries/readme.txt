This folder contains my own libraries that are used within the project.

Installation
--------------------------------------------------------------------------------

To install the libraries, just place each of the entire folders as a subfolder in your
Arduino/libraries folder.

When installed, this library should look like:

Arduino/libraries/PID_Controller                      (this library's folder)
Arduino/libraries/PID_Controller/PID.cpp              (the library implementation file)
Arduino/libraries/PID_Controller/PID.h                (the library description file)
Arduino/libraries/PID_Controller/keywords.txt         (the syntax coloring file)
Arduino/libraries/PID_Controller/examples             (the examples in the "open" menu)
Arduino/libraries/PID_Controller/readme.txt           

Arduino/libraries/KalmanFilter                        (this library's folder)
Arduino/libraries/KalmanFilter/KalmanFilter.cpp       (the library implementation file)
Arduino/libraries/KalmanFilter/KalmanFilter.h         (the library description file)
Arduino/libraries/KalmanFilter/keywords.txt           (the syntax coloring file)
Arduino/libraries/KalmanFilter/examples               (the examples in the "open" menu)
Arduino/libraries/KalmanFilter/readme.txt             

Building
--------------------------------------------------------------------------------

After this library is installed, you just have to start the Arduino application.
You may see a few warning messages as it's built.

To use this library in a sketch, go to the Sketch | Import Library menu and
select PID or KalmanFilter. This will add a corresponding line to the top of your sketch:
#include <PID.h> or #include <KalmanFilter.h>

To stop using this library, delete that line from your sketch.
