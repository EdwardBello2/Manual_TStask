# Manual_TStask

Summary:
Code to execute a simple target-appear display figure. No automated touchscreen-detection or reward-delivery included in this code. The assumption is that the trainer will manually control target appearance/disappearance, and closely monitor subject behavior and manually deliver rewards accordingly.

Detailed instructions:
After opening the program, press the "Run" button. To make the circle appear, simply click the "On" button in the Target Appear box, and to make it disappear click the "Off button. To disable the program without closing it out, just press "Run" again and it resets everything. 


To open the program: 
The code can be run two ways.
1. Directly thru MATLAB
Code was developed using MATLAB 2021a, but it may be backward compatible as well, worth testing it out if you're not sure. The file to run has a .mlapp extension, which is a "matlab app" (look up matlab documentation on this). It's essentially a GUI. Assuming that Matlab 2021a is installed on your machine, just open "manualTargetAppear.mlapp" thru the interface in Matlab, or else just double-click the file and Matlab should open it. 

2. As a standalone executable program
This part is more new to me (Ed), but I figured I'd include it as an option. It may or may not be a good option! To run the code, run "manualTargetAppear.exe" found in "\manualTargetAppear\for_redistribution_files_only\". If that doesn't work, try running "MyAppInstaller_mcr.exe" found in "\manualTargetAppear\for_redistribution\" to run an installation wizard much like other things we often install. 



Change Log:

Added in edit fileds to change circular target size and position, set within now enforced axes limits between 0 and 10 for both x- ans y-coordinates.

v1.0.0
Program runs stably, at least with a Matlab 2021a installation on the PC running it.
Basic version of the program, with target appearance and disappearance controlled manually by the user. See README file for details.

