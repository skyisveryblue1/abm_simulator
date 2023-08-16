# abm_simulator
Simulator for running abstract machine with dual cores implemented by Java

1.	Introduction of System
This project is a system as a simulator for running abstract machine with dual cores.
Here we will introduce about diagram of the simulator.

1.1.	Diagram 
<br/>
 ![image](https://github.com/skyisveryblue1/abm_simulator/assets/119230301/46033393-2f36-467c-b584-bc4f46479fd5)
<br/>
Figure 1. Diagram of ABM Simulator with dual core.

1.2.	Structure of project
1.2.1.	  ABMSimulator2
This component is implemented by ABMSimulator2 Java class and is used for:
-	Creating Menu Bar and Other UI components including panels and text areas
-	Adding additional component
-	Initializing two cores of simulator

1.2.2.	 ABMSimulatorCore
This component is implemented by ABMSimulatorCore Java class, an inner class of  ABMSimulator2 class and is used for: 
-	Creating local variables of one ABMSimulator core.
-	Loading content of abm file.
-	Running abm commands and outputting its result.
1.2.3.	 addActionListener
This functions are used to process the actions of user through UI menu button components and are used for :
-	Browsing abm files through File selector.
-	Running  the simulator.

2.	User Guide
2.1.	How to install environment?
-	Install JDK +1.8
-	Install VSCode 
-	Install Java Extension.
2.2.	What operating system was used?
MacOS/Linux
2.3.	How to compile your program?
It can be compiled by using VSCode and other tools includes IntelliJ IDE and so on.

2.4.	How to run the program?
-	Step1:  Open the ABMSimulator2.Java by VSCode and execute the program.
![image](https://github.com/skyisveryblue1/abm_simulator/assets/119230301/6f1bb960-f6aa-4040-9b4c-cb6dd1fb1f41)
 
-	Stem2: After open window, click the “File/Open” menu button.
 
-	Step 3:  Press the “Run” menu button.
 ![image](https://github.com/skyisveryblue1/abm_simulator/assets/119230301/048a6197-b930-4e73-b619-62a0a4de26bb)

3.	Test Result
Open “test1forP2.abm” and Run then gives the following result:
 ![image](https://github.com/skyisveryblue1/abm_simulator/assets/119230301/9ef55fc4-13aa-470d-b27a-0aa4b49159ae)


 

