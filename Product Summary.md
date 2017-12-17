# Product Name
LBB02 (La Borne à Bonnaud)

## Product Conception

#### This file shall store all the information related to the conception of the product. The goal is to allow anyone to:
- retrieve
- understand
- reproduce 
- and maybe enhance the conception of the product.


### What is the purpose/concept of the product ?
> Describes what is the purpose of your product ? If there are similar/comercial solutions that exists ? 

Building an original bartop runining on emulation station (potentially more than 15000 games!)

### What is the Area of application ?
> Describes who could be the inteded user (ex: programer), or who is able to use it (ex : someone aged between 7-77)

Gamers from 5 to 95 years old

### Who are the makers on this projet ?
> List all the people implicated in the conception of this product.

@Jorgininho (desing, conception, manufacturing)
@nicodb (Manufacturing)

### Principle of conception
> What skills did you used to produce the model of your prototype ? (3D modelling, ...) If theorical reflexionn was needed, please inform your reflexion (ex: mathematical reflexion with result used). If you have these reflexions on a specific file please add it to the folder and list it in the table here under. Leave blank if none.


### What are the files used for conception
> List all the conception files used for this project, this could be 3D models, or 2D sketch. For each precise the software used

Conception Files | Descritpion | Software
-----------------|-------------|---------
*Ex : Model.skp* | *3D model of the product* | *Sketchup*
LBB02v1.f3d | f3d file from fusion 360 project, 3D model of the whole bartop (structure and components) | fusion360


## Product Manufacturing

#### This file shall store all the information realted to the manufacturing of the product. The manufacturing might be related to a freezed version of the conception of the product.

## Raw material used for the mnufaturing
Reference | Type (tag) | Description
----------|------------|------------
*A* | *Wood plate*| *raw wood plate dimension : l :300mm L:200mm : e: 12mm*
A | fir | L:X l:X e:12mm
B | screw | D: L: 
C | component | screen of 15inch
D | screw | D: L: 
E | cable | IDE cable of 1m and 40 pist
F | element | cable lug
G | element | IDE connector

## Steps for manufacturing of the product ?
> Describes the different steps needed to go from a parent conception file to the actual manufacturing of the product

Steps # | Type of operation (Tag) |  Description 
--------|-------------------------|-------------
*1* | *Gcode configuration* | *configure fusion to allows generation of Gcode *
*2* | *Gcode convertion* | *convert 3D model to Gcode via the software Fusion *
*3* | *CNC setup* | *Install the material **A** on the CNC*
*4* | *CNC Machining* | *Launch the machining for part1*
1 | Gcode convertion | from iges manufacturing file  ref:A generate the Gcode for Openfab CNC
2 | CNC machining | from stock (ref:A in raw material) manufacture the wood structure of the bartop
3 | Manutention | Mount the wood structure with screw (ref:B) 
4 | 3D Printing | Print the 3D form for the top
5 | Manutention | Remove feet from screen (ref:C)
6 | Manutention | Mount the screen on the wood structure with screw (ref:D)
7 | Manutention | remove one side of button cable 10mm of sheath(ref:E)
8 | Soldering | bend and solder to naked end of the button cable
9 | Manutention | cut 10mm piece of thermo-retractable sheath and put on each soldered end of the button cable
10 | Manutention | on each end of the button cable, put a lug (ref:F) then retract the thermo-retractable sheath on each
11 | Mantutention | on the other end of the button cable, connect the IDE connector (ref:G)
12 | Manutention | assemble all element together  (wood structure, screen, buttons)
13 | Configuration | install recall box on the raspberry

Now play

## What are the technics used to manufacture the product ? 
> Describes breifly how a user can manufacture the product

 Reference | Manufacturing files	| Description	| System	| Software	| Conception parent file	| Material
 ----------|---------------------|-------------|---------|-----------|-------------------------|---------
*ex:A* | *Ex : Part1.gcode*	|*Gcode of the part 1 to be manufactured*	| *CNC Openfab	* | *Linux CNC	* | *part1.fusion* | 	*Wood*
A | setup_CNC_v1.iges | setup file for CNC of the wood structure of the bartop | CNC Openfab | Fusion360 | LBB02v1.f3d | fir
B | top-left | STL file for the top-left 3D shape | 3D printer | Fusion360 | LBB02v1.f3d | PLA
C | top-right | STL file for the top-right 3D shape | 3D printer | Fusion360 | LBB02v1.f3d | PLA
D | top-logo | STL file for the top-logo 3D shape | 3D printer | Fusion360 | LBB02v1.f3d | PLA
E | top-top | STL file for the top 3D shape | 3D printer | Fusion360 | LBB02v1.f3d | PLA



