This Project was Born as i could not afford to Buy expensive preprogramed Board's and professional cockpits and button boxes cost upwards of 1000$. So i Decided to Code and build one for realistic experience for Euro truck sim 2 and flight sim.Living in a Third world nation,these things are expensive and hard to come by so i decide to use whatever was available to me and build one using generic available electronics.
I learned a lot also made some mistakes and this repo aims to document the How-To and what not to and everything in between including the code. 

![20241031_171731](https://github.com/user-attachments/assets/aae5e4a0-9db4-4eb5-9b8d-9246dc7b67fb)
![20241031_171735](https://github.com/user-attachments/assets/0e3ea56c-4c07-448a-9c2e-c650ca72414b)


### Software
1. VsCode with Arduino extension enabled or Arduino ide
2. The code from this repo but you would have to change some parts in it as per your pinout's and how you intend to connect your switches,buttons to the respective pins on the arduino


### Hardware Required
1. Arduino Leonardo or Arduino Mega(i made the mistake of not using this and went for the smaller leonardo instead, i built this during semi-condutor shortage thus couldn't find the mega).
2. If using The Leonardo a Tx/sx extension
3. Soldering Iron(optional) if using spade connector switches or you can use spade female connectors crimped to wires using crimping tools.
4. 9x On-On toggle switches, i used omron one's cheaper one's are available
5. 3x On-Off-On toggle Switches
6. 1x Push switch
7. 1x Push tactile switch
8. 2x Led On-off switches one Green one Red
9. 2x Rotary Encoders
10. 2x Pull Switches(to simulate airbrake, parking brake)
11. 1x push switch(engine start,actual automotive/truck spare part)
12. 1x Relistic Key switch(to simulate electics start,Actual automotive/truck spare part)
13. 4x Led's (2 red, 1 yellow, 1 green) to wire up start and give a realistic feel
14. 1x usb cable that connectes to your arduino
15. 1x Electrical Panel Box or Project box as per your liking(I got a generic electrical one,the cheapest i could find).You can build this even in a custom made wooden box.
16. Lots of female female/dupoint quick connect cables(i made the mistake of using small 0.18mm spade conenct switches and soldered) rather use dupoint pin Switches. Or use spade connectors,whatever that you want.

#### Mistakes I made
1. Not using The Arduino Mega, i had to use a tx/sx pin extension,using the Mega would have meant enough pings
2. Not using Dupoint Male quick connect switches,instead using spade connector switches for the smalled on-on switches. Often ending up with cold solder joints.

