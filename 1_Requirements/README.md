# REQUIREMENTS
# INTRODUCTION
Wiper system is an important component in all the vehicle system. They consist of ac motor fitted with arm which cleans the windshield surface of both front and rear windshield. Modern day cars also posses automatic sensing operation using Rain sensor which basically consists of LED that detects the amount of water on the windshield.

# SOFTWARE REQUIREMENTS
- STM32 IDE 

# COMPONENTS 
- STM32F407VG MICROCONTROLLER BOARD

# REQUIREMENTS FOR THE PROJECTS ARE :
- STM32F407VG :
     Th STM32F405xx and STM32F407xx family is based on the high-performance Arm® Cortex®-M4 32-bit RISC core operating at a frequency of up to 168 MHz. The Cortex-M4 core features a Floating point unit (FPU) single precision which supports all Arm single-precision data-processing instructions and data types. It also implements a full set of DSP instructions and a memory protection unit (MPU) which enhances application security. The STM32F405xx and STM32F407xx family incorporates high-speed embedded
     
- Xpack Packages :
   Windows Build Tools: The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.
   
- OpenOCD :
   Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand.
   
- QEMU :
   The xPack QEMU Arm is a standalone cross-platform binary distribution of QEMU, with several extensions for Arm Cortex-M devices.
   
# FEATURES 
  - Wiper system is easy to use.
  - Three LEDs indicating the wiping operation.
  - STM32F407VG microcontroller has Up to 1 Mbyte of Flash memory.
  - STM32F407VG microcontroller has Up to 192+4 Kbytes of SRAM including 64-Kbyte of CCM (core coupled memory) data RAM.
    512 bytes of OTP memory.
   
# SWOT ANALYSIS
  The image below shows the SWOT analysis 
  ![swot](https://user-images.githubusercontent.com/68462123/167817970-b2e6d1df-1407-4363-82e7-9cf3ccc385e7.png)
  
# 4W & H (WHO,WHAT,WHEN,WHERE,HOW)
  - WHO- Useful for drivers like car, buses and trucks for clear vision of the road
  - WHAT- Aim is to implement automatic wiper system for vehicles
  - WHEN- Helpful during rain 
  - WHERE- Installed at the front windshield
  - HOW- Ignition is turned on, the wiper starts its operation.
  
# HIGH LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL1 | car wiper using STM32F407VG | Implemented |
| HL2 | Led glowing in sequence| Implemented |
| HL3 | Car on and off | Implemented |

# LOW LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL1-LL1 | Push Button | Implemented | 
| HL2-LL2 | Red,Green,Blue Leds | Implemented |
