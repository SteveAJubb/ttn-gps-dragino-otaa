# ttn-gps-dragino-otaa
TTN (Arduino+Dragino GPS Shield) node using OTAA

This  can be used with the instructions at https://github.com/VojislavM/dragino-ttn-mapper to activate via
OTAA (over-the-air-activation) rather than ABP (activation-by-personalisation).

Files included are:  
Arduino IDE sketch  
TTN console decoder function for use in Applications > Payload Format

Note: When the Arduino starts it will take about ten minutes for the activation to complete and you will see multiple join requests on the console (I haven't checked but it appears to cycle through each channel) so be patient waiting for your data to be transmitted). Once the activation is completed the payloads are sent at whatever frequency you've specified.
