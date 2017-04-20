# Tool-and-build-load-programming
1.Setting Keil C(MDK522).

2.Setting nRF5x_MDK_8_11_1_Keil4.

	   -At this step connect board development kit pca100040 to computer by usb.
	   
3.nrfgostudio_win-32_1.21.2_installer or nrfgostudio_win-64_1.21.2_installer( dependent computer  32 bit hoặc 64 bit).

# How build and load programming to board development kit pca100040(using IDE keil c).
1. connect board development kit pca100040 to computer by usb 

2. Build programming Press F7 or move project -> Build Target

3. Load programming to  board development kit pca100040 Press F8 or move Flash -> Download


# How build and load programming to module nRf52832(using tool jlink).
1.Download jlink: https://www.segger.com/downloads/jlink

2. connect module nRf52832 to j-link-ARM:

   module nRf52832  |   j-link-ARM
   
	    VDD        ->    3V3
		
	    SDO        ->    SWIO
		
	    SCLK       ->    SWCK
		
	    GND        ->    GND
		

3.open j-Flash move options -> Project settings -> MCU -> Device -> nRF52832_xxAA.

4.Target -> Connect.

5.File -> Open data file.(select file.h).

6.Target -> Manual Programming -> Program & Verify.

# Download app mobi nRF UART v2.0 transmit and receive data.