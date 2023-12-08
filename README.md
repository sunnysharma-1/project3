# project3
pip3 install raspberrypi-tm1637

Practical No. 5

Step:-2 mkdir 4digit

stap:-3 cd 4digit

Step:-4 wget https://raspberrytips nofiles/1637 py stap:-5 is

stap:-home/admin/digit Create a file name clock. py

stap:-7 paste this code

Import sys

Import time

Import datetime Import RPL GPIO as GPIO

import on 1637

Display am1637.TM1637(23.24,tm1637 BRIGHT TYPICAL)

Diaplay.Clear() Display SetBrightnes(1)

while (True):

now datetime.datetime.now()

hour now.hour

minute now.minute

second now.second

currenttime [int(hour/10), hour, 10, int(minute (10), minute % 101 Display Show(currenttime) Display ShowDoublepoint(second % 21

time.sleep(1) step: Run This Code

Practical No. 5

pins connections for raspberry pi

GND GROUND (Any Pins Of Raspi)

VCC-Power Supply 5V pin no 2

DIO-Data in pin no:-18 of Raspi

CLK-clack pin no 16
