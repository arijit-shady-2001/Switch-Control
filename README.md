# Switch-Control
This is a simple and easy attempt to blink an LED with the help of a Button Switch

void setup()
{
     pinMode(5,INPUT);
     pinMode(10,OUTPUT);
}
void loop()
{
     int a=digitalRead(5);
     if(a==HIGH)
     digitalWrite(10,HIGH);
     else
     digitalWrite(10,LOW);
}
