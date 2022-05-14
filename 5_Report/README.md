# WIPER CONTROL SYSTEM

# Introduction

A windscreen wiper or windshield wiper is a device used to remove rain, snow, ice and debris from a windscreen or windshield . almost all motor vehicles, including cars , trucks, train locomotives, watercraft with a cabin and some aircraft, are equipped with such wipers, which are usually a legal requirement. A wiper generally consists of a metal arm, pivoting at one end and with a long rubber blade attached to the other. The arm is powered by a motor, often an electric motor, although pneumatic power is also used in some vehicles. The blade is swung back and forth over the glass, pushing water or the other precipitation from its surface. The speed is normally adjustable, with several continuous speeds and often one or more “intermittent” settings. Most automobiles use two synchronized radial type arms, while many commercial vehicles use one or more paragraph arms.
Wipers may be powered by a variety of means, although most in use today are powered by an electric motor through a series of mechanical components, typically two 4-bar linkages in series or parallel.
 

# Features

* Changes the wiper speed according to rain intensity
* Avoids accidents during rain.
* Ensures human safety
* Doesn't require driver to change the speed manually

# Components

## STM32F407VG

![STM32F4DISCOVERY - Discovery kit with STM32F407VG MCU _ New order code STM32F407G-DISC1 (replaces STM32F4DISCOVERY) - STMicroelectronics - Google Chrome 12-May-2022 23_56_34](https://user-images.githubusercontent.com/101447824/168143906-fd07d15a-af52-46f4-a14e-2c5eadad64b0.png)

The  STM32F407VG family is based on the high-performance Arm® Cortex®-M4 32-bit RISC core operating at a frequency of up to 168 MHz. The Cortex-M4 core features a Floating point unit (FPU) single precision which supports all Arm single-precision data-processing instructions and data types. It also implements a full set of DSP instructions and a memory protection unit (MPU) which enhances application security. The STM32F405xx and STM32F407xx family incorporates high-speed embedded memories (Flash memory up to 1 Mbyte, up to 192 Kbytes of SRAM), up to 4 Kbytes of backup SRAM, and an extensive range of enhanced I/Os and peripherals connected to two APB buses, three AHB buses and a 32-bit multi-AHB bus matrix.
All devices offer three 12-bit ADCs, two DACs, a low-power RTC, twelve general-purpose 16-bit timers including two PWM timers for motor control, two general-purpose 32-bit timers. a true random number generator (RNG). They also feature standard and advanced communication interfaces.

## SWOT- Strengths, and Weakness, Opportunities Threats:

## Strengths

*	It can be easily and quickly installed in automobiles.
*	Low power consumption
*	Simple and portable
*	Easy to implement

## Weakness

*	It is a small circuit.
*	High cost.

## Opportunites
* This is a great model to prevent the accidents by increasing the drivers concentration during rains.

##  Threats
* The latest vehicle models have inbuilt wiper control system.

## 4W'S and 1'H

## Who
Wiper control system can be used by any vehicle having windscreen.

## What
It automatically controls the speed of the wiper and indicates the intensity.

## When
This system is useful in rainy season.

## Where
Mostly useful in cold climatic conditions , places having high fog and heavy rains. 

## How
when we ON the wiper system , the wiper speed is automatically adjusted inaccordance with the rain intensity.

# HIGH LEVEL TEST PLAN

| **Test ID** | **Description**                                              | **Actual Output** | **Expected Output** |   
|-------------|--------------------------------------------------------------|--------------------|-----------------|
|  HL01      | User should able to view intensity of rainfall on LCD |   Not Implemented | Displays on LCD |
|  HL02      | User should be given alert incase of heavy rainfall |  Not Implemented |Gives alert  |
|HL03|User should able to TURN ON wiper system |TURN ON | TURN ON | 
|HL04|The system sould able automatically switch the speed of wipers|Automatically switches speed|Automatically switches speed |
|HL05|The system should work accurately  |Works accurately | Works accurately |


# LOW LEVEL TEST PLAN
| **Test ID** | **Description**                                              | **Actual Output** | **Expected Output** |   
|-------------|--------------------------------------------------------------|--------------------|-----------------|
|LL01|User should able to TURN ON wiper system |TURN ON | TURN ON |  
|LL02|The system sould able automatically switch the speed of wipers |Automatically switches speed|Automatically switches speed |
|LL03|The system should work accurately |Works accurately | Works accurately |

