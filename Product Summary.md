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
> What skills did you used to produce the model of your prototype ? (3D modelling, ...) If theorical reflexionn was needed, please inform your reflexion (ex: mathematical reflexion with result used). If you have these reflexions on a specific file please add it to the folder and list it in the table here under.


### What are the files used for conception
> List all the conception files used for this project, this could be 3D models, or 2D sketch. For each precise the software used

Conception Files | Descritpion | Software
-----------------|-------------|---------
*Ex : Model.skp* | *3D model of the product* | *Sketchup*

## Product Manufacturing

#### This file shall store all the information realted to the manufacturing of the product. The manufacturing might be related to a freezed version of the conception of the product.

## Raw material used for the mnufaturing
Reference | Type (tag) | Description
----------|------------|------------
*A* | *Wood plate*| *raw wood plate dimension : l :300mm L:200mm : e: 12mm*

## Steps for manufacturing of the product ?
> Describes the different steps needed to go from a parent conception file to the actual manufacturing of the product

Steps # | Type of operation (Tag) |  Description 
--------|-------------------------|-------------
1 | *Gcode configuration* | *configure fusion to allows generation of Gcode *
2 | *Gcode convertion* | *convert 3D model to Gcode via the software Fusion *
3 | *CNC setup* | *Install the material **A** on the CNC*
4 | *CNC Machining* | *Launch the machining for part1*

## What are the technics used to manufacture the product ? 
> Describes breifly how a user can manufacture the product, 

 Manufacturing files	| Description	| System	| Software	| Conception parent file	| Material
 ---------------------|-------------|---------|-----------|-------------------------|---------
*Ex : Part1.gcode*	|*Gcode of the part 1 to be manufactured*	| *CNC Openfab	* | *Linux CNC	* | *part1.fusion* | 	*Wood*
