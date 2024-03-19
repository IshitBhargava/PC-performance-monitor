# PC-performance-monitor

**Things Needed:**
<pre>
  You need: (software)
  i)    OpenHardwareMonitor 2019
  ii)    Arduino IDE

  To get these applications, you can:
  Arduino IDE - Install from - https://www.arduino.cc/en/software
  
  OpenHardwareMonitor 2019 - Move "Aga.Controls.dll , License.html , OpenHardwareMonitor.config , OpenHardwareMonitor.exe , OpenHardwareMonitor.exe.config , openHardwareMonitorLib.dll , OxyPlot.WindowsForms.dll , OxyPlot.dll
  
</pre>

<pre>
  You need: (hardware)

  1x Arduino UNO
  1x RGB led
  1x HC-SR04 ultrasonic distance sensor
  1x Motor
  2x TMP36 temperature sensor
  1x 20x04 i2c LCD
  3x LEDs
  3x Push buttons
  1x Slide-Switch
  1x USB type-A breakout board
  1x USB cable (to upload code)
</pre>

______________________________________________________________________________________________________________________________________________________________________

**Hardware connections:**

<pre>
  NOTE: It is a good practice to check the PCB for vias before printing it.

  You can print the PCB using one of these PCB suppliers (you can also choose your own PCB supplier):
  JLCpcb
  PCBpower (recommended for Indians)
  Fritzing FAB

  After getting the PCB, you can solder all the components to it.
  Note: I suggest you to use male header to connect th Arduino UNO as it must be seperated from the PCB in order to upload the code.
</pre>
________________________________________________________________________________________________________________________________________________________________________

**Steps:**
<pre>
  Step 1: Detach the Arduino UNO from the PCB.
  Step 2: Connect the Arduino UNO using the USB cable.
  Step 3: Open the code named- "PCdisplay_extreme".
  Step 4: Select your board, An Arduino UNO in this case.
  Step 5: Select the port on which your Arduino UNO is connected.
  Step 6: Hit the upload button, usually represented by a arrow.
  Step 7: After the code is uploaded, attach the Arduino UNO back on the PCB.
  Step 7: Run OpenHardwareMonitor.exe
  Step 7: Go to 'options', then to 'serial', then to 'configure' then select the COM port on which your Arduino UNO is connected.
  Step 8: Click on close on the 'configuration' window.
  Step 9: Click on 'run' in 'options => serial => run'
  Step 10: it should shwo the perfomance on the LCD display.

  NOTE: Don't close OpenHardwareMonitor while you are monitoring the perfomance, but you can minimize it.
  
</pre>

___________________________________________________________________________________________________________________________________________________________________________

