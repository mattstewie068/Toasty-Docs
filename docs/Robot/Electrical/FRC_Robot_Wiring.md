# Robot Wiring

## Soldering vs. Connectors

## Soldering
Due to reliability issues with connectors on small diameter wires previously discussed, ...link... all wires under 12 AWG should be electrically and mechanically connected via a soldered connection with heat shrink tubing applied around the joint.

## Connectors

## Wire Gauges

Specified using the American Wire Gauge standard.


!!! note
    The table below specifies the legal wiring sizes as stated in the 2024 Crescendo Game Manual. Check the current years game manual to ensure rule compliance.

| Application                                                   | Minimum Wire Size |
| ------------------------------------------------------------- | ----------------- |
| 31 – 40A breaker protected circuit                            | 12 AWG            |
| 21 – 30A breaker protected circuit                            | 14 AWG            |
| 6 – 20A breaker protected circuit                             | 18 AWG            |
| 11-20A fuse protected circuit                                 | 18 AWG            |
| Between the PDP dedicated terminals and the VRM/RPM or PCM/PH | 18 AWG            |
| Compressor outputs from the PCM/PH                            | 18 AWG            |
| Between the PDH and PCM/PH                                    | 18 AWG            |
| Between the PDP/PDH and the roboRIO                           | 22 AWG            |
| Between the PDH and VRM/RPM                                   | 22 AWG            |
| Kraken x60 Powerpole Adapter protected circuit                | 22 AWG            |
| ≤5A breaker protected circuit                                 | 22 AWG            |
| ≤10A fuse protected circuit                                   | 22 AWG            |
| VRM 2A circuits                                               | 24 AWG            |
| roboRIO PWM port outputs                                      | 26 AWG            |
| SIGNAL LEVEL circuits *                                       | 28 AWG            |

\* circuits which draw ≤1A continuous and have a source incapable of delivering >1A, including but not limited to roboRIO non-PWM outputs, CAN signals, PCM/PH Solenoid outputs, VRM 500mA outputs, RPM outputs, and Arduino outputs

### Team Specific Wiring Guide

- 4AWG / 6AWG
- - Used to wire the battery to the main robot breaker and the main power distribution board
- 10AWG
- - Used to wire all Kraken motors. it is also used to wire any high current draw motors that have long wire runs from the PDH.
- 12AWG
- - Used to wire all non-Kraken motors that are located close to the PDH.

!!! warning
    Robot frame is not to be used as a power path. The robot will be inspected before it can compete to ensure that there is no conductivity between either the positive or the negative terminal of the battery input wires to the PDH and various possible conductive locations around the robot.

