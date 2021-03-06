
# Deck Tape 

<p align="center">
  <img src="https://github.com/TakinB/Gizmo/blob/master/side%20view.jpg?raw=true"/>
</p>

Deck Tape is a tribute to cassette players. It's an audio visualizer that integrates sound, color, and touch. 
An Arduino Uno board is used to control LED lights as well as the speed and direction of a DC motor based on the volume of the environment sounds and music.

A magnet is mounted on top of each DC motor which creates patterns in iron filings on the box top surface.

<p align="center">
  <img src="https://github.com/TakinB/Gizmo/blob/master/flowchart.png?raw=true"/>
</p>

**Why magnets?** 
>Cassette players use an electronic magnet to permanently change the orientation of magnetic oxide materials on the cassette tapes.

**Why cassettes?**  
>When I look back, I remember every cassette tape that I owned and my emotions when listening to them. However, it wasn't the case with my digital album collections. So I started with the question of: How can we bring the physical interaction that we had with cassette tapes into the modern way of listening to music?

In order to recreate the physical interaction with a cassette player, push buttons in Deck Tape is made with the same metallic latches that cassette players use. In other words, when you press buttons, you'll hear the same nostalgic click of old cassette players.
Also, users can change the patterns being shaped by the magnet by playing with the iron filings. In addition, LED colors and intensities change based on the historical volume of the song.

<p align="center">
  <img src="https://github.com/TakinB/Gizmo/blob/master/top%20view.jpg?raw=true"/>
</p>

## Getting Started
**Hardware:**
You will need the following in order to build the hardware:

 1. ring magnets (2) 
 2. DC motors (2)
 3. mirror acrylic 
 4. clear acrylic 
 5. walnut tree wood sheet
 6.  sound unit 
 7. Arduino Uno 
 8. power supply 
 9. LED strip Neo Pixel 
 10. L293D motor driver

**Software:**
You will need the following libraries installed for Arduino:
[Adafruit's NeoPixel library](https://github.com/adafruit/Adafruit_NeoPixel)

## Schematics
Please refer to the schematics folder on how to wire up the board with motors, sound module, and LED strip.

## Licenses

 - Bahareh Saboktakin, Royal College of Art, 27/11/2018
 - SparkFun Addressable RGB LED Sound and Music Visualizer Tutorial Arduino Code by Michael Bartlett date: 2/7/16 and 27/11/18 license: Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)







