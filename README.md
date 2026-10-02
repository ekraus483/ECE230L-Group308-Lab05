## Name
Ethan Kraus, Jason Wu
## Lab Summary
The purpose of this lab was to learn how to write basic verilog code which connected the physical elements of the board to the code itself and the circuits we define in them. While we did again use a k-map like last lab, the primary focus was on writing the verilog code itself, both in the constraints and the top level file.

## Lab Questions

### 1 - Explain the role of the Top Level file.
The role of the top level file is to connect our circuit files into one, overall program to then be run on the circuit board itself. It is where we connect the sw, led, or other variables which correspond with the hardware itself. We can also use it to connect parts of individual circuits to each other, like we did in this lab.
### 2 - Explain the function of the Constraints file.
The function of a constraints file is to connect the real physical components to the circuit that you design in verilog. The constraints are also a per board file so it’ll depend on the board. It also defines the components for the top.v file.
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
Minterm worked well for the second circuit, but maxterm was not a good choice for the first circuit. Using a max term k-map produced a 2-term solution, which could be later simplified down to a 1-term solution; however, a minterm k-map would produce the 1-term solution immediately. 



