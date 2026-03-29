
## 3/23/2026 - 1

I chose to create an Astable Multivibrator, however some of the main problems I ran into was LEDS flashing together rather than separately. The main target was to get the oscillations to show up because that is the whole point of the Astable multivibrator, and after thinking a little bit, I realized this was really similar to a problem I'd encountered in the past which was LEDS flashing together rather than flashing separately. I realized the thing that controls how the LEDS flash, is the values of the resistors and capacitors, and so I lowered the values of the resistors and capacitors to allow it to blink faster giving it and oscillation pattern.

![[Pasted image 20260328195509.png]]
## 3/23/2026 - 2

After completing the main Astable multivibrator which created an oscillation, my initial thought was to add a bistable multivibrator for more LEDS to use in my design to use as arms. 
![[Pasted image 20260328200228.png]]

However after creating the Bistable multivibrator, while trying to test the entire circuit with both the Astable and Bistable multivibrator together, I noticed that the circuit was bugging. The LEDS flashing in the Astable would suddenly both flash together and wouldn't fade away when I tried to activate the LEDS in the Bistable circuit. Also when doing it the other way around, when I attempted to start up the oscillation while the bistable circuit was locked in its position, the bistable would unlock and flash off without activating the other LED.

Ex: ![[Pasted image 20260328200410.png]]
(The LEDS from the Astable just lit up together while trying to activate the bistable at the same time)

Ex 2: ![[Ex2Gif.gif]]
(The Astable flashes, but the in the bistable an LED lights up for a second and disappears instantly.)


After looking online and researching,  I found out that in the simulation it took both circuits, and attached them to the same ground plane (The entire Black area underneath the circuit.). It helped me understand that when one multivibrator was running, if I tried to run the other, it would essentially take most of the power from the ground plane, which would cause the original to malfunction hence why it was glitching. I decided to instead attach the LEDS from the bistable to the Astable one to just create a even bigger oscillation pattern. This process was simple in the end but because I didn't realize that I was supposed to wire the LEDS to the collector end of the transistor, I attached the LEDS to the base of the transistors because I assumed that the current would flow through from there. After trial and error I finally attached the wiring to the correct place, which gave me the oscillation pattern I desired.
![[Pasted image 20260328201434.png]]
Make sure you connect it to the collector and not the base of the Astable circuit to ensure the bottom flashes with the Astable.
Correct Routing: ![[Pasted image 20260324002029 1.png]]
### Time taken to journal: 15 minutes
### Time taken building circuit + researching: 2 Hours.

## 3/24/2026
I started to create the schematic which was fairly simple, just choosing the parts I used on falstad, and connecting them again in the schematic editor.

![[Pasted image 20260328201601.png]]

and when I moved on to creating the actual PCB design I didn't run into any problems there. The only issues was the edgecut being very time consuming due to my penguin design(Mainly trying to round it out). The rewiring of components to eachother took a while at first but it went smoothly, but when I finally found out that I could also wire the harder components on the bottom of the PCB it was easier. Overall creating the entire Schematic and PCB went very smoothly, but took a long time. 

Once that was done, I chose to make a couple of silkscreen edits on my PCB to make it have a penguin nose/face, and you know I obviously had to include the infamous 67 in there.

**BIG TIP**- if the wiring starts to look too complex/confusing, consider wiring some parts on the bottom of the PCB, as it'll free up lots of space and look a little bit cleaner.

Wiring on the top(Red): ![[Pasted image 20260328201635.png]]
Wiring of the Bottom(Blue):![[Pasted image 20260328201654.png]]
### Time taken to build schematic: 30 minutes.
### Time taken to build PCB: 90 minutes.
### Time taken to Build schematic and PCB combined: 2 hours

# Total Time taken overall: 4 hours and 15 Minutes.