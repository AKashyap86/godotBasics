# godotEssentials
This is a repository which will contain essential information including links to tutorials about godot engine . For starters I will post links to what all modules I used in making my game, but later on it will contain more complex creations, including my creations if needed.

NOTE: This piece of information might consist develepomental meddling so it is not for everyone! Also this is not so advanced , so this is a good medium step I think. You can try if you have got the basics covered up.


------------------------------------------------------------------------
HOW TO MAKE A GAME FOR ANDROID AND LINUX USING GODOT ENGINE 
------------------------------------------------------------------

Step1 --> Download godot engine !!

https://github.com/godotengine/godot

How to build godot for linux -->

http://docs.godotengine.org/en/3.0/development/compiling/compiling_for_x11.html

Optimized steps I followed for my system -->

scons -j6 platform=x11

How to build godot for android -->

http://docs.godotengine.org/en/3.0/development/compiling/compiling_for_android.html

Optimized steps I followed for my system -->

scons -j6 platform=android target=release
scons -j6 platform=android target=release android_arch=x86

This will cover mostly targeting android and operating system for godot x11 as linux

If problems check that you have followed all steps in installing dependencies, sometimes copy pasting everything does not install all software, and you might need to manually install the other software

If any problems apart from this, do the simple steps below -->

--> Update your operating system. Then keep updating it every once in a while.
Linux commands to update the computer-->
sudo apt update && sudo apt upgrade
sudo apt autoremove
sudo apt dist-upgrade
sudo do-release-upgrade
There might be other commands at times but these are basic which are needed to do it.

--> Update the graphics drivers.
Linux, in start, system tools, software updater, settings -->
then set it to proprietary best driver, maybe one which you have downloaded from your graphics card manufacturers site.


--> Update the engine version.
well download and compile again for both the systems



Godot 2 to godot 3 transition.
1--> Use the in engine converter.
2--> Then, completely remove, HButtonArray VButtonArray etc, also from code other wise game will crash as per time of using godot 3.0.2 (roughly)
3--> Then I also needed to change my character (GUI primarily, and animations, some values were different.)
4--> Then it worked perfect, and working in dev 3.1 
5--> Except shaders of course on mobile. But works perfectly on linux.

So now you got your game running shaders in godot 3.1 dev on linux and able to test all using the upcooming code. More coming in future update including codes. !!
A lot of that will be my own creation

----------------------------
MODULES USED
--------------------------
1 --> Godot Ads AIO by frogsquare https://github.com/FrogSquare/GodotAds simply because it has so many ad modules
2 --> Godot gpgs by Kopfenheim https://github.com/Kopfenheim/godot-gpgs simply because of sheer level of documentation


