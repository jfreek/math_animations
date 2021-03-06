# math_animations

Project with animations for mathematical objects, equations and their behavior with python 3.

Still a lot to work to do, but it's useful for simple mathematical examples.
The project is intended to create intuitive animations. 

To create videos I run animations in separate steps and then join each section as complete video.

### Some examples:
A cube skeleton, from geometry folder.

![alt-text](https://github.com/jabud/math_animations/blob/master/examples/cube_skeleton.gif)

Partial derivatives from calculus.

![alt-text](https://github.com/jabud/math_animations/blob/master/examples/derivative.gif)

Error functions from linear regression.

![alt-text](https://github.com/jabud/math_animations/blob/master/examples/e3e4.gif)

### Libraries
I am using mainly matplotlib, although I added a few libraries for animations in the requirements.txt file, 
since I use them from time to time, as openCV, pygame, moviepy, glfw, glumpy, etc 
(Some scripts are 3D animations and games for example).

### Fonts
There is a font I use for some scripts, you can download it here: https://www.dafont.com/es/alterebro-pixel-font.font

All you have to do is save it in this path `python3.6/site-packages/matplotlib/mpl-data/alterebro_pixel_font/alterebro-pixel-font.ttf`
 inside your matplotlib library.
 
 ### Canvas
 Canvas2d still has some features I need to work on, it's animated only for shapes of + and L and the switch between them.
 
 ### Basic usage
 Each script is a particular math example and they run from the comand line:
 `python path/script.py`
 
 Some of them inherit from canvas2d.
 
 The ones from linear_regression and calculus run using the keyboard. Using numbers from 1 to N, for each step of the animation.
 0 resets the animation.
 
 ... I think that is it, if you have any questions you can send me an email to: jorge.abud@pm.me
