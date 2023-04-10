Here are the pcbs made for Electrosocks.

You can also get them on my OSHWLAB page :
 - kicker board : https://oshwlab.com/anonymousse_1/kicker_sn_1
 - frame board : https://oshwlab.com/anonymousse_1/frame-eleksoc

Please be aware these pcbs comport some errors. The ones I've seen are those :
  - On the kicker pcb, I put the octocoupler resistor at the wrong place (should be placed before with the correct resistance, not after)
  - Pillars on the sides of the kicker don't have large enough tracks to use it to power the raspberry pi
  - The dc-dc converter at the front of the frame can not be powerfull enough for the whole robot (we used another one to supply the raspberry pi)
  - Some solderings are tricky and need to be done in a precise way (firstly the sensors connectors on the bottom, cut the pins that overtake on the top, place some tape and then solder the battery holder)
