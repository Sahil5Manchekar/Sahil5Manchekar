int pirsensor = 2;
int readValue;
void setup(){
pinMode(pirsensor,INPUT);
pinMode(13,OUTPUT);
Serial.begin(9600);
}
void loop(){
readValue = digitalRead(pirsensor);
if(readValue = = 1);
{
digitalWrite(13,HIGH);
}
else{
digitalWrite(13,LOW);
}
Serial.println(readValue);
}
