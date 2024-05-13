#  ANALOG DESIGN OF INVERTER, NOR AND NAND GATE USING VIRTUOSO

**AIM:**<br>

&emsp;&emsp;To design the following circuits using Cadence Virtuoso<br>

&emsp;&emsp;&emsp;&emsp;&emsp;1) Inverter<br>
&emsp;&emsp;&emsp;&emsp;&emsp;2) 2 Input NAND gate<br>
&emsp;&emsp;&emsp;&emsp;&emsp;3) 2 Input NOR gate<br>

**SOFTWARE REQUIRED:**<br>

&emsp;&emsp;Cadence Virtuoso<br>
  
**PROCEDURE:**<br>

STEP:1 Open MobaXterm<br>
STEP:2 Click on session(top left corner)<br>
STEP:3 Choose remote host and in the host name type "student@cadence.saveetha.in" then enter password.<br>
STEP:4 Type "xdg-open .", A new window will be opened.<br>
STEP:5 Create a new file and within the folder right click and click "open in terminal".<br>
STEP:6 The in the terminal type the following commands<br>
&emsp;&emsp;&emsp;&emsp;-> pwd<br>
&emsp;&emsp;&emsp;&emsp;-> tcsh<br>
&emsp;&emsp;&emsp;&emsp;-> source /cadence/install/cshrc<br>
&emsp;&emsp;&emsp;&emsp;-> virtuoso<br>
STEP:7 Then Analog design window will be opened<br>
STEP:8 In that window click file->new->library then,<br>
&emsp;&emsp;&emsp;&emsp;>>Give library name then choose "attach to an existing technology library"<br>
&emsp;&emsp;&emsp;&emsp;>>Choose the folder where you need to work<br>
&emsp;&emsp;&emsp;&emsp;>>Then click gpdk045 library and click ok<br>
STEP:9 Again in the analog design window click file->cell view->choose library->"type cell name".<br>
STEP:10 Schematic window will be opened<br>
STEP:11 Design the gates and simulate it and verify its output with its respective truth table<br>

**INVERTER:**

![Screenshot 2024-04-27 114426](https://github.com/TharunPR/VLSI-LAB-EXP-6/assets/117915125/2cc93bc3-6ac9-4963-b808-340a07633abc)

**OUTPUT:**

![Screenshot 2024-04-27 113848](https://github.com/TharunPR/VLSI-LAB-EXP-6/assets/117915125/2d2778e4-1e57-4b86-89ec-60fdc1c773da)

**2 INPUT NAND:**

![nand_2ip Screenshot 2024-05-07 151323](https://github.com/TharunPR/VLSI-LAB-EXP-6/assets/117915125/4214e3b5-bb14-4d93-8a81-f64039bd8279)

**OUTPUT:**

![nand_2ip Screenshot 2024-05-07 152513](https://github.com/TharunPR/VLSI-LAB-EXP-6/assets/117915125/0ccc1a38-8d99-4556-97f9-fdfe4c387f65)

**2 INPUT NOR:**

![nor_2ip Screenshot 2024-05-07 152808](https://github.com/TharunPR/VLSI-LAB-EXP-6/assets/117915125/765b5632-dc94-4581-b370-922518f454c6)

**OUTPUT:**

![nor_2ip Screenshot 2024-05-07 143309](https://github.com/TharunPR/VLSI-LAB-EXP-6/assets/117915125/bed65e81-a0aa-4058-93cd-d8cad426e384)

**RESULT:**<br>

&emsp;&emsp;Thus the analog design of inverter, nand and nor gates is done and the outputs are verified successfully.



