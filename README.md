# RTL design using Verilog with SKY130 Technology


![cover pic workshop](https://user-images.githubusercontent.com/92054999/165689301-956d3570-449c-4e84-adf4-aeab16164152.PNG)

## Brief Description of the Workshop
# *Index*
- [RTL design using Verilog with SKY130 Technology](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#RTL-design-using-Verilog-with-SKY130Technology)
    - [Brief Description of the Workshop](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Brief-Description-of-the-Workshop)

 - [Day 1 - Introduction to Verilog RTL design and Synthesis](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Day1-Introduction-to-Verilog-RTL-design-and-Synthesis)
              
    - [Part 1:Introduction to open-source simulator iverilog](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#part-1-Introduction-to-open-source-simulator-iverilog)
      - [Sub-Part 1: Introduction to Command prompt and Library](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-Part-1-Introduction-to-Command-prompt-and-Library) 
      - [Sub-Part 2: Introduction to iverilog design test bench](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-Part-2-Introduction-to-iverilog-design-test-bench) 
    - [Part 2:Labs using iverilog and gtkwave](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-2:Labs-using-iverilog-and-gtkwave)
      - [Sub-part 1: Introduction iverilog gtkwave](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-1-Introduction-iverilog-gtkwave)
    - [Part 3:Introduction to Yosys and Logic synthesis](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-3:Introduction-to-Yosys-and-Logic-synthesis)
      - [Sub-part 1:Introduction to yosys](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-1-Introduction-to-yosys)
      - [Sub-part 2:Introduction to logic synthesis](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-2-Introduction-to-logic-synthesis)
    - [Part 4:Labs using Yosys and Sky130 PDKs](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-4:Labs-using-Yosys-and-Sky130-PDKs)
      - [Sub-part 1:Introduction to yosys Synthesis tool](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-1-Introduction-to-yosys-Synthesis-tool)
 - [Day 2 - Timing Libs,hirarchical vs flat synthesis and efficient flop coding styles](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Day-2-Timing-Libs-hirarchical-vs-flat-synthesis-and-efficient-flop-coding-styles)
   - [Part 1:Introduction to Timing libs](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-1-Introduction-to-Timing-libs)
   - [Part 2:hierarchical vs flat synthesis](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-2-hirarchical-vs-flat-synthesis)
     - [Sub-part 1:Hierarchiacl synthesis](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-1-Hierarchiacl-synthesis)
     - [Sub-part 2:Flat synthesis](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-2-Flat-synthesis)
     - [Sub-part 3:Sub module synthesis](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-3-Sub-module-synthesis)
   - [Part 3:Flop Coding styles and optmization](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-3-Flop-Coding-styles-and-optmization)
     - [Sub-part 1:Introduction to flop](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-1-Introduction-to-flop)
     - [Sub-part 2:Coding style](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-2-Coding-style)
     - [Sub-part 3:Optimization Technique](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-3-Optimization-Technique)
- [Day 3: Combinational and Sequential optimmization](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Day-3-Combinational-and-Sequential-optimization)
   - [Part 1:Introduction to Optimization](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-1-Introduction-to-Timing-libs)
   - [Part 2:Combinational Optimization](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-2-Combinational-Optimization)
   - [part 3:Sequential Optimization](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#part-3-Sequential-Optimization)
       - [ Sub-part1:Sequential optimisation unused outputs](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part1-Sequential-optimisation-unused-outputs) 
 - [Day 4:GLS,Synthesis simulation Mismatch and Blocking/Non blocking statements](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Day-4-GLS-Synthesis-simulation-Mismatch-and-Blocking-Non-blocking-statements)
   -  [Part 1:GLSConcepts And Flow Using Iverilog](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-1-GLS-Concepts-And-Flow-Using-Iverilog)
   -  [Part 2:Blocking And Non Blocking Statements](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-2-Blocking-And-Non-Blocking-Statements)
   -  [Part 3:Synthesis Simulation Mismatch](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-3-Synthesis-Simulation-Mismatch)
       - [Sub-part 1:Missing of sensitivity list](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-1-Missing-of-sentivity-list) 
       - [Sub-part 2:Blocking Statement & non-blocking statement](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-2-Blocking-Statement-&-non-blocking-statement)
 - [Day 5: IF,case,for and generate for](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Day-5-IF-case-for-and-generate-for)
   - [Part 1:If and case construct](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-1-If-and-case-construct)
       - [Sub-part 1:IF construct](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-1-IF-construct)
       - [Sub-part 2:Case construct](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-2-Case-construct)
   - [Part 2:for loop and generate for](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Part-2-for-and-generate-for)
       - [Sub-part 1:for loop ](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-1-for-loop)
       - [Sub-part 2:generate for](https://github.com/ayushkashyap12/-sky130RTLDesignAndSynthesisWorkshop/edit/main/README.md#Sub-part-2-generate-for)
 - [References](https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop/blob/main/README.md#References)
# Day 1: Inception of Verilog Simulator-iVerilog, yosys and Skywater

On the First day, We learnt about the different tool used here  i.e.(iVerilog-Used for RTL Simulation and Gate Level Simulations,yosys-Opensource Logic Synthesis Tool,Skywater 130nm Standard Cell Libraries) and concept of simulation and synthesis were analysed.

## Part 1:Introduction to open-source simulator iverilog
### Sub-Part 1: Introduction to Command prompt and Library
  - The command used to create the folder and git clone is shown below :
  ![l1](https://user-images.githubusercontent.com/92054999/165711632-1569ef7e-51db-4e42-87df-f62820d9eef4.PNG)
  - Basic command such pwd, cd, ls and git clone in the command prompt were learnt.
### Sub-Part 2: Introduction to iverilog design test bench
  - In the library sky 130, we have pre Installed Verilog files. We have used iverilog simulator to run good_mux.v file.
  

![l2_b (intro to i verilog and gktwave)](https://user-images.githubusercontent.com/92054999/165744826-73e3c845-44ab-42ca-b5bf-b67d5cdc63e4.PNG)

## Part 2:Labs using iverilog and gtkwave
 ### Sub-part 1: Introduction iverilog gtkwave
 - After the simulation, gtkwave was obtained and we analysed the output of the good_mux.v.
  
 ![l2_c (gktwave)](https://user-images.githubusercontent.com/92054999/165745314-dfa75527-50c1-48cd-9a17-2c30eee580cf.PNG)
 - We can also the verilog code using the editor as shown below:
    
   
![l2_d(file code seen)](https://user-images.githubusercontent.com/92054999/165745846-90de0c84-6f04-4948-9596-4af9dc092c78.PNG)

## Part 3:Introduction to Yosys and Logic synthesis
 ### Sub-part 1:Introduction to yosys
  - Basically , this is the synthesizer we have used here. It is the tool to convert rtl into netlist.
  - The flow graph of the of  the setup  is shown below:

   ![woww 2](https://user-images.githubusercontent.com/92054999/166156724-5b0a3e18-3b3c-4385-b7bd-3a1ca52e868a.PNG)

  
   - The simulation is done by giving design and test bench to the simulator tool i.e iverilog and then  value changed dumped file is obtained, we can see the timing 
     analysis in the gtkwave window.
    




  - The primary input and primary output will remain same between RTL design and Synthesized list-SAME testbench can be used.
  ### Sub-part 2:Introduction to logic synthesis
  
  - Register Transfer Level (RTL) It is the behavioral representation of the required specification. The Figure is shown below, which explains clearly
 
```
module(input a,output b);
assign y=b;

endmodule

```
 
  - Synthesis is the process of the conversion of RTL to gate level translation
  -  The RTL and the library file is fed into the synthesis i.e. yosys and then the generated figure is netlist.
  - The design is converted into gates and the connections are made between the gate and this file is called netlist.
       

 
  - .lib file is the collection of the logical modules i.e basic logic gate and,or etc.
  - The gate can be slow or fast depending on the use of the circuit.
    
  -Combination delay in logic path determines the maximun speed of operation of the digital logic circuit.
    ![woowww1](https://user-images.githubusercontent.com/92054999/166156973-4abd9c02-be91-49a5-bdfd-dae6758ca711.PNG)

    
   - So, we need cells that work fast to make Tcombinational delay small.So, the setup time is constraint is met.
   - However, We also need cell that work slow to meet the hold time constraint.
   

![c3](https://user-images.githubusercontent.com/92054999/165756668-5618b6ee-0cb2-4101-a7b8-4e139f42bbb0.PNG)
   - .lib contain slow as well as fast cell ,depends on the circuit usage.
   - Comparison of fast cell and slow cell: 
      - load in Digital circuit is generally capacitance
      - We can say to charge capacitance fast , we need more current i.e. wider transistor. Hence, Less delay but more will be power ,area and vise versa.
 


## Part 4:Labs using Yosys and Sky130 PDKs
### Sub-part 1:Introduction to yosys Synthesis tool
   - In this part, yosys tool was learnt and the step by step synthesis was done.
      - Invoke the yosys tool
           
![intro to yosys lab (step 1 invoke the yosys)](https://user-images.githubusercontent.com/92054999/165781146-d80d90d8-b9fb-459a-bc7b-a0f71f1cc685.PNG)
   - Reading the library file sky130 by the read_liberty -lib  library path and reading the Verilog module by read_verilog file name
   



![yoysy lab step ii](https://user-images.githubusercontent.com/92054999/166057446-01ea4174-d53b-420e-8e9e-e179a06c6350.PNG)

   - The module to be synthesized given by synth -top module_name
   
   
   ![yosys lab step iii synthesizing](https://user-images.githubusercontent.com/92054999/166057865-f699cb75-f5e4-4641-ba6d-02671c8601ad.PNG)
   - The cell of the module is mapped with the library and sky130 netlist is generated.
    

![yosys show with sky technology](https://user-images.githubusercontent.com/92054999/166058182-3380c029-de31-4e66-8f3e-93dc61583916.PNG)

# Day 2 : Timing Libs,hirarchical vs flat synthesis and efficient flop coding styles

On the second day , we focussed on the library sky130 and the different types of synthesis. Moreover, we analysed different types synchronous and asynchronous set /reset pin on the basis on timing diagram .
## Part 1:Introduction to Timing libs
   - The library we used here was sky130_fd_sc__hd_tt_025C_1v80.lib,the library is basically defined on 3 parameters which process corner,voltage and temperature.
     Here process is typical(tt), temperature is 25 and the voltage is 1.8 v. According to different places,these values changes,which is taken care of while defining      library.
     
    
![intro to  lib (lab 4 part 1)](https://user-images.githubusercontent.com/92054999/166062808-0669d5bf-72f3-4989-88cb-ccfbbe5a4530.PNG)
  - The main details i.e. technology, delay model, operation mode of the library used is given below in the figure.
  
![intrro to  lib(lab 4 part 2)](https://user-images.githubusercontent.com/92054999/166063074-d79f74a7-7ef3-42d3-84f3-63235e00d0da.PNG)
  - In this Library, we can have several cell with different specification i.e. they can differ  by leakage power or area.
 
![lab4_part3](https://user-images.githubusercontent.com/92054999/166063521-c9508f49-1e17-44b5-b96b-11d1b3885dc2.PNG)
 ## Part 2:hierarchical vs flat synthesis
 ### Sub-part 1:Hierarchical synthesis
   - Hierarchical synthesis is the synthesis which is used to synthesis in step by step method.In the given below module, we have two sub module first one is linked to second one in the hierarchical manner.
   ![hier definition](https://user-images.githubusercontent.com/92054999/166065622-7c07b004-cd70-47ee-8ad1-c320dc9f5172.PNG)

  - The netlist of the hierarchical synthesis is given below:
  ![net list generated for hierarchical](https://user-images.githubusercontent.com/92054999/166065758-8ab2812a-857a-43ff-9e13-8ccf27fb2997.PNG)
 ### Sub-part 2:Flat synthesis
   - In this type, the circuit is broken into different types of gate independent of the hierarchichal manner in which they are defined.
    

![flat synthesis diagram](https://user-images.githubusercontent.com/92054999/166066145-1285ab58-0982-4f12-a165-1f1df6d72131.PNG)
### Sub-part 3:Sub module synthesis
   - In the type, We synthesis the particular sub module.Supppose,the synthesized sub module is repeated multiple times.So, to save time and power, we go for synthesizing any one of them.
    
![submodule result with pic](https://user-images.githubusercontent.com/92054999/166066838-4203fcfa-e1d3-443a-a322-901277bfbe7b.PNG)
 # Part 3:Flop Coding styles and optmization
 ### Sub-part 1:Introduction to flop
   - In this part, we will focus on the existance of the flop and It's Importance.
   - In  combination circuit , there are several gates and each gate has their own propagation delay which results into glitch.
   - To remove this glitch , we place flop in middle of the combinational circuit, which to sensitive only at the edges and this prevent from the glitches.
   - However, Input d must be Initialised with some value. So, to Intialze the value, we have set/reset pins.
 
### Sub-part 2:Coding style
  - In this part , we have done about synchronous(set/reset pin) ,asynchronous(set/reset pin) and mixture of the both.
  - Asynchronous(set/reset pin), which will be working independent of the clock or It not synchronised with clock.i.e always@(posedge clk or posedge set).
      - Taking example of asynchronous set, both the synchronous set pin and the clock will work Independently in this case.
                  ![pic 2 gtk wave asyn_set](https://user-images.githubusercontent.com/92054999/166069976-d392d6dc-b58a-40e7-9f87-dad1e83e9af0.PNG)
  - We have mapped with the sky130 technology and found the result of the  asynchronous set.
                  ![synthesis(asynchr_set)-2 sky pic](https://user-images.githubusercontent.com/92054999/166070315-e8f4d2f6-7a9f-44f5-a82f-372c3a391e0d.PNG)
  - Synchronous(set/reset pin), which will be working in synchronisation with the clock e.g always@(posedge clk)
      - We have analysed the working of the synchronous reset by studying the gtkwave wave behavior.
                  ![pic 3 synnc rest gtk wave](https://user-images.githubusercontent.com/92054999/166070841-dae0194f-950a-488e-b7c1-10e526e8443f.PNG)
  - We have mapped synchronous reset with sky 130 technology,which is shown below:
                  ![synthesis(synchro_reset)2-skypic](https://user-images.githubusercontent.com/92054999/166071011-3a3d8f85-88b0-4aaf-814f-06e8b3ece57f.PNG)
### Sub-part 3:Optimization Technique
  - Optimization means simplification of any module. We have taken two special cases here to explain optimization
  - Verilog code:
  ```
   module mul2(input [2:0]a,output [3:0]y);
   assign y=a*2;
   endmodule
   ```
  - The above code is basically a multiplier but we don't need any extra harware to design this.
                  ![synthesis  result -no hardware needed-1](https://user-images.githubusercontent.com/92054999/166072720-eb332627-897d-4d62-9096-64847433fff4.PNG)
                  
  - We have mapped with the sky130 Technology and verified that there s no need of extra hardware.
                  ![synthesis mul2p sky pic 2](https://user-images.githubusercontent.com/92054999/166072949-97fe529f-2675-430b-8b35-08e288e6a8b3.PNG)

  - Verilog code:
   ``` 
  module mul8(input [2:0]a,output [5:0]y;
  assign y=a*9;
  endmodule
  ```
  - Likewise, here we don't need any extra hardware which is verified by simulation as well as synthesis.
                   ![synthesis report of a 2 nd code(p1)](https://user-images.githubusercontent.com/92054999/166073528-6676f12d-045b-4afa-ad8f-f8cad0209be6.PNG)
                   
# Day 3: Combinational and Sequential optimization
  - On the third day, we learnt about simplifying different types of circuit, be it combination or sequential circuit.In other words, optimization means to simplify the equation, so that area or power is saved.
## Part 1:Introduction to Optimization
  -  Optimization is an interesting area to explore with to respect to combinational and sequential circuit.In this part, we have explored steps to simplify the circuit functional design.     
## Part 2:Combinational Optimization 

  - The process of squezzung the logic to get the most optmised design so that area or power can be reduced.There are several method to do so like constant propagation, Direct propagation and boolean logic optimization.The simulation will clearly explain the combinational optimization.
  - Verilog code:The Mux code is converted into and gate which is verified by the synthesis report.
```
module(input a, input b, output y);
assign y= a?b:0;
endmodule
``` 
![opt_check synthesis,sky pic 1](https://user-images.githubusercontent.com/92054999/166160538-3847c0ab-569c-4b99-8297-629f00bbbf3b.PNG)

## part 3:Sequential Optimization
  - In this part, We have used sequential constant propagation technique to reduce the functionality of the circuit i.e. making the output constant.
  - In the code, we started with mux with input 1'b1 and In the synthesis report there is constant assigned to the output.So, this circuit is optimized.
![codenew 1](https://user-images.githubusercontent.com/92054999/166160910-00c83000-e970-4f79-8654-57fdee01229f.PNG)
![dff_const2 gtkwave](https://user-images.githubusercontent.com/92054999/166160941-af70ef33-14f6-4935-bc44-c0f868da5b24.PNG)
![dff_2-sequential optimisation ,no flip flop ,code+sky pic](https://user-images.githubusercontent.com/92054999/166160953-75984286-6f34-4f53-9601-10e50ff20bb3.PNG)

### Sub-part1:Sequential optimisation unused outputs
  - In this part,Unnecessory pins of the design were removed in the synthesis report,which is beneficial for the circuit.
  -  In the example below, we have taken 3 flip flop example but after synthesis It is reduced to 1 flip flop as 2 pins were not used in the circuit.
 
![code new](https://user-images.githubusercontent.com/92054999/166161691-6ea2f5b9-9c58-4809-bfff-9cf6ac066279.PNG)
![analysis of code-showing 1 ff as 3 ff](https://user-images.githubusercontent.com/92054999/166161697-e81a282c-067c-4699-a1d9-65bdb36581fd.PNG)
![skypic of unused count](https://user-images.githubusercontent.com/92054999/166161700-50b488c2-0708-450d-b1b7-2e4ad024b388.PNG)

# Day 4:GLS,Synthesis simulation Mismatch and Blocking/Non blocking statement
  - On this day, we learnt about Importance of Gate level simulation, blocking /non blocking statements and caveats related to it. At last, we analyzed the reason to simulation synthesis mismatch.
##  Part 1:GLS Concepts And Flow Using Iverilog
  - Gate level simulation  is used to verify the logical correctness of design after synthesis as well as ensuring thw  timing of the design.
  - For  checking the timing, GLS needs to be run with delay annotation.
  - for this GLS, we need netlist,testbench and the cell library to the iverilog(simulator tool),we can verify in the gtkwave window.
## Part 2:Blocking And Non Blocking Statements
  - In blocking statements ('='), It executes the statement in the order It is written i.e. one by one evaluation is done where as in Non blocking('<='),It executes all the RHS when always block is entered and assigned to LHS i.e. parallel evaluation.
## Part 3:Synthesis Simulation Mismatch
  - In this part, we have analyzed about the mismatch of iverilog simulation and synthesis of gate level simulation, as both differ in some special case due missing of sensitivity list or caveats with blocking/non-blocking statement.
### Sub-part 1:Missing of sensitivity list
  - In this we have observed how the senstivity list impact the output and as a result simulation synthesis mismatch occur.
  - The verilog code is having always@(sel) i.e. output will change only when sel line changed, This results into faulty output.To elimiante this , we should go for always@(*) ,this will take care of the all the input present in the circuit.
  
 ```
module mux(input i0, input i1, input sel,output reg y)

always@(sel)
begin
  if(sel)
    y=i1;
  else
    y=i0;
end
endmodule
```
The correct way of writing the code is:

```
module mux(input i0, input i1, input sel,output reg y)

always@(*)
begin
  if(sel)
    y=i1;
  else
    y=i0;
end
endmodule

```
![gtkwave for bad_mux v](https://user-images.githubusercontent.com/92054999/166163338-72626061-1d67-401b-b8c9-06db500660f7.PNG)
![synthesis for gls in gtkwave](https://user-images.githubusercontent.com/92054999/166163344-f177d08b-dc3d-42ae-bfb2-b342e76abe41.PNG)
  - The simulation and synthesis results differ due to mismatch in sensitivity list.

### Sub-part 2:Blocking Statement & non-blocking statement
  - This can be one of the reason for synthesis simulation mismatch, as using blocking statement in always block is dangerous to use or you have to take more care.
    The simulation and synthesis results clearly shows the mismatch.
  - The verilog code for the caveats with blocking is given below:
```
module blocking_caveat(input a,input b, input c,output reg d);
reg x;
always @(*)
begin
d=x&c;
x=a|b;
end
endmodule
  
```
![error in gtk wave ,taking old value,blocking issue](https://user-images.githubusercontent.com/92054999/166163570-dee3fc13-b314-48fb-adb0-0db07ed10e54.PNG)

![gls output of theory 1,which corrct](https://user-images.githubusercontent.com/92054999/166163575-a8410e99-8a84-4e48-9eae-0794f4c1678d.PNG)
# Day 5: IF,case,for and generate for
  -On this day, we have focused on the fundamental principal of if,case,for loop,generate for and their structure.If Incomplete structure ,It would lead to Inferred Latches.
## Part 1:If and case construct]
###Sub-part 1:IF construct
  -In this part, we have analyzed the structure of if statement and it's application.
 This is a general if else construct,

```
if(condtion1)
 -----
elseif(condition2)
 -----
else
 -----
```
  - In the given below verilog code, there is incomplete if ,which will result into inferred latch.
  - When i0=1, the output will follow i1 but when i0=0, output will give previous value.
![code for incomp_if](https://user-images.githubusercontent.com/92054999/166165166-a3e3c4eb-255a-4338-8a63-2a6a9929d14a.PNG)
![incomplete if gtk](https://user-images.githubusercontent.com/92054999/166165169-08ebf0c0-5a36-44e6-ace5-6efa97cb60a5.PNG)

### Sub-part 2:Case construct
  -In this part, structure of case were analyzed and simulation were studied.
This is a general if else construct,
```
module();
input a,b;
output d;
always@(*)
begin
case(a,b)
----
---
endcase
end
endmodule
```
  - In the given below verilog code. there is incomplete case statement used i.e 10 or 11 case is not used,which will lead to inferred latch.
  - To eliminate this latch, we must use default statement in the case.
![code](https://user-images.githubusercontent.com/92054999/166165309-c54f4737-ef3b-4af1-9f3c-16c0149e74f7.PNG)
![simulation- when sel 1  is 1, out is latched](https://user-images.githubusercontent.com/92054999/166165311-e183633e-c7e2-4e0b-9c34-b56684707ae6.PNG)


## Part 2:for loop and generate for
### Sub-part 1:for loop
  - For loop is mainly used for evaluating the expression multiple times.For ex: suitable fordesigning  16:1 mux,32:1 mux.
  - For loop is used inside always block.
  -  The Verilog code and simulation is shown below:
![code](https://user-images.githubusercontent.com/92054999/166191580-d82bba7e-a203-4ae7-8ff6-952813765502.PNG)
![gtkwave for this code](https://user-images.githubusercontent.com/92054999/166191669-548f2c85-108f-4a0b-aee3-c5200c0b7bd4.PNG)

### Sub-part 2:generate for
  - Generate for loop is used to Instatiate the block.
  - It can't be used inside always block.
  - In the verilog code shown below, We have taken the example of ripple carry adder.
 


![code new](https://user-images.githubusercontent.com/92054999/166196035-a96b09f7-f58d-4469-bedb-b1650622975d.PNG)

![simulation of multiple file](https://user-images.githubusercontent.com/92054999/166196050-a160de30-ebfe-4302-b37b-bd54b85e43c4.PNG)

![simulation](https://user-images.githubusercontent.com/92054999/166196068-c7f14bcf-d7e6-4b5d-b961-a09cc6d6dee5.PNG)


# References
- [https://github.com/The-OpenROAD-Project/OpenLane](https://github.com/The-OpenROAD-Project/OpenLane)
- https://github.com/VrushabhDamle/sky130AdvancedPhysicalDesignWorkshop
