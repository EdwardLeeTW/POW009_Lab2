# POW009_Lab1
 The hand-on example code for RTC POW009-Lab1

- - -
## Hardward EVM Boards Used:
## DSPIC33CK CURIOSITY DEVELOPMENT BOARD
Part Number: DM330030

![image](https://www.microchip.com/content/dam/mchp/mrt-dam/devtools/2956-ds-33ck256mp508-curiosity-development-board.jpg) 
## Microchip APP-POWERRTC1 EVM
Part Number: APP-POWERRTC1

![image](https://a.rimg.com.tw/s1/6/a1/07/22025696299271_191.jpg) 
- - -

## Summary

The hand-on example code for RTC POW009-Lab1 was integrated the dsPIC33CK Framework for SMPS Application.
- Controller: dsPIC33CK256MP508@100MIPS
- I/O: 0.5Hz LED Toggle with LED1 (RE6)
- PWMs: PWM4H & PWM4L
  - PWM Frequency: 250KHz
  - PWM4H on RC14
  - PWM4L  on RD6
  - Duty Cycle: Fixed at 40%
  - Deadtime: Rising Edge: 150ns / Falling Edge: 150ns
- Vout Feedback: AN22
  - Triggered by PWM4_Trigger1

- - -

## Related Documentation

- [dsPIC33CK256MP508 Family Data Sheet](https://ww1.microchip.com/downloads/en/DeviceDoc/dsPIC33CK256MP508-Family-Data-Sheet-DS70005349G.pdf)
- [dsPIC33CK256MP508 Family Silicon Errata and Data Sheet Clarification](https://ww1.microchip.com/downloads/en/DeviceDoc/dsPIC33CK256MP508-Family-Silicon-Errata-and-Data-Sheet-Clarification-DS80000796G.pdf)

Alternative Controller Plug-In Module:
- [dsPIC33CH512MP508 Family Data Sheet](http://ww1.microchip.com/downloads/en/DeviceDoc/dsPIC33CH512MP508-Family-Data-Sheet-DS70005371D.pdf)
- [dsPIC33CH512MP508 Family Silicon Errata and Data Sheet Clarification](http://ww1.microchip.com/downloads/en/DeviceDoc/dsPIC33CH512MP508-Family-Silicon-Errata-and-Data-Sheet-Clarification-DS80000805F.pdf)

**Please always check for the latest data sheets on the respective product websites:**
- [dsPIC33CK256MP508 Family](https://www.microchip.com/dsPIC33CK256MP508)
- [dsPIC33CH512MP508 Family](https://www.microchip.com/dsPIC33CH512MP508)

## Software Used 

- [MPLAB® X IDE v6.0](https://www.microchip.com/mplabx-ide-windows-installer)
- [MPLAB XC16 Compiler v2.0](https://www.microchip.com/mplabxc16windows)
- [MPLAB Device Family Pack (DFP) v1.8.224](https://microchipsupport.force.com/s/article/Choose-DFP--Device-Family-Pack--in-MPLAB-X-IDE)
- [MPLAB Code Configurator (MCC) v5.1.17](https://www.microchip.com/mcc)
    - MPLAB Code Configurator (MCC) - Core v5.4.11
    - MPLAB Code Configurator (MCC) - Device Libraries dsPIC33 v1.171.1

## Hardware Used

- DSPIC33CK CURIOSITY DEVELOPMENT BOARD, Part-No. [DM330030](https://www.microchip.com/en-us/development-tool/DM330030)
- Microchip APP-POWERRTC1 EVM, Part-No. [APP-POWERRTC1](https://shopee.tw/%E3%80%90ICBOX%E3%80%91Microchip-APP-POWERRTC1-%E5%AF%A6%E9%A9%97%E6%9D%BF-0300801566001-i.219280202.7044587367)

## Supported Target Devices

- [dsPIC33CK256MP508](https://www.microchip.com/dsPIC33CK256MP508)
- [dsPIC33CH512MP508](https://www.microchip.com/dsPIC33CH512MP508)
- Code compatible with all Single and Dual Core dsPIC33C MP families of devices

- - -
