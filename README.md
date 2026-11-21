--- LAB DISCUSSION --- 

LabAct0: I started by downloading the Android Studio App. Once I clicked the Download button,
it took a very long time-about 5-10 minutes- before I even saw any progress. After the download 
finished, I opened the app immediately, but there were still many steps to go through. 
I got a bit nervous when a prompt appeared suggesting that the laptop needed to be
rebooted to open the app; I was worried that all my data, files,  and everything else on laptop 
might be lost. It turned out I was mistaken-it was just a simple restart. So once the laptop 
has restarted, I proceeded with the activity and followed all the steps provided on teams. 
I encountered some errors, but I looked up how to  fix them and also asked an acquaintance for help; 
in the end, everything was resolved succesfully. Moreover, I also struggle connecting my project to
GitHub because I don't have account so I have to sign up first and the terminal kept giving me 
errors.By doing careful troubleshooting and running the correct Git commands, 
I was able to overcome all the challenges.

LabAct1: In this activity, I saw what happens to the Activity lifecycle when I rotate the 
screen and when I press the Home button. When I rotate the screen, the Activity gets destroyed
and made again, and it keeps the saved text unless I clear it. When I press the Home button, the 
app just goes to the background (onPause and onStop) and stays in memory, so when I go back, 
it runs  onRestart, onStart, and so on. Using Logcat helped me check the right order 
and time of the lifecycle states and see when I clicked Log Check-In Heartbeat or Clear Log.
For setup and Gradle sync problems, turning on viewBinding in build.gradle.kts, 
syncing Gradle, and saving activity_main.xml before building fixed the errors for the banner
and Clear Log button.
 