

Kobi's macropad
v2.3

<img width="1090" height="487" alt="Screenshot 2026-01-28 112529" src="https://github.com/user-attachments/assets/c04c31e1-969a-4b56-afe1-521ebc039741" />


<img width="795" height="431" alt="Screenshot 2026-01-30 180026" src="https://github.com/user-attachments/assets/947091a0-8b93-47c9-abb0-c48cafcc27e2" />
<img width="596" height="415" alt="Screenshot 2026-01-30 175950" src="https://github.com/user-attachments/assets/a8026d04-6b52-474a-b34b-cae64d889281" />



Requirements
Type	Needed
Computer	Windows, macOS, or Linux
Port	USB
Software	 VS Code
 Quick Start

Plug in your board via USB.

Install the IDE for your board.

Select your board in Tools → Board.

Select the correct port in Tools → Port.

Upload a Blink example to test.

If the LED blinks, you’re ready.


How to build

in the folder cad contains the fusion assembly and the top and bottom half of the case.
these should be 3d printed. 
in the folder "pcb" contains the pcb to be printed by e.g. jlcpcb 

components:


4x cherry mx switches

<img width="200" height="200" alt="R" src="https://github.com/user-attachments/assets/de7adcb7-745a-4a7d-9796-d6a4c7d5fb31" />

2x sk6812 leds 

<img width="200" height="200" alt="R" src="https://github.com/user-attachments/assets/8ff499d7-3631-4513-bdf3-fc882170f057" />


1x Seeed Studio XIAO RP2040

<img width="200" height="200" alt="R" src="https://github.com/user-attachments/assets/8433ebeb-967a-4ccd-93d2-bc84190edbc3" />


1x 3d printed case 

<img width="200" height="200" alt="R" src="https://github.com/user-attachments/assets/3e560d01-7625-47da-b23b-22084954b135" />


solder


<img width="200" height="200" alt="R" src="https://github.com/user-attachments/assets/c5762bd3-49ac-40b3-92f1-484a8514b013" />

soldering iron 


<img width="200" height="200" alt="R" src="https://github.com/user-attachments/assets/ae660d88-4264-4732-a73f-712d6099f482" />

once all components are obtained solder on all board components. 
then test to see if there is any issues.
must insure that the top half of the case is on top of the pcb and under the switches (sandwiched between) before soldering switches on to pcb as this is the way to hold the pcb inside the case.
after testing glue the bottom case to the top case. configure code and the macropod will be ready

🔌 Safety

Never exceed board voltage limits

Disconnect power before soldering

Avoid short circuits

🧩 Troubleshooting
Issue	Solution
Board not showing	Try another USB cable
Upload fails	Check board + port selection
Nothing works	Recheck wiring
Random behavior	Loose wires or wrong pin numbers


🤝 Contributing

Have a project, guide, or improvement? Open a pull request.

📄 License

open sorce 
