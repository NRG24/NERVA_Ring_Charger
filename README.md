# NERVA_Ring_Charger
So this is the charger for the NERVA Ring, I suggest taking a look: https://github.com/NRG24/NERVA_Ring This is a portable, magnetic charging case for the ring using a strategic power path management system. There is a 100mAh battery, which balances size with capacity. There are also magnets perfectly spaced to allow for a snapping mechanism. 
The real magic is actually hidden, however. There is an extremely low profile 4mm magnetic pogo connector on the NERVA Ring's PCB that allows for secure connectivity. It was very difficult to find. 
There is a print-in-place hinge for the box to open and close with 0.25mm tolerances. 
The circuit works by splitting the 5V input voltage (USBC) and having one half charge the onboard 100mAh LiPo. Then, it goes through a boost converter to 4.6 volts which is precisely and strategically under 5V. Because of the two Schottky diode OR-ing system, the 5V (top half) current will take priority and go to charge the 22mAh ring battery. When the case is not plugged in, the boost converter will provide just enough voltage and current to charge the ring battery as well.
<img width="844" height="638" alt="Screenshot 2026-04-29 at 3 23 45 PM" src="https://github.com/user-attachments/assets/598aadce-e9d0-4ca8-82a3-a117d9fc2898" />
<img width="666" height="547" alt="Screenshot 2026-04-29 at 3 45 39 PM" src="https://github.com/user-attachments/assets/2b691734-3728-4e7b-adf8-d8168cd8f7b6" />
<img width="881" height="457" alt="Screenshot 2026-04-29 at 10 37 57 PM" src="https://github.com/user-attachments/assets/f6d3f2f1-946a-4c05-b0f1-92f46f9faf57" />
<img width="576" height="527" alt="Screenshot 2026-04-29 at 10 38 20 PM" src="https://github.com/user-attachments/assets/0690b5b0-6462-4741-9586-c6a9f3aa0489" />

https://github.com/user-attachments/assets/c79a6dce-659e-46af-84e8-e46c985744b7


