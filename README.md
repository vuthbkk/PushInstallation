# PushInstallation
Push Program Installation <br>
This Python script compose of 3 main steps. <br>
1. Run 01_Check Target ComputerName Online Status, this is to check whether the computer in the list is alive and ready for next step (transfer installation source to target computer) or not. The output of this step will generate text file with ping result of each target computers. <br>
2. Run 02_Copy file to online computer, this is to push installation to the list of target computer. The output of this step will generate the text file with file transfer result of each target computers. <br>
3. The last 03_Run Command_Reset SCCM GUID, this file will use PSexec function to remotely setup SCCM application.  The output of this step will generate the text file with PSexec result. <br>
