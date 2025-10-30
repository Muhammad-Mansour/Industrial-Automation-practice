Readme for my CAD-E practice

this

1\. Simple start stop circuit



2\. sequential operation for 3 motors, each runs for 5s



3\. A Circuit for 3 motors.

 	- 1st motor can run directly

 	- 2nd motor can't run unless motor1 is running

* same as motor 3 can't run unless motor 2 is running.

 	- while the 3 motors are running you can stop anyone without affecting any of them



4\. running motor forward/reverse simple circuit with interlock so the motor won't explode



5\. washing machine circuit

 	- 1 motor running forward for 5 sec

 	- stops for 2sec

 	- running reverse for 5sec

 	- stops for 2sec then repeat



6\. at start

 	- first motor runs

 	- after 5sec second motor runs

  at stop

 	- second motor stops

 	- after 3sec first motor stops



7\. Star-Delta starting method circuit for motor



8\. Star-Delta starting method circuit for motor but in F/R case



9\. 2 motor exchanging with each other in same process

 	- when you start any motor it should run for 10 sec

 	- if you tried to run the other won't run, they can't work together

 	- but if you stopped the one working the other will complete the process in the same time

 	- for example if you started the first one for 5 sec then stopped the other will complete the rest 5sec



10\. could be considered as improvement on Forward/Reverse circuit as here you after you run in a direction then stop you can't start again unless 5sec passes



11\. in this circuit we using phase sequence relay signal to try maintain the same behavior of the circuit

 	- if the power lines are L1,L2,L3, it will reach L1,L2,L3

 	- if it comes L2,L1,L3 it will reach also as L1,L2,L3

 	- the problem is this circuit only maintain the behavior in this case only

 	- in other cases L1-L3 or L2-L3 exchange  it won't fix it



12- ATS circuit to switch between and an old generator and the main power source

 	- when the main power source cut off it waits for few seconds then connect to the generator while starting it automatically

 	- when the main power source come back it switch back to it after few seconds also

