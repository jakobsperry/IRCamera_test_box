# IRCamera_test_box
Code and CAD for the WPI RBE noiles IR camera test box

# How to use




To plug in the IR camera plug in top to bottom

<p>
  Black<br>
  Green<br>
  Yellow<br>
  Red<br>
</p>

<p>
  Point the camera at the LED's and you should see a red light on the IR camera and circles on the OLED showing the location of the LED's with respect to the cameras field of view
  </p>
  
<p align="center">
  <img src="IRCamera_tester_box_cad/use_photo.png" width="350" alt="using boxp">
</p>


# Wiring

<p>
  <b>Components:</b><br>
  1x STEMA QT 128x64 OLED display (https://www.adafruit.com/product/326)<br>
  1x ESP23_devkitc_v4 <br>
  2x 5mm IR LED<br>
</p>

<p align="center">
  <img src="IRCamera_tester_box_cad/wiring.png" width="350" alt="Box wiring">
</p>

<p>
  <b>Wiring:</b><br>
  OLED vin -> ESP 5V<br>
  OLED gnd -> ESP gnd<br>
  OLED rst -> ESP 23<br>
  OLED clk -> ESP 22<br>
  OLED data -> ESP 21<br>
  
  LED+ -> 330 ohm -> ESP 5V<br>
  LED- -> ESP gnd<br>
  
  
</p>

# CAD and Assembly
<p>
  <b>Components:</b> <br>
  1x 3D printed box (CAD avalible in repo) <br>
  4x 2-56 0.25" Pan head bolt <br>
  4x 2-26 nut <br>
  10x M3 Heat inset nut <br>
  10x M3 6mm socket head cap screw <br>
</p>

<p>
  <b> Assembly:</b><br>
  1) Insert all heat insert nuts into box top. There are 2 inserts per side and 2 inserts to mount the ESP32<br>
  2) Screw the SDoldered prototyping board and the OLED display to the printed box top. Use M3 screws for the board and 2-56 for the OLED <br>
  2) Print the pinout colors PDF and tape it to the box to indicate the correct IR Camera wiring<br>
</p>
<p align="center">
  <img src="IRCamera_tester_box_cad/top.png" width="350" alt="Box Top"><br>
  <img src="IRCamera_tester_box_cad/heat_insert.png" width="350" alt="heat insert">
</p>


