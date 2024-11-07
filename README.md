# CMOS Based NAND Gate
This project simulates the designed NAND Gate circuit to determine its Transient and DC characterisitics.
Note: The Circuit requires further optimization to improve performance. Will Surely upgrade it.

# NAND GATE 
Logic family is a type of method that is used for the implementation of different types of logic gates in the VLSI industry. And logic family is classified into two types that is Bipolar Logic Family and the Unipolar Logic Family. The bipolar logic family is classified into two types Saturated and unsaturated logic family. The unipolar logic family is classified into three types PMOS (P- P-channel Metal Oxide semiconductor), N-MOS (Nchannel Metal Oxide Semiconductor), and CMOS 
(Complementarily Metal Oxide Semiconductor). As we know CMOS consists of both p- p-channel and n-channel MOSFET (Metal Oxide Semiconductor Field Effect Transistor) which are connected in series with each other. For the implementation of NAND Gate using CMOS, we have to connect Both P-MOS in parallel with each other and N-MOS in series with each other. Let us name the first P-MOS as M1, Second PMOS as M2 one N-MOS as M3, and other N-MOS as M4. Vcc1 is the high voltage and GND is taken as Ground. As in this circuit, we are going to analyze 2 input NAND Gate using 180nm technology which is performed in eSim. There are two input A and B which is going into both P-MOS and N-MOS. And output of this proposed NAND Gate is obtained at Yout.

# Paper link: Documentations/Research paper initial.pdf

# Block Diagram of NAND gate
<img width="370" alt="Block Diagram" src="https://github.com/user-attachments/assets/7d12a378-a421-49a9-9d3b-fa4a41beb183">


# Circuit Diagram of NAND Gate
<img width="382" alt="Screenshot 2024-11-07 231416" src="https://github.com/user-attachments/assets/eb93eeae-2992-4725-a0cc-f190050bfecf">

# Transient Plot
<img width="900" alt="Transient Analysis" src="https://github.com/user-attachments/assets/78b57246-25d1-41c5-935d-e35d237c8f04">


# DC Plot
<img width="347" alt="v2dc" src="https://github.com/user-attachments/assets/8994980a-c439-499a-a192-5f41132b34dc">

# Tools used and steps to reproduce all waveforms (Tools allowed are xschem/eSim/ngspice)
Ngspice is an open source mixed-signal circuit simulator.

## Installing Ngspice
For Ubuntu
Open your terminal and type the following to install Ngspice
$ sudo apt-get install -y ngspice

# Running the Simulation
$ ngspice

To simulate a netlist, type:
ngspice 1 ->  source <filename>.cir

You can exit from the Ngspice Shell by typing:
ngspice 1 ->  exit

#Future Work
1. Efficiency can be made in designing using advanced technology.

#Contributors
 Kunal Ghosh
 Sumanto

#Acknowledgement
 Kunal Ghosh, Director, VSD Corp. Pvt. Ltd.

#Contact Information
Kunal Ghosh, Director, VSD Corp. Pvt. Ltd. kunalghosh@gmail.com

   
   














