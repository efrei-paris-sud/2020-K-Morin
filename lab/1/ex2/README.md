## Exercise 2 
The goal of the second exercise was to make the led flash.

A gif of my assemblage is joined in the folder.

## Code

int led = 6;

void setup() {
  pinMode(led, OUTPUT);

}

void loop() {
  digitalWrite(led, HIGH);
  delay(1000);
  digitalWrite(led, LOW);
  delay(1000);
}
  

## Issues
The issues I had with this exercise were that for some reason, my computer could not detect my board correctly. So i changed my board and it fixed the problem.