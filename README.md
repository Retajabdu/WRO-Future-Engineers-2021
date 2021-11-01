

Code for qualifying matches:

Components integrated into the code are one EV3 Color Sensor, one EV3 Gyro Sensor, one

EV3 Large Motor “B”, and one EV3 Medium Motor “A”. When the program starts, two

variables “Blue” and “Orange” are set to zero. Motor “A” is set to start at negative fifty speed;

as it is an inverted motor and will forward when speed is negative. Next, the gyro sensor

angle is reset. Two if conditions are introduced after the robots start moving via motor A.

Whenever the color sensor sees the color orange the variable “Orange” is changed by one.

Alternatively, when the color sensor sees the color blue the variable “Blue” is changed by

one. These two if conditions are underneath a loop that repeatedly checks if “Orange” = 0 or

“Blue” = 0. These if conditions were utilized to check whether the robot is moving clockwise

or counterclockwise. When the color blue is detected, it means the robot is moving

counterclockwise. Else, if the color orange is detected, it means the robot is moving

clockwise. Now, as for turns. Whenever the color orange is detected. Motor B runs for

forty-seven degrees at one hundred speeds until the angle of the gyro sensor is greater than

eighty degrees. Next, motor A is stopped and motor B runs for negative forty-seven degrees

at a hundred speed. Then, motor B is set to "hold position" at stop and motor A is started at

negative fifty speed. In contrast, when the color blue is detected, Motor B runs for negative

forty-seven degrees at one hundred speeds until the angle of the gyro sensor is greater than

eighty degrees. Next, motor A is stopped and motor B runs for forty-seven degrees at a

hundred speed. Then, motor B is set to "hold position" at stop and motor A is started at

negative fifty speed. This program is responsible for moving the robot based on the orange

and blue lines.





Final matches:

Components integrated into the code are one EV3 Color Sensor, one EV3 distance color

sensor, one EV3 Gyro Sensor, one EV3 Large Motor “B”, and one EV3 Medium Motor “A”.

Similar to the qualifying matches, when the program starts, two variables “Blue” and

“Orange” are set to zero. Motor “A” is set to start at negative fifty speed; as it is an inverted

motor and will forward when speed is negative. Next, the gyro sensor angle is reset. Two if

conditions are introduced after the robots start moving via motor A. Whenever the color

sensor sees the color orange the variable “Orange” is changed by one. Alternatively, when

the color sensor sees the color blue the variable “Blue” is changed by one. These two if

conditions are underneath a loop that repeatedly checks if “Orange” = 0 or “Blue” = 0. These

if conditions were utilized to check whether the robot is moving clockwise or

counterclockwise. When the color blue is detected, it means the robot is moving

counterclockwise. Else, if the color orange is detected, it means the robot is moving

clockwise. Now, as for turns. Whenever the color orange is detected. Motor B runs for

forty-seven degrees at one hundred speeds until the angle of the gyro sensor is greater than

eighty degrees. Next, motor A is stopped and motor B runs for negative forty-seven degrees

at a hundred speed. Then, motor B is set to "hold position" at stop and motor A is started at

negative fifty speed. In contrast, when the color blue is detected, Motor B runs for negative

forty-seven degrees at one hundred speeds until the angle of the gyro sensor is greater than

eighty degrees. Next, motor A is stopped and motor B runs for forty-seven degrees at a

hundred speed. Then, motor B is set to "hold position" at stop and motor A is started at

negative fifty speed. In addition, another program is run in these matches. To start, an if

condition is introduced at the beginning of the program. If the distance sensor detects

anything in 30cm (traffic lights) another if condition is introduced. If the color of the object

seen is red, motor A will run for one rotation, motor B will run at negative thirty degrees at

seventy-five degrees, waits for a second, runs for negative sixty degrees at a hundred

speeds, waits for a second, and finally for thirty degrees at a hundred speeds. Else, if the

distance sensor detects any objects in 30cm and the object seen is green, motor A will run

for one rotations, motor B will run at thirty degrees at seventy-five degrees, waits for a

second, run for negative sixty degrees at a hundred speeds, waits for a second, and finally

for thirty degrees at a hundred speeds. This will be in charge of avoiding the traffic lights as

well as turning right/left when the traffic light is green/red.

