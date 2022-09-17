# LED-face-mask-using-ESP-12F-and-WLED-firmware
A LED face mask which can be controlled wirelessly using WLED firmware over simple html page

8×8 Neo-pixel Matrix Face Mask Using WS2812 + ESP-0 and WLED Firmware
By AdityaG116 in CircuitsWearables1591
Published Apr 24th, 2022licenseDownloadFavorited
Introduction: 8×8 Neo-pixel Matrix Face Mask Using WS2812 + ESP-0 and WLED Firmware
8×8 Neo-pixel Matrix Face Mask Using WS2812 + ESP-0 and WLED Firmware
8×8 Neo-pixel Matrix Face Mask Using WS2812 + ESP-0 and WLED Firmware
8×8 Neo-pixel Matrix Face Mask Using WS2812 + ESP-0 and WLED Firmware
In this article, we will learn how to make an 8×8 Neo-pixel Face mask using an ESP-01 wireless module and how to control it via WLED firmware. The WS2812 LEDs are easy to use and work on almost every IoT module. I will be using 60 led's/m strips in this project and the total count of LEDs will be 64.

The circuit is powered by a 3.7 V battery with a battery recharging module and a couple of switches. The effects and colors will be controlled through WIFI via the WLED HTML page on various devices.

Supplies
1.Soldering Iron

2.Wires

3.Pushbuttons or Slideswitch

4.Heat shrink tubes

5.Transperant insulating tape

6.Hot Air Gun

7.Velcro

8.Dark coloured cloth ( I will be using Black colour cloth )

9.Flat Elastic thread

10.ESP-01 - https://www.amazon.com/dp/B01EA3UJJ4?ref_=cm_sw_r_cp_ud_dp_EPXF638KDPX2VMPMP6ZK

11.LD1117 3.3V Voltage Regulator - https://www.amazon.com/dp/B07MVV3JGP?ref_=cm_sw_r_cp_ud_dp_GY8HT281BJ62ASSKPRMW

12.WS2812 Neo-pixel Led's - https://www.amazon.com/dp/B01CDTEJBG?ref_=cm_sw_r_cp_ud_dp_FYPMQNAF3BH7VK6MDRJQ

13.3.7 Lithium ion battery - https://www.amazon.com/dp/B086Q7FJDT?ref_=cm_sw_r_cp_ud_dp_XWC365HCKP55GCAMTDE9

14.TP4056 1A Li-Ion Battery Charging Board Micro USB with Current Protection - https://www.amazon.com/dp/B00LTQU2RK?ref_=cm_sw_r_cp_ud_dp_9BRN4MZJAJQ6XS9MD2P6

=================***Links***=====================



1.Arduino IDE/ NodeMCU-PyFlasher-4.0-x64 ( I have used NodeMCU-PyFlasher-4.0-x64 to flash WLED Firmware)

2.How to program an ESP - 01 module

1.https://github.com/Aircoookie/WLED (WLED github link)

2.https://github.com/Aircoookie/WLED/releases/download/v0.13.1/WLED_0.13.1_ESP01.bin ( WLED Firmware for ESP-01)

Add TipAsk QuestionCommentDownload
Step 1: Making Mask
Making Mask
Making Mask
Making Mask
Making Mask
Make a face mask using any dark-colored cloth.
I have used a black color cloth.
Sew it as per your requirement and size.
Make a pocket-like section for inserting the LED matrix.
During the daytime, this section can be used to put a filter inside it.
Since it is made up of cloth so it is washable and reusable.
Add Velcro at inserting section by which we can insert the matrix in the section.
Add TipAsk QuestionCommentDownload
Step 2: Setting Up Esp-01 and Programming
Setting Up Esp-01 and Programming
Setting Up Esp-01 and Programming
Programming ESP-01 using NodeMCU software or Arduino IDE. Use the bin file for flashing after flashing don't forget to restart the module.
Add TipAsk QuestionCommentDownload
Step 3: Soldering
Soldering
Soldering
Soldering3 More Images
Before soldering components please do check on a multimeter that all components are working fine because more than 4 V can damage the esp-01 module.
Soldering all the components as given in the schematics/circuit diagram.
After soldering cover all soldering points using insulating tape or heat shrink tubes to avoid a shock circuit.
Do the connections as following
Data In pin ==> GPIO2
5v ===> Vin of LD1117
GND ==> GND of LD1117
LD1117 3.3v Vout ====> ESP-01 VCC and EN/CH_PD pins
TP4056 output ===> LD1117 Vin
TP4056 GND===> LD1117 GND
Battery +ve ===> TP4056 input
Battery -ve ===> TP4056 GND
Please connect buttons between battery and LD1117 as well as in between GPIO2 and Data In pin of LEDs.
Add TipAsk QuestionCommentDownload
Step 4: Configuring
Configuring
Configuring
Configuring5 More Images
Now only power up the esp-01 and keep the GPIO2 ==>LED Data In off.
As shown in the above pictures you will see the Default Access point name of esp-01 As WLED-AP.
Its default password will be wled1234.
We can change the Access Point name and password as per our requirement.
The HTML page will open up automatically and by using this page we can set up the number of LEDs.
Now choose the color and effect.
After choosing the color we can turn on the data pin switch (if we turn on both the switches then the access point will not be visible) .
Add TipAsk QuestionCommentDownload
Step 5: Finalizing
Finalizing
Finalizing
Finalizing
We have successfully built our LED face mask.
Charge the battery at a healthy capacity use the battery charging module indicator light (ona full charge it will turn blue)
Now put the Neo-pixel LED matrix in the pocket section of the mask.
Now we can glow in the dark.
Add TipAsk QuestionCommentDownload
Wearables Challenge
Participated in the
Wearables Challenge

View Contest
Be the First to Share
Did you make this project? Share it with us!

I Made It!
Recommendations
Life Sized Talking BMO From Adventure Time (that's Also an Octoprint Server!)
Life Sized Talking BMO From Adventure Time (that's Also an Octoprint Server!) by katzcreates in 3D Printing
 16  1.1K
Color-Changing Prom Dress With Magic Wand
Color-Changing Prom Dress With Magic Wand by kellechu in Wearables
 124  16K
3D PRINT a STEAM TRAIN 🚂 With Live Camera Streaming and Wifi Controls 
3D PRINT a STEAM TRAIN 🚂 With Live Camera Streaming and Wifi Controls by DIY Machines in 3D Printing
 167  16K
LATTEintosh DIY Mini PC
LATTEintosh DIY Mini PC by Arnov Sharma in Computers
 62  7.1K
Back to School: Student Design ChallengeBack to School: Student Design Challenge
Cheese ChallengeCheese Challenge
Teach With Tinkercad ContestTeach With Tinkercad Contest

Add Tip
Ask Question
Post Comment
We have a be nice policy.
Please be positive and constructive.

Add Images
Post
Open Menu8×8 Neo-pixel Matrix Face Mask Using WS2812 + ESP-0 and WLED Firmware by AdityaG116FollowDownload Favorited I Made It View Comments Share More Options
AdminEdit Instructable
Categories
Circuits
Workshop
Craft
Cooking
Living
Outside
Teachers
About Us
Who We Are
Why Publish?
Resources
Sitemap
Help
Contact
Find Us
© 2022 Autodesk, Inc.

Terms of Service|
Privacy Statement|
Privacy settings | Do not sell my personal information|
Legal Notices & Trademarks
Autodesk
