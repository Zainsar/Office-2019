FIRST METHOD 

ctrl + shift + mouse right click

open power shell window here

write this on power shell

.\setup.exe /configure .\configuration-office2019Enterprise.xml

press enter 

SECOND METHOD

STEP 1| FOR ACTIVATION PRODUCT KEY 

OPEN COMMAND PROMPT WITH RUN AS ADMIN

STEP|2

TYPE ALL COMMAND ONE BY ONE 

cd /d %ProgramFiles%\Microsoft Office\Office16
cd /d %ProgramFiles(x86)%\Microsoft Office\Office16

NOTE:-
If you install your Office in the ProgramFiles folder, the path will be “%ProgramFiles%\Microsoft Office\Office16” or “%ProgramFiles(x86)%\Microsoft Office\Office16”. It depends on the architecture of the Windows OS you are using. If you are not sure of this issue, don’t worry, just run both of the commands above. One of them will be not executed and an error message will be printed on the screen.

for /f %x in ('dir /b ..\root\Licenses16\ProPlus2019VL*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"

cscript ospp.vbs /setprt:1688

cscript ospp.vbs /unpkey:6MWKP >nul

cscript ospp.vbs /inpkey:NMMKJ-6RK4F-KMJVX-8D9MJ-6MWKP

cscript ospp.vbs /sethst:107.175.77.7

cscript ospp.vbs /act

Right now the Office is activated successfully.
