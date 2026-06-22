# Mixer

A Mixer made in TIA Portal v19 on S7-1200 PLC Controller.

<br><br>



## Project image
<br><br>
<img width="878" height="655" alt="image" src="https://github.com/user-attachments/assets/eab0a1b3-5c95-4d3e-81ff-221be30af6b5" />
<br>

## Ladder Diagram

<img width="924" height="699" alt="image" src="https://github.com/user-attachments/assets/f26fc5b8-b3df-43dc-bfcb-ad9f7063439c" />
<br><br>
Available also as a <a href="https://github.com/pacarti/Mixer/blob/main/Mixer.pdf">PDF</a>

## Functionality Description

Pumps <b>PUMP_1</b> and <b>PUMP_2</b> are being used to transfer 2 separate liquids into the tank.<br><br>
When the liquid reaches the low level which is triggered by the <b>L_LEVEL</b> switch, the pumps are being activated. They are active until the liquid reaches the <b>H_LEVEL</b>(another switch).<br><br>
Once the liquid reaches the high level(H_LEVEL), pumps are being switch off. Then, as visible in Network 2, the <b>Mixer</b> is being activated for 7 seconds.<br><br>
After that, <b>VALVE</b> is being activated in order to drain the mixed liquid from the tank.


