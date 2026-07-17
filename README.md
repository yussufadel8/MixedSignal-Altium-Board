\# Mixed-Signal 4-Layer Controller Board



A 4-layer mixed-signal PCB built to a central-controller-board specification (Ethernet, USB, CAN, 24-bit ADC, dual motor drivers, stereo audio) as a guided learning project — following an instructor's component-selection process and independently executing the schematic capture and PCB layout.



\## Features



\- \*\*Main controller\*\*: STM32F407VG (LQFP100) — handles Ethernet, ADC, motor control, and audio peripherals

\- \*\*Debug/programmer\*\*: onboard STM32F103, functioning as an ST-Link-style debugger for the F407

\- \*\*Ethernet\*\*: 10/100 Mb/s PHY (DP83826), up to 2 Mb/s application-level transfer

\- \*\*USB 2.0\*\*: via CH340C USB-to-UART bridge

\- \*\*CAN bus\*\*: up to 1 Mb/s

\- \*\*UART\*\*: general-purpose serial interfaces

\- \*\*24-bit ADC\*\*: ADS122C04, external reference and clock, PGA gain of 128, 100 SPS — measures a differential input of 0–10 mV at 2.5 V common mode (e.g. load cell / bridge sensor)

\- \*\*Dual bidirectional motor drivers\*\*: DRV8701 gate driver + DMHT6016 FET bridge, 0–100% duty cycle, 36 W (12 V, 3 A) per channel

\- \*\*Stereo audio\*\*: I2S DAC with headphone and speaker amplification

\- \*\*Microphone input\*\*: MEMS mic routed to onboard codec



\## Status



Design complete (schematic + PCB layout in Altium Designer). \*\*Not fabricated\*\* — this was built as a hands-on learning project to gain experience with Altium Designer and large mixed-signal board layout, guided by an instructor-provided component selection process.

