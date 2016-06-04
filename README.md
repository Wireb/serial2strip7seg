### Serial to dual 7 segment display led strip driver

This driver is a serial input to dual 7 segment display driver. 

####Inputs:
Synchronous serial input signals 
  Data in
  Serial clock
  Reset
  Latch data
  
####Outputs:
Synchronous serial outputs signals 
  Data out
  Serial clock
  Reset
  Latch data
LED strip outputs
  14x 2.3A @ 20V max (not including thermal limits)
  
####Power:
Logic and serial intputs/outputs can be run off 3.3V or 5V   
LED side only needs a ground connection
!!NOTE!! logic and led grounds are connected. Make sure the LED grounds are large enough to carry all the current of the LED strips. Also watch out for ground loops. 
