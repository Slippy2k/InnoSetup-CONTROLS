# InnoSetup CONTROLS
<p><b>2023.05.01</b>: Added the possibility (specified from command-line) to examine only one page of the InnoSetup installer (command-line parameter: /OnePage=?). Please look at the included example *.cmd script.</p>
<p>---</p>
If you are starting your adventure with the [code] of InnoSetup, or you just don't know/remember any of the control(s) where they'are belongs...<br>
<br>
You can use my sample named DEMO, to get the information about InnoSetup controls in a simple way.<br>
<br>
It changes the control color when you hover the mouse cursor on it, and adds the frame to the control, with exceptions to change the color of Tbevel and TBitmapImage classes. The DEMO installer shows you information of any control in InnoSetup installer.<br>
<br>
My installer doesn't install anything, nor creates the uninstall entries in the OS registry, all of it it's disabled, so, you don't be to afraid for that.<br>
<br>
Some of the controls are blinking when changing, but I can't do anything with it.<br>
<br>
Some of the controls classes does not have some properties, like a Tbevel and TBitmapImage, so, it doesn't read some properties of them.<br>
<br>
The installer pauses the execution on Prepare2Install, and two Installing steps, so, you can clearly see and check the controls of that steps.<br>
<br>
I've changed some controls position, to show all of them, especially on FinishedPage (last page of the installer).<br>
<br>
Of course, the colors can be changed from the command line. I prepared a sample .CMD script with all possible parameters.<br>
<br>
I hope that this sample will help for all users, who want to improve/extend the [code] of the installer, or just simply find information of an element in the InnoSetup installer.<br>
<br>
Added context help for the UserInfoSerial, if you can't get the right SN, right-click on that control.<br>
<br>
If my work helped you in any way, please support my work also :-)<br>
