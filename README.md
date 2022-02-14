## pico:ed de Elecfreaks

[pico:ed de Elecfreaks](https://www.elecfreaks.com/picoed.html)

Basada en el RP2040 (Raspberry Pico)
SRAM	256KB
Flash	2MB
GPIO	19 Pcs
En la placa: Buzzer, LED, 7x17 LED matrix, 2 * Button

Trae micropython 1.17

[Repositorio de github](https://github.com/elecfreaks/pico_ed)

[librería base](https://github.com/elecfreaks/pico_ed/blob/master/pico_ed/lib/Pico_ed.py)

[Documentación](https://www.elecfreaks.com/learn-en/pico-ed/index.html) y [ejemplos python](https://www.elecfreaks.com/learn-en/pico-ed/pico_ed_python.html)

[micropython para RP2040](https://docs.micropython.org/en/latest/library/rp2.html)

## Ejemplos

import Pico_ed
# led
Pico_ed.led.on()
Pico_ed.led.off()

# pantalla

Pico.display.show('Hi')
Pico_ed.display.show('Hola')

# musica

import machine

while True:
    if Pico_ed.ButtonA,is_pressed():
        Pico_ed.music.phonate('1155665-4433221')
        
