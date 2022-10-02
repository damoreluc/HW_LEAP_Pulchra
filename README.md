# HW_LEAP_Pulchra
File del progetto HW Leap Pulchra

## Scheda della stazione meteo con Arduino MKRWAN1310

__Connettori:__

* X1: direzione vento (X1-1: +3V3; X1-2: tensione analogica tra 0V e +3V3; X1-3: GND)
* X2: anemometro (X2-1: +3V3; X2-2: impulsi, open drain; X2-3: GND)
* X3: alimentazione +3V3 (X3-1: +3V3; X3-2: GND)
* X4: pluviometro (X4-1: +3V3; X4-2: impulsi bilancere, open drain; X4-3 +12V riscaldatore neve; X4-4: GND riscaldatore neve)
* X5: alimentazione +12V (X5-1: +12V; X5-2: GND)
* X6: ventola interna all'armadietto (X6-1: +12V; X6-2: comando PWM ventola, collettore transistor Q1)
* X8: sensore bagnatura foglia (X8-1: +3V3; X8-2: on/off, open drain; X8-3; GND)

---

__Componenti e sensori integrati onboard:__
* U1: scheda microcontrollore e radio MKRWAN1310
* U2: modulo condizionamento per sensore esterno di temperatura PT100, ADAFRUIT_MX31865
* U3: (opzionale) sensore temperatura e umidità interno BME280
* U4: (opzionale) display oled SSD1306_128X64
* U5: (opzionale) sensore di temperatura interna analogico TMP36
