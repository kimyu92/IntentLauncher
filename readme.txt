Import Library to android

This was actually fixed with the new updated 0.2.8 version. 
===========================================================
1. All I did was create a new directory called 'libs' 

2. Dragged the jar file into it. Right click the jar file 'Add as library'. 

3. This will expand the jar file. 

4. Entered this into the build.gradle file 'dependencies { compile files('libs/jtwitter.jar')}. 

5. Entered the import statement to bring the classes into my source file. Everything worked fine.

Source
http://stackoverflow.com/questions/18735923/importing-jar-libraries-into-android-studio
