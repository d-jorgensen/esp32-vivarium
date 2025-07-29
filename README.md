This is a prototype vivarium controller for 2 snakes, monitoring and running their heat, as well as running a 12VDC pump for watering plants in their tanks. In addition a small fan runs on both to provide a small amount of air circulation. 

kicad documentation coming soonish...

Future updates are to possibly include the lights (uvb arcadia tubes), and probably add a small cob led light strip to supplement the plants. PWM fans would be a nice addition to better control humidity / heat. BME280 for mesuring humidity and as a secondary temperature reading. 


Items used in this project
  1. esp32-c3
  2. relay board with 4 relays
  3. two max6675 sensors with k-type probes, one using hardware spi and the other on software
  4. i2c with 20x4 display
  5. 60W 12v DC power supply
  6. lm2596 buck converter set to 5V DC
  7. 2x 12v DC USB buck converters
  8. 12v DC pump
  9. 2x USB fan
  10. 2x 120VAC indicator lights
  11. 2x 120VAC outlets
  12. 2x toggle switches for outlets
  13. 2x SSR for quick switching of heat on/off

