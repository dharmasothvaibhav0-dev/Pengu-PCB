# Pengu-PCB
Using an Astable Multivibrator to light up different LEDS automatically, the LEDS as the eyes oscillate and flash after one another (Like they are winking)

<img width="978" height="868" alt="image" src="https://github.com/user-attachments/assets/69b40179-db27-4d0f-bd74-6d9d73ea2dd9" />

-----------------------------------------------------------------------------------------
# The Circuit

The Main components in my circuit includes 6 resistors, 2 capacitors, 2 transistors, and 8 LEDS. The circuit itself is basically an Astable multivibrator which is what causes the oscillation to occur. I originally intended to create a seperate Bistable multivibrator, however it did not work as expected so I connected the components from the bistable to create one big Astable circuit. Because of the Astable circuit type, it causes the LEDS to flash one after another in a pattern. An observation I made was that the pattern for the bottom LEDS can also swap if we were to reroute the wires to the opposite collector which was interesting to me. 


<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/28629083-2bf3-41ef-a2a2-d7089c1a3294" />




--------------------------------------------------------------------------------------------------
# Falstad Circuit link

I created the circuit using Falstad. Feel free to try it out!

https://is.gd/EEGnGU


------------------------------------------------------------------------------------------------

# PCB Design


I chose to convert my Circuit into the design of a penguin. I used the main two LEDS part of the Astable circuit as the eyes for the penguin, and the other LEDS I attached as arms.

Front of the PCB- 
<img width="533" height="550" alt="image" src="https://github.com/user-attachments/assets/b2658460-c288-49ca-9c63-f802d3be6dda" />

Back of the PCB- 
<img width="596" height="571" alt="image" src="https://github.com/user-attachments/assets/7c2d7f4f-a76f-4c9a-ba10-a0354473dc4e" />

