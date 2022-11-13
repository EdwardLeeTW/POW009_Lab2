# POW009_Lab2
 The hand-on example code for RTC POW009-Lab2

- - -
## Hardward EVM Boards Used:
## dsPIC33CK CURIOSITY DEVELOPMENT BOARD
Part Number: DM330030

![image](https://www.microchip.com/content/dam/mchp/mrt-dam/devtools/2956-ds-33ck256mp508-curiosity-development-board.jpg) 
## Microchip APP-POWERRTC1 EVM
Part Number: APP-POWERRTC1

![image](https://user-images.githubusercontent.com/61537309/200979780-344b1282-f81b-4b78-8f60-89ab7975ca87.png)
- - -

## Summary

The hand-on example code for RTC POW009-Lab2 is used to measure plant bode plot with Kp (P-term) contorl.
- Codebase: POW009-Lab1 v1.0
- Kp (P-term) contorl using PowerSmart-DCLD

## Version Description
- v1.0 (Nov 13, 2022)
  - Implement Kp (P-term) control using PowerSmart-DCLD
  - Add Mindi/Plant modeling example for reference
  
    ![image](https://user-images.githubusercontent.com/61537309/200979664-ae62631e-80bd-4bae-8a84-3f4db3b424a8.png)
  - Test P-term control function with adjusting "Nominal Efficiency" on PowerSmart
  
    ![MicrosoftTeams-image](https://user-images.githubusercontent.com/61537309/200979998-f56c543f-3cbf-4592-a875-0fb102785eae.png)
  - Add test result to Bode-100 file

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
- [MPLAB® PowerSmart™ Development Suite v1.0.0.633](https://www.microchip.com/en-us/solutions/power-management-and-conversion/intelligent-power/mplab-powersmart-development-suite)

## Hardware Used

- dsPIC33CK CURIOSITY DEVELOPMENT BOARD, Part-No. [DM330030](https://www.microchip.com/en-us/development-tool/DM330030)
- Microchip APP-POWERRTC1 EVM, Part-No. [APP-POWERRTC1](https://shopee.tw/%E3%80%90ICBOX%E3%80%91Microchip-APP-POWERRTC1-%E5%AF%A6%E9%A9%97%E6%9D%BF-0300801566001-i.219280202.7044587367)

## Supported Target Devices

- [dsPIC33CK256MP508](https://www.microchip.com/dsPIC33CK256MP508)
- [dsPIC33CH512MP508](https://www.microchip.com/dsPIC33CH512MP508)
- Code compatible with all Single and Dual Core dsPIC33C MP families of devices

- - -
