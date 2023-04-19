# ALU Construction notes

Everythign is modular and made o smaller blocks until we get logic functions


## MACRO ALU

Components for Macro ALU (16 BIT):
	- 16x 1 Bit ALU
	- 1 ALU controller 

Placing:
	- HILBErt CURVE FOR timming tree
	- stacked for normal
	- snaking


## MICRO ALU (1 Bit)

Outputs:
	- Result
	- Set
	- Overflow
Inputs:
	- A
	- B
	- Ainvert
	- Binvert
	- Carryin
	- Operation

Components
	- 2 control bits multiplexer for the output
	- full adder
	- And
	- or
	- 2 inverters with multiplexer for (A,B)invert

 
