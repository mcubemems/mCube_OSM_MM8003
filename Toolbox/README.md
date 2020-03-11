# Changelog
======
## 1.0.0
* Initial release.
	
## 1.0.1
* Fixed issue "Close file and change label to 'Start logging' when disconnected".
* Fixed issue "DFU complete/fail pop-up window".
* Fixed issue "Calibration button can't click when change setting from IMU to AHRS".

## 1.0.2
*Fixed 3D view texture and rotation.
	
## 1.0.3
* Added "Pop up calibration successfully window when user click 'Calibration' button manually".
*	Added "Close 'Start Calibration' & 'Calibration Success'  pop-up window automatically after 3 seconds".
*	Added "Show identify/calibration confirmation pop-up window, closed after 60 seconds".

## 1.0.4
* Revised phrases for alert windows.
*	Cleaned codes for redundant comments.

## 1.0.5
* Add feature: "Auto scale for each chart".
	
## 1.0.6
* Fixed issue "Auto-scale: Axis alignment middle, Axis set to inf".
* Fixed issue "Mag max range to sensor limit: 800μT".
* Add Feature "Auto-scale: Alignment middle to zero, Range set to multiples of 5".

## 1.0.7
* Fixed if manual mag calibration hasn't been sent, but a previous good quality signal arriving will wrongfully change to calibration success state.
* Added close poor quality alert event. If poor quality alert is given and the quality turns good, close the pop-up window.
*	Fixed issue: "Re-reconnect"
*	Fixed issue: "Ignore last packet in serial port"
*	Move all serial port object to background thread
  * Fixed issue: "Serial port lose data when CPU high"

## 1.0.8
* Fixed issue: "Lost packet from UART after wrong packet"
*	Fixed issue: "ChartView auto-scale wrong range"
*	Fixed issue: "Miss BLE connected packet from UART"
*	Fixed issue: "Concatenate unparsed data"

## 1.0.9
* Fixed issue: "ChartView auto-scale boundary"
*	Fixed issue: "Better performance on worker thread"
*	Fixed issue: "Even disable data output, should update version number on disconnect"

## 1.1.0
* Fixed performance issue: "Set cube update ODR to 25Hz"
	
## 1.1.1
* Fixed performance issue: "Reset cube update ODR back to module ODR"
*	Fixed performance issue: "Update CubeView frame when receive data to increase CubeView CPU priority"

## 1.1.2
* Fixed issue: "Will always reconnect serial port in configuration. Only when change baudRate then need reconnect."
*	Fixed issue: "Didn't close configuration window when serial port disconnect. Close configuration window when serial port disconnect"

## 1.1.3
* Fixed issue: "Disable and enable data output will trigger re-connect"
*	Fixed issue: "Disable and enable data output will trigger re-connect then unexpected close configuration window"
