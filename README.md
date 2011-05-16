You are the man or not
======================
Demo Project Skeleton for Newbie Wannabees

Getting Started
---------------
1. Get a [GitHub](http://github.com) account as soon as possible :P
2. Fork this project by clicking on the **Fork** button.
3. Clone your *fork* by executing `git clone git@github.com:YOUR_GITHUB_USERNAME/YouAreTheManOrNot.git`
4. Start hacking away :)

Demo
----
The purpose of this `Demo Project` is to create a basic 3D asteroid game *clone* with the following
features:

No third party libraries are allowed (including **STL**, **BOOST**, **QT**, **WXWIDGETS**, **MFC** 
but not limited to) except the ones explicitly specified below.

1. **Engine**
	* C/C++ (*required*)
	* OpenGL 2.0 or DirectX 9 (SDL can be used for Window Management)
	* OBJ Model Loader
	* Texture Loader (stb_image.c is provided for image loading)
	* Primitive bounding-box (or bounding-sphere) based collition detection
	* SkyBox
	* Camera (3rd person)
	* Keyboard + Mouse input (again SDL can be used for Input Management)
	* Basic Sound system (based on OpenAL, BASS, FMOD or even SDL)
2. **Game**
	* AI
		* randomly spawn asteroids
	* GUI
		* game start screen
		* game over screen
		* health-bar
		* score/point (-bar)
	* Player
		* control spaceship
		* handling collision detection events (game over, etc)
		* shoot
	* Effects
		* spaceship jet (particles)
		* asteroid / spaceship destruction explosion (particles)
		
**BONUS**: if is portable and truly *cross-platform*.

**NOTE**: there's no need for space partitioning, culling or physics.

*Estimated time of completion*: **2 - 3 weeks**

Libraries
---------
* [stb_image.c](http://nothings.org/)
* [SDL](http://www.libsdl.org/)
* [OpenAL](http://connect.creativelabs.com/openal/default.aspx)
* [BASS](http://www.un4seen.com/)
* [FMOD](http://www.fmod.org/)
