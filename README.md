# UV-Wearable
void setup() {

initialize digital pin 13 as an output.

pinMode(10, OUTPUT); number on the bread board where you want your output to begin

}
the loop function runs over and over again forever

void loop() {

digitalWrite(10, HIGH); turn the LED on (HIGH is the voltage level)

delay(950); wait for a second

digitalWrite(10, LOW); turn the LED off by making the voltage LOW

delay(950); wait for a second; you do need both high and low to cause the LEDs to blink

he setup function runs once when you press reset or power the board

void setup() {

initialize digital pin 13 as an output.

pinMode(9, OUTPUT);

pinMode(10, OUTPUT);

pinMode(7, OUTPUT);

}
the loop function runs over and over again forever




void loop() {

digitalWrite(10, HIGH); turn the LED on (HIGH is the voltage level)

delay(950); wait for a second

digitalWrite(10, LOW); turn the LED off by making the voltage LOW

delay(950); wait for a second

digitalWrite(7, HIGH); turn the LED on (HIGH is the voltage level)

delay(1000); wait for a second

digitalWrite(7, LOW); turn the LED off by making the voltage LOW

delay(1000);

digitalWrite(9, HIGH); turn the LED on (HIGH is the voltage level)

delay(480); wait for a second

digitalWrite(9, LOW); turn the LED off by making the voltage LOW

delay(480); } wait for a second
