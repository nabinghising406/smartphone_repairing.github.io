# Dead Mobile Checking Process
#### 1. Check Battery(3.7~4.4v)
 - *_If faulty in Battery replace/Boost battery._*
 - *_Or use DC power supply(3.7~4.4v) 4v is safe._*
 ### COLD TESTING
> #### 1. Check Battery Connector Pins.
 > - Keep multimeter in beep mode.
 > - Fix red wire at GND(any metalic contacts) and check battery connector pins with wire of multimeter.
 > - "+" 250~750 means OK.
 > - "+" Less than 200 mean half short.
 > - "+" Beep means full short.
 > - "+" No value means Open(therre is no connection with board)
 ### Hot Testing
> #### If battery connector is OK.
 > - Apply 3.7~4.4v to battery connector from DC machine and see ampare meter.
  >>- If ampare increases upto 0.15 without power ON on mobile phone means Half short.
  >>- If ampare increases more than 0.20 without power ON on mobile phone means full short.
  >>- If ampare increases upto 0.15 with power ON on mobile phone means software problem.
  >>- If ampare increase upto 0.20 with power ON on mobile phone means Mobile phone board(PCB) OK.
  >>- If ampare not increases with power ON means swith/components/IC problem.
