This project was done as a part of the training course Verification using System Verilog.</br>
It includes the RTL design of a Single port memory module, synchronized with the reference clock which is used by the Driver as well, for data transfer according to the AMBA APB Protocol. The top module instantiates the [Memory module](), [Driver module]() and the [Testbench](). The tb generates random signals (which are constrained to valid values, like word aligned memory address) and feeds them to the driver module. The state machine inside the driver module generates the signals which are in turn fed to the memory module and perform read or write operations across it.  
The outputs generated from the memory are read by the testbench (monitor) back and shown on the display. As a simpler alternative, which gives a wider view over the whole process going on across the various modules, the waveform can also be observed. </br>
[Here](https://www.edaplayground.com/x/mCkg) is the link to the edaplayground where the testbench can be executed and observed.</br> 
The protocol is explained [here](https://developer.arm.com/documentation/ihi0024/c). </br>
Note: 
AMBA - Advanced Microcontroller Bus Architecture, 
APB - Advanced Peripheral Bus </br>
The following diagram gives a brief about the project ![Overview of the Project]()</br>
This is a snippet from the waveform window, which shows the functional correctness of the module ![Waveform]()
