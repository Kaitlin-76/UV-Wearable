#define LED 11
void setup() {
 Serial.begin(115200);
 Serial.println("MiCS-5524 demo!");
  Serial.println("Gas Sensor demo!");
pinMode (LED, OUTPUT);
}

void loop() {
 int MiCSreading = analogRead(A0);
 int FormReading= analogRead(A2);
Serial.print (MiCSreading);
 Serial.print(",");
 Serial.println(FormReading);

analogWrite(LED, MiCSreading);
delay (2000);

}
