# Multiplexer4to1
# AIM:
To simulate and synthesis multiplexer using vivado
# APPARATUS REQUIRED:
vivado
# PROCEDURE:
```
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the Fille Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
```
# Truth Table
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f1dac9e1-e938-4072-bfa9-c17a0a54b7c7)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f8ea8610-f6fc-4de3-a68a-5a9a4cfcd673)
# VERILOG CODE:
```
module mux(a, b, c, d, se, sl,y);
input a,b,c,d, so, s1;
output y;
assign y-s1 ?(s0?d:c): (s0?b:a);
endmodule
```
# OUTPUT:
![WhatsApp Image 2024-04-19 at 19 22 49_7cf6aeda](https://github.com/Afsar1276/Multiplexer4to1/assets/161407741/f32f8e9f-03bb-4d76-afba-3b5dd450c28a)
# RESULT:
Thus, the verilog program for Multiplexer4to1 has been simulated and verified successfully.





