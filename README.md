

This command works just fine: 

gradle -b docker.file  startContainer  


This one doesn't

gradle startContainer 

Per issue https://github.com/bmuschko/gradle-docker-plugin/issues/35 it looks like the fix has something to do with the 
difference of the plugins vs apply plugin differences, I just don't know what needs to be done to fix it. 


