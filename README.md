# Stacey's Computer from A View To A Kill. (A Software Forgery).
A recreation of Stacey's Apple IIc program from the 1985 James Bond film A View To A Kill. Written in Applesoft Basic for the Apple II. By [Max Piantoni](https://www.maxpiantoni.com) 

**[Click here for an in depth video about this project on YouTube](https://youtu.be/YGVfwEEjRfs)**

## Instructions
- To run this project, download  VTAK.dsk and run it in on your Apple II (or in an emulator).
- To transition between the graph screen and the map screen press any key on your Apple's keyboard.
- This project has been tested on an Apple //c and an Apple //e, results may vary on earlier machines with less RAM.

## Links & Coverage
Much to my delight, this project has reached others who sit within this Venn Diagram, those who love Apple IIs and James Bonds...

- [A lovely writeup by Blake Patterson on Byte Cellar](https://bytecellar.com/2020/04/29/apple-c-scene-from-80s-bond-film-a-view-to-a-kill-perfectly-re-created-with-applesoft-basic/)
- [Some great comments over at Hacker News](https://news.ycombinator.com/item?id=23027207)
- [There's also some great comments on the YouTube video about the project](https://youtu.be/YGVfwEEjRfs)

## Software & Tools
Here's a list of the tools used to develop this:

Apple II Software I Used:
- Apple Mechanic for creating shape tables
- MousePaint for adding the text to the map
- Copy II Plus for moving files between disks etc
- The boot disk uses DOS 3.3
- I also looked at but didn’t use a bit of other Apple II software while I was deciding what to do about text on the HGR screen. Including The AppleSoft toolkit font thing (I think called animatrix), Fontrix, Beagle Graphics, some other beagle font tools, etc 

Mac Software I Used:
- Visual Studio Code to write the code
- Virtual II as the emulator, I also created the disk images in virtual II and imported files (using its ability to mount a folder as a disk). Once the files were imported I  moved them around using Copy II Plus.
- Affinity Designer for drawing the coastline for the map (not the label text though). I also figured out the best way to draw my circles in Affinity before plotting them manually in Apple Mechanic. My first pass at freestyle plotted circles were charming but wonky.
- Buckshot for converting the coastline drawing to HGR data
- ADT Pro to send the disk image to my Apple IIc and write it to 5.25 floppy


