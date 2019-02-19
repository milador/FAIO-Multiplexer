# FAIO 2.0

<p align="center">
<img align="center" src="https://raw.githubusercontent.com/milador/FAIO-2/master/Resources/Images/faio2-logo.png" width="50%" height="50%" alt="Open-GCI Logo"/>
</p>

FAIO 2.0 is an open-source all in one switch interface that enables those with limited or no hand movement to use Adaptive switches as input to operate in multiple input modes.

The Supported modes include:

* Switch Access Mode ( HID Keyboard )
* Morse Keyboard Mode ( HID Keyboard )
* Morse Mouse Mode ( HID Mouse )
* Joystick Mode ( HID Joystick )

Additional firmware to operate Xbox Adaptive Controller is available as well.


# Downloads 

These are all the files and documentation associated with the Open-GCI project.

 <table style="width:100%">
  <tr>
    <th>Resource</th>
    <th>Version</th>
    <th>Format</th>
    <th>Link</th>
  </tr>
    <tr>
    <td>FAIO 2.0 All</td>
    <td>2.0</td>
    <td>ZIP</td>
    <td><a href="https://github.com/milador/FAIO-2/archive/master.zip">FAIO-2-master.zip</a></td>
  </tr>
  <tr>
    <td>FAIO-2 Manual</td>
    <td></td>
    <td>PDF</td>
    <td><a href=""> </a></td>
  </tr>
  <tr>
    <td>FAIO-2 BOM (XLSX)</td>
    <td>February 18, 2019</td>
    <td>XLSX</td>
    <td><a href="https://github.com/milador/FAIO-2/raw/master/FAIO-2_BOM.xlsx">FAIO-2_BOM.xlsx</a></td>
  </tr>
  <tr>
    <td>FAIO-2 USB Firmware</td>
    <td>1.0</td>
    <td>Ino</td>
    <td><a href="https://github.com/milador/FAIO-2/raw/master/Software/FAIO_USB_Firmware/FAIO_USB_Firmware.ino">FAIO_USB_Firmware.ino</a></td>
  </tr>
  <tr>
    <td>FAIO-2 XAC Firmware</td>
    <td>1.0</td>
    <td>Ino</td>
    <td><a href="https://github.com/milador/FAIO-2/raw/master/Software/FAIO_XAC_Firmware/FAIO_XAC_Firmware.ino">FAIO_XAC_Firmware.ino</a></td>
  </tr>
  <tr>
    <td>FAIO-2 Board Layout</td>
    <td>1.0</td>
    <td>BRD</td>
    <td><a href="https://raw.githubusercontent.com/milador/FAIO-2/master/Hardware/PCB_design/FAIO2.brd">FAIO2.brd</a></td>
  </tr>
  <tr>
    <td>FAIO-2 Board Schematic</td>
    <td>1.0</td>
    <td>SCH</td>
    <td><a href="https://raw.githubusercontent.com/milador/FAIO-2/master/Hardware/PCB_design/FAIO2.sch">FAIO-2.sch</a></td>
  </tr>
</table> 

# Usage

The FAIO 2.0 switch interface can operate in 4 modes and switch D is used to switch between them in USB and Bluetooth modes.The RGB Led blinks 2 times to indicate the current mode.

<p align="center">
<img align="center" src="https://raw.githubusercontent.com/milador/FAIO-2/master/Resources/Images/faio2s.png" width="50%" height="50%" alt="Open-GCI Diagram"/>
</p>

## USB or Bluetooth mode

 <table style="width:100%">
  <tr>
    <th>Mode Number</th>
    <th>Mode</th>
    <th>Color</th>
  </tr>
    <tr>
    <td>1</td>
    <td>Keyboard Switch</td>
    <td>Green</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Morse Keyboard</td>
    <td>Pink</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Morse Mouse</td>
    <td>Yellow</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Joystick</td>
    <td>Orange</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Configuration</td>
    <td>Purple</td>
  </tr>
</table> 

## XAC mode

 <table style="width:100%">
  <tr>
    <th>Button Number</th>
    <th>Xbox Button</th>
    <th>Color</th>
  </tr>
    <tr>
    <td>1</td>
    <td>A</td>
    <td>Green</td>
  </tr>
  <tr>
    <td>2</td>
    <td>B</td>
    <td>Red</td>
  </tr>
  <tr>
    <td>3</td>
    <td>X1</td>
    <td>Blue</td>
  </tr>
  <tr>
    <td>4</td>
    <td>X2</td>
    <td>Yellow</td>
  </tr>
</table> 

