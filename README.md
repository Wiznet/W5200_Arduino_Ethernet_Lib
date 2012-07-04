# Arduino Ethernet library using W5200 from [Wiznet](http://www.wiznet.co.kr/)
## How to use:

1. Install W5200 library
   Overwrite w5100.cpp, w5100.h to the "/libraries/Ethernet/utility" folder in your Arduino IDE. 

2. Note: libraries/Ethernet/Ethernet.h needs to change #define MAX_SOCK_NUM 4 to #define MAX_SOCK_NUM 8, since it doesn't #include "w5100.h" anymore
    

3. Using the W5200 library and evaluate existing Ethernet example.
   In the Arduino IDE, go to Files->Examples->Ethernet and open any example, compile and upload the file to Arduino board.


