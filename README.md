![counter](https://enp0tr91vnxl0ju.m.pipedream.net)

# Marlin for Diggro Alpha 5 3D printers

Since Anet has released an exact copy of their ET4 Pro 3D printer, the Diggro Alpha 5, with the same impractical kind of firmware, I decided to take my chances and try  installing Marlin on this machine. The machine itself is good foundation for future mods, but the firmware is rendering this printer almost useless in my opinion. If you had ever anything to do with setting up Marlin, then the original firnmware will annoy you very much. I promise. Although the printers are very similar, in my case the config for ET4 Pro (which is the exact equivalent of Diggro Alpha 5), didn't work as expected.

The original developer of this Marlin fork, https://github.com/davidtgbe, has put a great effort to deliver a Marlin version for the Anet ET machines and he did it very well. I've just worked on the config, and fine tuned the UI a bit, so remove a bit of the guess work for Diggro Alpha 5 owners attempting to flash their machines with this firmware.

# Important notes on flashing

The process is not straightforward, but for someone with some 3d printer moding experience it shouldn't be that hard. Every single step is well documented in tutorials or videos. I will list the most important informations to take into consideration before flashing below. It is goode to use Visual Studio Code IDE and the Platormio extension, which is used to compile the firmware.

- Warranty void - you need to remove the bottom lid to get access to the programing pins. This may and will damage the warranty seal.
- You need to have a ST-LINK compatible programmer in order to flash the bootloader or the firmware
- It's good to make a backup of the original fimware in case you brick your machine or just want to return to the original software
- If you have any issues with your Diggro Alpha 5 printer, just look for solutions for Anet ET4. There is a lot of them on the net.

# Help & tutorials

-   Building the firmware with VSC: https://github.com/davidtgbe/Marlin/blob/bugfix-2.0.x/docs/Tutorials/build-es.md
-   Flashing the firmware build: https://www.youtube.com/watch?v=dyTOkUW0aas
-   Useful tips: https://www.youtube.com/watch?v=1NYQkeClfD8

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
