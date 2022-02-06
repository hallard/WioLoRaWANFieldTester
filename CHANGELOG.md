## Release 1.5
- Fix RFM95 compilation & misc fix includes new binaries
- Includes the GPS serial speed fix for some LoRa-E5 board wrongly configured
- Reduce communication period after 30 minute non moving device

## Release 1.4
- Battery status now empty when Wio Battery chassis non connected
- Non duty cycle zone now have 25s Duty Cycle instead of 5s ( preserve backend capacities )
- Display the wio terminal name on boot (based on DEVEUI)
- Reduce communication period when the device is out of GPS coverage or not moving
- fix the bar display with last value displayed on first column

## Release 1.3
- initialization of the change log