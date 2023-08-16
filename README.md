# Schematics-MV1F
 
Neo-Geo was introduced to the world on 1990.

The Neo Geo originally launched as the Multi Video System (MVS) coin-operated arcade machine. 

With its games stored on self-contained cartridges, a game cabinet can easily be changed to a different game title by swapping the game's cartridge and cabinet artwork.

The Neo Geo was marketed as the first 24-bit system; its CPU is actually a 16/32-bit 68000 with an 8-bit Z80 coprocessor, while its GPU chipset has a 24-bit graphics data bus. 

According to serverals sources, this is the 8th revision of this board.

## Reading scanned schematics
On the scanned original schematics, there is some funny informations:

### Components identifications 

All majors components were identifed by an ID composed with 2 characters: an number from "1" to "9" and a letter from "A" to "L"; this _identification_ can be not unique.
in fact, it doesn't identify the component itself but the coordonate on the board, where the number identify the column and the letter the line.

![PCB components Coordinates](https://github.com/Neo-Geo-Hardwares/Schematics-MV1F/blob/main/img/mv1f_coordonate.jpg)

It could be followed by a second letter, wich identify the "sub" part of the component (the second AND gate of a 74LS05 will be identifed as "5L**B**").

### Errors and missconceptions

During the process of understanding, I've seen severals issues and typo error.

 * On Page 1, the 74HC32 (Quad 2-input OR Gates) use the 2 drawing convention for 2-input OR Gate, it's confusing.
 * On Page 3, another 74HC32 (Quad 2-input OR Gates) use the "alternative" drawing convention for an 2-input OR Gate, so far I didn't find any usage of the 3 other gates from this IC.

![OR Gate](https://github.com/Neo-Geo-Hardwares/Schematics-MV1F/blob/main/img/logic_gates_OR.jpg)
![2-Inverted Input NAND Gate](https://github.com/Neo-Geo-Hardwares/Schematics-MV1F/blob/main/img/logic_gates_Inverted_NAND.jpg)

 * 
 * On Page 3, the pinout of the JAMMA's Blue (**B**) pin is correctly identified (**12**) and mislabelled as **GREEN**, the JAMMA's Green (**G**) pin is also correclty referenced (**N**) and mislabeled as **BLUE**
