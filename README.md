# RISE

Everything related to the *Penn State Rocket Lab Initiative*.

Currently working on writing a program and designing a model rocket on which I will launch a Raspberry Pi Zero W with an array of sensors.

Very much still *in progress*.

## Don't do this

![ShortedPowerBoost](/resources/ShortedPowerBoost.jpeg)

## To do

### Orient the STLs correctly!
### M2.5 definitively!
#### I got mine from an old hard drive lol

- find appropriate camera resolution and framerate, [here's a helpful article](https://picamera.readthedocs.io/en/release-1.10/fov.html)
  - the spycam is the same as the picamera v1
- make script start on startup
- stop collecting data on landing, when the pressure data is no longer changing
- Should we truncate the data after a certain point to decrease file size? Like the hundreds or thousands place
  - Looking at the csv file, it seems that the digits repeat themselves, that there are only so many distinct messages

## Assembly instructions

### Parts required

- 12X 5mm M2 screws
- Printed parts
  - The sensor spacers were printed out of TPU
  - SkeletalFairing was made out of PLA at 215C
