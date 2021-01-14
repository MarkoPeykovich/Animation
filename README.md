# Animation
THREE.js Animation

This is a THREE.js Animation. The basic idea for this animation came from one you-tube tutorial called "Three.js Crash Course for Absolute 
Beginners - 3D in the Browser". I've decided to change it to a certain degree. First, in my animation the objects move not by click-event 
or mouse-event, rather they move automatically, once the animation has started, i.e. once one opens the index.html file in the browser and
all the objects have received their random x,y,z positions. Secondly, my animation has four different geometries of objects used (BoxGeometry, 
ConeGeometry, TorusGeometry, CylinderGeometry) not just BoxGeometry. Thirdly, these four types of objects are scattered across four parts 
of the screen and they move back and forth (via TimelineMax) and rotate around x or y axis, with width/2 and height/2 of the screen as quasi 
boundaries between the four respective parts of the screen to which these objects belong.
