What it is: An audio system with DSP facilities and full MCU breakout 

What it has:
• 1 x STM32 main MCU (microcontroller)  
• 2 x ESP32 support MCUs to provide for example Bluetooth and WiFI functionality  
• 1 x ADC (PCM1865 24 bit 110dB S/N)  
• 1 x DAC (PCM5102A 32 bit 112dB S/N)  
• 1 x Class D power amplifier (Stereo 15W per channel Class D power amplifier)  
• 1 x DAB radio receiver  
• 1 x FM radio receiver  
• 1 x AM radio receiver  
• 1 x Touchscreen display  
• 1 x Infrared remote control inputs  
• 4 x SPDIF optical inputs  

Audio sources:
• 4 SPDIF inputs  
• Onboard DAB radio  
• Onboard FM radio  
• Onboard AM radio  
• Analogue (3.5 mm blue jack)  
• Onboard ESP32 e.g. Bluetooth in and Internet in (via WiFi) (Requires the ESP32 to contain the appropriate firmware)  

Audio ouputs:
• Stereo speakers (6R to 8R preferred)  
• HiFi headphone output (3.5 mm green jack)  
• LoFi headphone output (3.5 mm green jack)  
• On board ESP32 e.g. Bluetooth (SBC codec) (Requires the ESP32 to contain the appropriate firmware)  

Power supply requirements:
• Connector marked "5V": 5V. Typically obtained from the high voltage supply via a DC to DC buck converter.  
• Connector marked "12V": 12V to 24V. Ideally 19V for 6R speakers and 24 V for 8R speakers.  

Suggested speakers:
• Wharfedale 220 (8 ohm nominal impedance).  

==========

My (JSB) firmware to use with this board:
• For STM32: Project "11_LivingRoomHiFi" in repository "PJB_UAS_Firmware_STM32" (https://github.com/JSB2500/PJB_UAS_Firmware_STM32/tree/main/11_LivingRoomHiFi)  
• For left hand ESP32: Project "01_BluetoothSource" in repository "PJB_UAS_Firmware_ESP32" (https://github.com/JSB2500/PJB_UAS_Firmware_ESP32/tree/main/01_BluetoothSource)  
