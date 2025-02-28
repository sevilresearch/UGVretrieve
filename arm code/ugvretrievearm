#include <Servo.h>

Servo myservo; // create servo object to control a servo Servo servo2;// create servo2
Servo servo3;// servo3
// twelve servo objects can be created on most boards

int pos = 0;	// variable to store the servo1 position int pos2 = 90; // variable servo 2
int pos3 = 0; // servo 3 void setup() {
myservo.attach(5); // shoulder servo2.attach(6); // elbow servo3.attach(7); // claw
}
// //servo 1 void loop()


{


for (pos3 = 0; pos3 <= 90; pos3 += 1) { // goes from 0 degrees to 180 degrees
// in steps of 1 degree
servo3.write(pos3);		// tell servo to go to position in variable 'pos' delay(10);	// waits 15ms for the servo to reach the position
}
for (pos3 = 90; pos3 >= 0; pos3 -= 1) { // goes from 180 degrees to 0 degrees servo3.write(pos3);		// tell servo to go to position in variable 'pos' delay(10);	// waits 15ms for the servo to reach the position
}	// waits 15ms for the servo to reach the position

for (pos = 90; pos >= -90; pos -= 1) { // goes from 0 degrees to 180 degrees
// in steps of 1 degree
myservo.write(pos);		// tell servo to go to position in variable 'pos' delay(20);	// waits 15ms for the servo to reach the position
}
for (pos = -90; pos <= 90; pos += 1) { // goes from 180 degrees to 0 degrees myservo.write(pos);	// tell servo to go to position in variable 'pos'
delay(20);	// waits 15ms for the servo to reach the position
}

//servo 2

for (pos2 = 0; pos2 <= 180; pos2 += 1) { // goes from 0 degrees to 180 degrees
// in steps of 1 degree
servo2.write(pos2);		// tell servo to go to position in variable 'pos' delay(20);	// waits 15ms for the servo to reach the position
}
for (pos2 = 180; pos2 >= 0; pos2 -= 1) { // goes from 180 degrees to 0 degrees servo2.write(pos2);		// tell servo to go to position in variable 'pos' delay(20);	// waits 15ms for the servo to reach the position
}
//servo 3 the Claw

}
