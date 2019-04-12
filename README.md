# Vioce-Changer
 I want to make a realtime vioce changer for the final project.

## Summary
The realtime vioce changer will be interactive that transforming and modifying vioces with effects. I did several research about this subject, and I found that whether is a hardware or software vioce changer,the principle is to change the soundtone by changing the frequency of the input sound, so that the output sound is different from the original one. A vioce changer works in shifting the pitch-sensitive fundamental waves of the users voice and offer various pitch shift options. In another word, compressing or expanding time can change the outout effect of vioces. Many project achieved the goal by transforming vioces into 'number'(such as granular synthesis -a technique of joining and layering lots of very short audio samples or “grains”). Basd on those principle of the vioce changer, auduino is suited for making it. It can achieved time-compressing or stretching one loop, repeating or dropping short segments to keep up with realtime or combining voices with a sine wave to create a digital ring modulator effect.

## Component Parts
1. 
-Arduino Uno (an older Arduino Duemilanove or “328” Diecimila can be used as well…but not an Arduino Mega nor Leonardo, sorry).
-Adafruit Wave Shield.
-Adafruit Microphone Amplifier Breakout.

2.
-Arduino Uno
-Arduino Uno shield
-12-bit ADC (converting mic input to a digital signal)
-12-bit DAC (converting the modified digital sound back to an analog audio signal)
-low-pass filter -resistors and capacitors (filtering out some of the noise from the signal)

## Challenges
I think the challenges would be the hardware parts. I was confused while looking up several tutorials, which people used different component parts for approaching the goal. The method seems to be long and complex, and before taking this class,I've never try hareware project. 

## Timeline
- Week 1: Write proposal
- Week 2: Buy main components and try to figure out how these works
- Week 3: Do the schematic and code part
- Week 4: Test
- Week 5: Present!

## References and link
https://www.instructables.com/id/Dalek-Voice-Changer-Arduino-Shield/
https://learn.adafruit.com/wave-shield-voice-changer/overview
http://www.pimall.com/nais/nl/n.howvoicechangerswork.html
