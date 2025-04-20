# Penalty Shootout Game

After spending some time learning how to switch between different cameras in the [Unity Game Engine](https://unity.com/) and learning more about colliders , triggers and sound. An idea of creating a humble soccer penalty shootout game came to mind and I took on the challenge. 

The result is this 3D game that has some humble graphics to make the soccer field and the goal post look somewhat realistic , all created with materials from Unity itself. The game consists of a first person point of view behind a ball and an arrow that is constantly moving from left to right. When the player decides that the arrow is aimed directly at the goal post and decides the shoot the ball , the arrow disappears and the ball moves forward in the direction of the arrow. The camera shows the ball moving in action.![Uploading 屏幕截图 2025-04-18 180618.png…]()


If the ball finds its way inside the goal post , a crowd cheers the player on and the level increments by 1. The ball is then reinitialized randomly at a certain place away from the goal post on the field and the player will have to score another goal. Every three levels that the player passes , the speed that the arrow moves left to right in increases in an attempt to make it more difficult for the player to shoot the ball at a good angle to score a goal. 
![Uploading 屏幕截图 2025-04-18 180641.png…]()

Software Purpose
Development Process Selection: Adopt agile development, because the level difficulty and physical parameters need to be adjusted according to player feedback.
Target Market: Casual game platform (such as Steam mini games, web-based H5 games).


The buttons M , L , & R can be used to switch between the main camera  and the left and right side cameras if the player wished to get a better view of the field relative to where the ball is. 

Development Schedule
Phases                     Time Scope        Deliverables 

Requirements Analysis      2025.1.1-1.7      Game Prototype Sketch 
Core Physics Engine        2025.1.8-1.21     Ball Movement and Collision Logic 
UI and Level Design        2025.1.22-2.5     Game Interface, Scoring Panel 
Testing and Optimization   2025.2.6-3.1      Fix Collision BUG 
Documents and Videos       2025.3.2-4.20     README.md, Demo Video 

P2211342  Gary	  Physics engine and core logic	          33.3
P2321361	Oliver	UI design and level implementation	    33.3
p2321186	Tomson	Testing & Documentation	                33.3

Development plan and current status
Completed: basic shooting logic, scoring system.
Future plans: add multiple levels and online battle mode.

Youtube URL
https://youtu.be/rmLNoGi6PqU
