materiales de ingenieria

este respositorio contiene materiales de ingenieria de un modelo de vehiulo autonomo que participa en la competencia WRO Future Engineers en la temporada 2023

t-photos: 


v-photos:


video:


schemes:


Description:
used fischertechnik parts for the basic construction of the vehicle, together with a 9V scoder motor for the front drive part and a rechargeable battery to power it. created a directional axis with parts controlled by a servomotor.

#include <Servo.h>

Servo servo1;

void setup() {
servo1.attach(9);
}

void loop() {
servo1.write(68);
delay(4000);

servo1.write(45);
delay(3000);
}

Arduino R3 board was used together with a breadboard working with the arduino software. used a color sensor TCS3200 for the differentiation between green and red.
