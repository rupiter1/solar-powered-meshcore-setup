BOM:
https://heltec.org/project/wifi-lora-32-v4/

this is the main board and brain/transmitter 20usd (24usd with shipping to new zealand)
These items: 
Solar panel 2.08nzd
https://www.aliexpress.com/item/1005005721676312.html?

Solar charger (CN3791 6volt) 5.54nzd
https://www.aliexpress.com/item/1005012291361698.html?

Antenna (915mhz GIZONT) 24.23nzd
https://www.aliexpress.com/item/1005009210548173.html?

Antenna Adapter (n-type to u.fl) 16.80nzd
https://www.aliexpress.com/item/1005009210548173.html?

are all from aliexpress which inculdes tax and shiping in nzd and usd(estimated)

sub total ailexpress 48.65nzd (27.32USD)
<img width="426" height="359" alt="image" src="https://github.com/user-attachments/assets/f6e40222-3904-4d0a-ac8b-fd1e6311c93b" />


total (heltec + ailexpress) = 51.32USD

im spending these hours researching what i need to create a custom Meshcore repeater. i've researched: meshcore unit 1: solar panel 2: solar charger 3: batteies 4: antenna 5: antenna adapter 6: all prices are nzd

1: as i did my research to find the best cheapest and easiest to use meshcore unit. i found out very quicky that almost everyone is saying get the heltec v3 (for older videos) and with newer info i found people liked the heltec v4 more than the v3 for it's higher output power 27dbi (roughly 500mw) and it's based on the esp32 s3, which makes this board quite cheap and quite powerful(useful). i've picked this right from the heltec site.
<img width="1314" height="933" alt="Screenshot 2026-10-03 223620" src="https://github.com/user-attachments/assets/2ebcd363-afb9-4442-ae72-388e402460b1" />

2: picking the right solar panel for heltec v4 which draws roughly 140ma at 3.8volts. from this info i knew i wanted a one wat solar panel as 1 wat is the max it can pull in and we need to account for the fact that the power consumption jumps up to 500ma when it's transmitting. also as i live in new zealand the only reasonably priced store to buy this from is AliExpress. i know that often these panels end up not producing the full 1wat. i also know that two 18650 batties is a good sweet spot between power and size.
<img width="1358" height="880" alt="Screenshot 2026-10-03 215722" src="https://github.com/user-attachments/assets/0a8394e5-2910-427a-9bfa-529b845b890b" />
<img width="1864" height="881" alt="Screenshot 2026-10-03 214815" src="https://github.com/user-attachments/assets/73af6289-63b3-4cb5-b099-be9cd5ef689c" />

3: now to pick the solar charger. i do know that the heltec has it's own little solar charger built in but i would like to separate the solar panel from the most expensive part of the project. for this project there was only one board that was even talked about. it's the CN3791. again from AliExpress
<img width="1863" height="842" alt="Screenshot 2026-10-03 220525" src="https://github.com/user-attachments/assets/88f94347-b565-4bdd-8809-0333c02c7b59" />

4: batteries. this one doesn't affect me too much. im just going to use two cells from my friend, wired in parallel to stay at the roughly 4.2v of the charger.

5: antenna: this one is deep and confusing but i've got what i need. i've learnt that it's very import to get an antenna that right for your project. in new zealand our meshcore runs at 915mhz, and i want a somewhat high gain antenna because im just using this as a repeter so it's going long distances and doesn't need to have good range under it or above it. alpha antenna's are often picked for these but in new zealand there not nearly worth shipping here, so i picked a well regarded AliExpress brand called GIZONT Store. I picked a somewhat smaller n-type connecter that has a good signal to noise ratio of 1.2 at 915mhz (i think it's snr)
image.pngimage.pngit says $13.29 but really it's 21.07 before tax because of there weird bonus system.
<img width="1212" height="299" alt="Screenshot 2026-10-03 221336" src="https://github.com/user-attachments/assets/8150c15e-fb8c-41f2-8832-bf9c232a8db9" />
<img width="1860" height="783" alt="Screenshot 2026-10-03 221838" src="https://github.com/user-attachments/assets/4bfe3995-19c8-44fe-a67d-3894ff308dc3" />

6: the antenna adapter is a simple one. longer cables or lower quality ones can add noise but unless there straight up broken a 20cm cable is absolutely fine. this 20cm is just an n-type to u.fl adapter cable. from AliExpress
<img width="1875" height="866" alt="Screenshot 2026-10-03 222828" src="https://github.com/user-attachments/assets/5856fe78-a2d8-497d-9261-b31831464e57" />





What's next!?

im planing to 3d model a housing for this tec, but i'd like to do it while i have the gear because i have made a few projects like this before and i go through versions after versions and i need the gear to test, fix and rebuild. this is for the lack of an stl or pcb.
<img width="591" height="620" alt="Screenshot 2026-10-03 125026" src="https://github.com/user-attachments/assets/1afa7019-bfd8-45c8-8c3e-c083acbf709d" />

this was an idea for a housing for the gear, it was good to get my ideas out in onshape but im going to restart with the learnings of making that housing.

and im not sure how to add my BOM into the read me so please check the main github, for the file listed BOM, which holds all that data :P
