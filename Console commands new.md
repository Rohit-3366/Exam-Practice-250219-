#WMIC- windows management instrumentation command line




how to open window management instrumentation command line
open command prompt in your system
now command the wmic cpu get caption, name, deviced, numberforcesstatus
now you will gat various information regarding your cpu used on your computer
>wmic cpu get caption, name, deviceid, numberofcores, maxclockspeed, status


Caption                                DeviceID  MaxClockSpeed  Name                                 NumberOfCores  Status
Intel64 Family 6 Model 183 Stepping 1  CPU0      2100           13th Gen Intel(R) Core(TM) i7-13700  16             OK  

this link is from sciencedirect website 
https://www.sciencedirect.com/topics/computer-science/wmic-command


this link is from askgarth website 
https://askgarth.com/blog/how-to-use-wmic/


this link is from techtarget t
https://www.techtarget.com/searchwindowsserver/definition/Windows-Management-Instrumentation




three example to display information of your disk, memory, video card 
 first way give the command wmic logicaldisk get name
other way is wmic path win32_videocontroller get name,adapterram,driversion
and 3rd option wmic os list brief
