# VH130.
TITLE : SMART MONITORING OF WASTE MANAGEMENT USING IOT
TEAM DETAILS
1. M.Lakshmi Thirupathamma  9921005308@klu.ac.in
2. D.Sarath Chandra         9921005285@klu.ac.in
3. Neti Teja                9921005199@klu.ac.in
4. A.O.Sai Charan           9921009019@klu.ac.in
 
5. PROBLEM STATEMENT :
 Unscientific treatment, incorrect garbage collection, and ethical issues are the main issues affecting solid waste management. Hazards like air pollution, water contamination, and environmental deterioration follow from this.
 One of the biggest issues facing the globe today is solid waste management. If waste is not properly collected, stored, and disposed of, it can endanger human health and the environment.
 Tons of solid waste are disposed of at landfills every day. These pollutants originate from a variety of locations, including schools, office buildings, factories, construction sites, and demolition operations.

 OBJECTIVES OF THE PROJECT :
* Our micro project's primary goal is to maintain our health.
* We can do this by keeping our surroundings tidy and free of insects.
*  Thus, we have created a smart garbage that will instantly sound an alert to employees to maintain the area clean. Afterwards, there will be a decreased chance of contracting an insect infection and an improved quality of life.




 6.CODE :
#define Trigpin 7 
#define Echopin 8 
#define low_led 9
#define high_led 10
float distance; int time; int ll = 700;
void setup() {
digitalWrite (low_led, LOW); digitalWrite (high_led, LOW); 
pinMode (Echopin, INPUT); 
serial.begin(9600); 
serial.println ("Welcome To Distance Meter"); 
serial.println ("Coded By LAKSHMI");
serial.println ("Welcome To Distance Meter");
digitalWrite (low_led, LOW); 
void loop() {
duration = pulseIn(Echopin, LOW); 
digitalWrite(Trigpin, HIGH); 
delayMicroseconds(2);
digitalWrite(Trigpin, LOW); 
delayMicroseconds(6)

if (distance<3) :
{
distance = duration * 0.034 / 2; delay (ll); 
Serial.println(" "); 
Serial.print ("Distance = ");
Serial.print (distance); 
Serial.print (" CM");
Serial.println(" ");
Serial.println ("Nobody Is In Front of the Sensor");
digitalWrite (low_led, HIGH); delay (500); digitalWrite (low_led, LOW); delay (500); digitalWrite (low_led, HIGH);
}
else:
{
Serial.println ("Someone Is Infront of the Sensor"); 
digitalWrite (high_led, HIGH); delay (100); digitalWrite (high_led, LOW); delay (100); digitalWrite (high_led, HIGH); delay (100); 
} 
void setup(){
Serial.begin(9600);
pinMode(4,OUTPUT)
}
void loop(){
int value =analogRead(A3)
Serial.print("Value:");
Serial.print(value);
if (value<30)
digitalWrite{4,HIGH);
Serail.print('Rain is coming remove the dust");
}
else
{
digitalWrite(4,LOW);
}
}
define LED pin; pinMode(4, OUTPUT);
}
