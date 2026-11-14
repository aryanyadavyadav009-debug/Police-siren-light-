const int ledPinR = 7;
const int ledPinB = 13;

void setup(){
 pinMode (ledPinR, OUTPUT);
 pinMode (ledPinB, OUTPUT);
 }
void ledR_ON(){
digitalWrite (ledPinR, HIGH);
}
void ledB_ON(){
digitalWrite (ledPinB, HIGH);
}
void ledR_OFF(){
digitalWrite (ledPinR, LOW);
}
void ledB_OFF(){
digitalWrite (ledPinB, LOW);
}
void loop(){
for(int x=0;x<3;x++);
Serial.println
ledR_ON();
  delay(200);
ledR_OFF();
  delay(50);
for(int x=0;x<3;x++);
Serial.println
ledB_ON();
  delay(200);
ledB_OFF();
  delay(50);
}






