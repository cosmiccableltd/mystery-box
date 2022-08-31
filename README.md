# Mystery Box

## About
The Mystery Box is a small PCB which provides power ports for various devices to indicate a ringing phone and drive POE devices.
It was designed by [Cosmic Cable Ltd.](http://cosmic.cable.limited) to be used for self-made telephone booths. 

## Versions

## Ports
| Port Name | Function                                                      | Usage                                   |
| --------- | --------                                                      | -----                                   |
| J1        | [POE](https://en.wikipedia.org/wiki/Power_over_Ethernet) Port | POE powered network device              |
| J2        | LAN Port                                                      | Connection to external network          |
| J3        | Analogue Telephone Port                                       | Connection to external analogue network |
| J4        | Analogue Telephone Port                                       | Connection to analogue telephone        |
| X1-1      | +12V                                                          |                                         |
| X1-2      |  GND (switched)                                               | swichted on ringing phone line          |
| X1-3      | +12V                                                          |                                         |
| X1-4      |  GND                                                          |                                         |
| X1-5      | +12V                                                          |                                         |
| X1-6      |  GND                                                          |                                         |
| X1-7      | +12V                                                          |                                         |
| X1-8      |  GND                                                          |                                         |

## Known Issues
We experienced that the PMV20EN Q2 Mosfet might die from to high current.
It should be changed to something which can handle more current or otherwise it must be ensured that the outgoing power is limited.
