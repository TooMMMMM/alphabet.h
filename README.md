# alphabet.h
A library for the matrix of the new Arduino UNO r4 wifi
you can add this library with #include "alphabet.h"

put alphabet.h file in the same directory of your .ino program

here's an example of use:

/*
#include "Arduino_LED_Matrix.h"
#include "alphabet.h" 
int i=0;
ArduinoLEDMatrix matrice;

void setup() {
  matrice.begin();
}

void loop() {
  
  matrice.loadFrame(alphabet[91]); //it's an heart for you
  delay(2000);


  for(int i=0;i<91;i++)
  {
    matrice.loadFrame(alphabet[i]);
    if(i>10 && i<65)
    delay(40);
    else
    delay(800);
  }  
}

*/
