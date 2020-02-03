# The SN76477

Is a complex sound generator in the form of a monolithic chip produced by Texas Instruments in 1978. If you played ***Space Invadors*** or ***Sheriff*** it was this chip that gave you the sound effects. 

Being a kid of that time, and one interested in sounds and music, I felt building up a synthesisor around this chip was a good way to learn electronics. This repo is my own private Idaho and hopefully it's of some use to you. 

## Footprint

![Layout](/images/boardlayout.png)

The chip is a 28-DIP and has the following measurements: 

- 1.78 Mm (0.07 In) Pitch
- 10.16 Mm (0.40 In) Span
- 25.15 X 8.89 X 5.08 Mm Body

Looking inside the chip via an X-ray is cool

![Layout](/images/xray.png)
![Layout](/images/xray2.png)

I've created an Eagle library of the above, so you can just import it into your project and use it straight away. 

## Breakout Board

To make this work better with modern bread boards, you need a breakout board in order to connect all the various components up to. 

![Layout](/images/breakoutboard.png)

Eventually this will be turned into a fully-fledged PCB
