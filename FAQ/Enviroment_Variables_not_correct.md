An common error is:
'python' is not recognized as an internal or external command,
operable program or batch file.
or:
'pip' is not recognized as an internal or external command,
operable program or batch file.

Lucky for you, this error is easy to solve!

###What's wrong:
Windows defines command in something called "enviroment variables", if an program is not in here, Windows does not understand what you mean
###How to solve this:
If you install python, it can automatically set the correct enviroment variables, if you did not click this option, we are going to do this manually
###How to set them manually:
Step 1]	Press Windowskey + Pause/Break (Or rightlick on "This Pc" and select properties)
<p align="center">
<img src="https://i.imgur.com/w77iL4P.png">
</p>
Step 2] Click on "Advanced system settings", an new window appears, now click on "enviroment variables..."
<p align="center">
<img src="https://i.imgur.com/3I8TVKx.png">
</p>
Step 3] Another window pops up, now find "Path" and click "Edit...", now another window pops up.
<p align="center">
<img src="https://i.imgur.com/lrpEZcq.png">
</p>
Step 4] Hit "New" and enter "C:/Python27", hit "New" an 2nd time, now enter "C:/Python27/Scripts"
<p align="center">
<img src="https://i.imgur.com/DHSd2x8.png">
</p>
Step 5] Close all the windows by pressing "OK", and restart the command promp, now it should be working!
