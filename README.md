# LCD_Test_Device
# Description: This device allows for an 1602-LCD, an Arduino Nano, two Pushbuttons, and two Potentiometers to be attached to the board
# The potentiometers are used for controlling the brightness of the backlight and the contrast of the LCD letters.
# The push buttons are for general purpose things like switching between different tests or controlling what is displayed on the LCD
#
# To-Do: Allow access to analog pins via pin headers
# 1. Allow access to analog pins via pin headers
# 2. Add a RX/TX pin header
# 3. Get rid of the nano and have the "nano" parts directly on the board
# 4. Redesign the board to be more case friendly
# 5. I am stupid and technically made everything upside down. Flip all text so it looks right when being held
# 6. Update readme with places you can buy parts instead of just datasheets and websites
# 7. Print the board and actually see if this thing works
#
# Parts used:
# LCD: Longtech LCM1602A http://www.longtech-display.com/PRODUTS/LCD%20MODULES/character%20module1.htm
# Pushbuttons: 2x Multimec 5GTH9 https://cdn.sos.sk/productdata/80/f6/aabf7be6/5gth9358222.pdf
# Potentiometers: 2x ACP CA9-V10 https://www.acptechnologies.com/catalogue/potentiometers/ca9-ce9/
# Arduino: Arduino Nano https://store.arduino.cc/usa/arduino-nano
# Capacitor: diameter 10mm, pins: 5mm
# Resistors: 150-250 ohm (current should to be around 50mA for PBs) width: 5mm
# Diode: On the board, vertical mount it. The ones I have are 1N4001 and those should work (I haven't gotten this printed yet)
# Pin headers: 2.54mm Pin headers
#
# If someone uses this and sees anything that should be changed about the board, tell me. I'm still learning.
