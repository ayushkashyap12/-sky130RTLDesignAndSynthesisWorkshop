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
  - The block Diagram of the Design for the setup  is shown below:

   
  
![yosys setup](https://user-images.githubusercontent.com/92054999/165747782-a0b5eaa3-8067-4c08-9e58-6ef8cd7c814c.PNG)
   - The Verification of the synthesis can be in the following manner:
    

![p2](https://user-images.githubusercontent.com/92054999/165748256-b0711e6b-6fc1-454b-abbd-01c362201558.PNG)


  - The primary input and primary output will remain same between RTL design and Synthesized list-SAME testbench can be used.
  ### Sub-part 2:Introduction to logic synthesis
  
  - Register Transfer Level (RTL) It is the behavioral representation of the required specification. The Figure is shown below, which explains clearly
  

![cap1](https://user-images.githubusercontent.com/92054999/165750996-1a61f10b-457f-4a40-a39c-29d985cc453c.PNG)
 
  - Synthesis is the process of the conversion of RTL to gate level translation
  - The design is converted into gates and the connections are made between the gate and this file is called netlist.
       
![synthesis](https://user-images.githubusercontent.com/92054999/165752623-77f6e455-e25c-44bc-a59a-a08248ef4ec2.PNG)
 
  - .lib file is the collection of the logical modules i.e basic logic gate and,or etc.
  - The gate can be slow or fast depending on the use of the circuit.
    
  -Combination delay in logic path determines the maximun speed of operation of the digital logic circuit.
    ![c2](https://user-images.githubusercontent.com/92054999/165753937-7f5dc88a-719a-41aa-8ebb-1d74ce875373.PNG)
    
   - So, we need cells that work fast to make Tcombinational delay small.So, the setup time is constraint is met.
   - However, We also need cell that work slow to meet the hold time constraint.
   

![c3](https://user-images.githubusercontent.com/92054999/165756668-5618b6ee-0cb2-4101-a7b8-4e139f42bbb0.PNG)

