MITM_image_extraction
=====================

<h2> About </h2>

Bash script implementing a MITM attack with Ettercap & image extraction from intercepted packets with Driftnet. 
Port forwarding setup within script. 

<h2> foreword </h2>

Only tested on the Raspberry Pi "Rasbian" image. Due to the nature of this program continously writing new images, I have formatted the code to write to an external HDD connected to the RPi. 

Execute from the shell as ```. MITM-image-extraction.sh``` to prevent running script in the child shell.

<h2>Dependencies</h2>

ettercap & driftnet. Stricly intended for personal research.
