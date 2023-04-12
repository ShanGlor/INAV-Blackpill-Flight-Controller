# Blackpill-F411-Flight-Controller
INAV/Betaflight Firmwares for STM32F411 (Blackpill) Flight Controller

QUADCOPTER

108mhz, 2x UARTs, 1x Software_Serial, 2x SPIs, 1x I2C, 2x ADC.

4x Motors + 4x Servos, LED Strip, SDCard Blackbox, Voltage Sensor, Beeper, Telemetry.

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/blackpill-fc-pinout-LARGE-rev2-QUADa.png?dl=0)

PLANE/VTAIL

108mhz, 2x UARTs, 1x Software_Serial, 2x SPIs, 1x I2C, 1x ADC.

1x Motor + 5x Servos, LED Strip, SDCard Blackbox, Voltage Sensor, Beeper, Telemetry.

![My Remote Image](https://github.com/EonClaw/STM32F411-Blackpill-INAV-FixedWing/blob/main/blackpill-fc-pinout-LARGE-rev3-FixedWing.png?dl=0)

For updated firmware specifically for a Fixed Wing see https://github.com/ShanGlor/BlackWing-INAV-STM32F411

(NOTE!!!) MPU6050 (Use INAV-5.1.0 with headers facing front) - Click "Keep Current Settings" after flashing otherwise it will not boot. Modify "Mixers" to QUADX or Plane then "Outputs" to Enable Motors and Servo Output.

![My Remote Image](https://github.com/EonClaw/DIY-Flight-Controller-STM32F411CEU6/blob/main/images/keepcurrentsettings.png?dl=0)

INAV Configurator Links

https://github.com/iNavFlight/inav-configurator/releases/download/5.1.0/INAV-Configurator_win64_5.1.0.zip

https://github.com/iNavFlight/inav-configurator/releases/download/6.0.0-RC4/INAV-Configurator_win64_6.0.0.RC4.zip

NOTE:
Check CLI to verify pin assignments.

No guarantees. No warranties. Use at your own risk.
