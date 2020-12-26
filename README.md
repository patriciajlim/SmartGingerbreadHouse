# Smart Gingerbread House
A Raspberry Pi and Arduino powered gingerbread house that is controlled directly from any web browser. Features include christmas lights, interior lights, doors, and music all controlled from the web. 

##How it works

I created a webpage with HTML, CSS, and Javascript that is hosted on a python Flask server behind Apache HTTP web server. AJAX requests in the Javascript are sent when each button is pressed to control different parts of the gingerbread house's hardware. The Flask app receives these AJAX requests and executes a function based on the button that is pressed. 

##Hardware

The house is powered by a Raspberry Pi, which hosts the Flask/Apache server on the Raspberry Pi's IP address, and Arduino which then controls all of the hardware. Christmas lights were soldered together with LEDs, resistors, and wires, while the door is controlled by a servo motor. Music is played by a piezo buzzer which uses frequencies to produce tones of music notes. 
