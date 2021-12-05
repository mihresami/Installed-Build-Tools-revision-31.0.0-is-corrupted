# Installed-Build-Tools-revision-31.0.0-is-corrupted
Android Studio error "Installed Build Tools revision 31.0.0 is corrupted"
Here is the solution
Go to the build.gradle in the project and open it then, change 
andorid{
compileSdkVersion into 30 and 
buildToolVesrion into 30.0.0
}
then  
chnage targetSdkVersion into 30 in the 
defaultConfig{
....
...
}
for details see the screenshot.
Thanks!

