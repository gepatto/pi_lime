# pi lime

## SDL2 files and Build.xml for Lime for Raspberry Pi   

until the lib submodules in Lime point to regular repositories  
this is a repository that holds files you need to replace   
when you checkout out Lime from Git on a Raspberry Pi running bullseye.


>project/Build.xml  
>project/lib/sdl
   

replace the file and directory in your clones lime repo and run   
`lime rebuild lime linux -v -rpi`

You can use [https://github.com/gepatto/pisetup/](https://github.com/gepatto/pisetup/)   
to setup haxe from docker on your raspberry pi.
