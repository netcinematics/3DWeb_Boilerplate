# BabylonJS_dev_boilerplate
Get set up developing BabylonJS as fast as possible. Utilizes npm http-server and is a baseline for integrating and developing AR.js demos.

- BabylonJS Development Environment - it is very possible to develop Babylon with bigger IDE's - I don't want to.

- my needs require, everything, to be as light as possible in order to maintain maximum flexibility (a requirement for animation mastery)

- so this module is a template environment, and a process, which allows for more rapid animation creation capability.


##First install npm and then npm install -g http-server

 - this will give you a very light-weight server set up (which is a big plus for animation work)

 - you can run that server from anywhere, and all downstream .htmls can be instantly pulled up to view.

 - in my environment, I keep hundreds of downstream .htmls ready for instant review at any moments notice (fast animation)

 ##Run-Server 

 - in command line, in the root directory above your code, run: http-server

 - this will start up a server listening on http://localhost:8080

 - now you can go to the URL:  

 - and see the /demos, this is ideal because it has a fast and wide breadth, as you will see.

 ##Demos

 - in the /demos folder you can iterate into the hundreds of examples.

 - I create a new sub-folder every time I create a new version of an animation.

 - they are all numbered with a postfix naming convention. It is very effective.

 ##Animation-Process

 - first look for /demos/template1, /template2, template3/...

 - these are different versions of templates.

 - when you start a new animation - grab whichever template you need, depending on the task.

 - then pop that new file up in the browers, instantly.

 - now you are ready to rock.

 ##Environment

 - there are important folders at root level with the demos /3d, /img, /lib, /licenses

 - 1. whenever you add an asset to the environment -> add the license to the /licenses folder <- important.
 
 - 2. add assets to either /3d, /img, or /lib.

 - 3. /lib is the best folder because it contains all of the various libraries that create the animation.

 - right now my /lib folder consists of BabylonJS, ThreeJS, ARJS.

 - but in the past it was jQuery, d3, Greensock - we've come a long way.


 I hope this is helpful to you. 