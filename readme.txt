

Kobi's macropad
v2.3





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
2x sk6812 leds 
1x Seeed Studio XIAO RP2040
1x 3d printed case 
solder
soldering iron 

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
