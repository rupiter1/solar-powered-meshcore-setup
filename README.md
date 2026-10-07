Introduction:
this is my meshcore project. my goal is to bridge my local area to the wilder auckland meshcore network with a Meshcore repleter, meshcore is a open source communications system that offers encryption, public/public messageing and is run on small and reasonably cheap modules (often based on esp32s) with an attached LoRa transmitter and receiver, (long range low power radio)

meshcore is incredibly useful under power-cuts or natural disasters (both often happen in my area of new zealand) moduels like the heltec v4 and most meshcore units draw roughly .5-2 wats making them ideal in these disasters. my goal is to create a meshcore setup where it is recharged by the sun, making it run for a virtually endless amount of time. repeating other's messages to the wider network.  

The BOM (Bill of Materials) is subject to change and I plan to design my own solar charging board as a fun sidequest to this project but for now i would like to keep the scope of this project limited and easy to follow along. but for now the BOM is a great start for someone looking to build there own Meshcore or Meshtastic repeater. there are water proof cages for meshcore projects on aliexpress, but i've built my mine for this setup, as listed here, this is prototype I can't guarantee that all the components will fill perfectly.

<img width="1080" height="1920" alt="meshcore1_1" src="https://github.com/user-attachments/assets/986b3377-cce3-4cce-a258-d3ee7ba87bd6" />
steps to build you're own!
first take you're heltec v4 and connect the antenna, then connect power ( antenna MUST be connected first ) go to the meshcore flasher ( https://meshcore.io/flasher ) and search heltec v4. follow through the process and make sure you're using chrome as some browsers can't connect to the heltec v4
<img width="1919" height="580" alt="Screenshot 2026-10-04 201757" src="https://github.com/user-attachments/assets/f111da99-ac4c-4703-b2da-e3ed41021a66" />


<img width="644" height="689" alt="Screenshot 2026-10-04 144736" src="https://github.com/user-attachments/assets/5ba79b59-43de-41a4-b0f3-999f9c2c4445" />

you're going to be printing this Meshcore case
which is listed under printable files, in the main repo.
the most import thing about this case is that you sand, fill (if needed) and paint it, 3d prints are not water proof but doing these steps will make it much more water resistant. 
then glue the solar mounts onto the main cage, use something like epoxy as it's strong and will last outside. ( will update the design to use screws ) glue one at a time and make sure that's weight on solar mount pressing into the main housing. screw the antenna adapter into the top of the main housing and seal this will a light coat of gap filler. to keep the water out. double sided tap the batteries and solar charger into the bottom tray of the main hosuing, and tape the Heltec v4 ontop of the tray. solder the wires to the solar panels and glue them to the solar mounts while feeding the wires through into the main housing, then fill the hole you came through. connect up the wires acording to the images below,

<img width="1920" height="1920" alt="mesh core wiring" src="https://github.com/user-attachments/assets/2dcd1875-c20a-4562-908f-a7c3dd694665" />=
<img width="1080" height="1920" alt="meshcore1_3" src="https://github.com/user-attachments/assets/33c960f3-6040-4051-99c6-ac16331ff606" />
<img width="1080" height="1920" alt="meshcore1_2" src="https://github.com/user-attachments/assets/42fea5b0-da68-42ef-836b-cf3e61dc401d" />

connect the antenna to the main housing (ontop)
and connect the u.fl side to the heltec v4.
connect power the heltec v4 and verify that it boots up, connect to the board with the Meshcore app, and you're off to the races!
And NEVER, I repeat NEVER! turn the Heltec on without an antenna connected. this will fry the board.

updated with v1.1 case designs!

What's next!?
order parts, refine case, find spot to place repeater, test and record data, report back findings,



make sure to click on the ailexpress links themselfs and dont "open in new tab" for some reason this doesn't work with them.

|Item                            |Price   |Source                                                |
|--------------------------------|--------|------------------------------------------------------|
|Heltec v4                       |24      |https://heltec.org/project/wifi-lora-32-v4/           |
|Solar Panel (2pcs)              |1.17    |https://www.aliexpress.com/item/1005005721676312.html?|
|Solar Charger                   |3.11    |https://www.aliexpress.com/item/1005012291361698.html?|
|Antenna (915mhz GIZONT)         |13.60   |https://www.aliexpress.com/item/1005009210548173.html?|
|Antenna Adapter (n-type to u.fl)|9.43    |https://www.aliexpress.com/item/1005009210548173.html?|
|~400grams pla+                  |5.6     |https://www.pbtech.co.nz/product/INKCRL0175           |
|Total                           |56.92USD|
