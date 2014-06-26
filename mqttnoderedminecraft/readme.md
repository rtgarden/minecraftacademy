
<h2>Play Minecraft via MQTT and Node-RED</h2>


http://logic.sysbiol.cam.ac.uk/?p=1499

How-to

    Install Minecraft and the Python API on the Raspberry Pi as described on Craig’s blog.

    Install Node-RED as described on the Hardware Hacks blog.

    Install mosquitto and mosquitto clients (i.e. mosquitto_pub) via sudo apt-get install mosquitto mosquitto-clients

    Install Eclipse Paho MQTT libraries for Python via sudo pip install paho-mqtt 

    Test if Minecraft, Node-RED, mosquitto et al. work.

    Assuming you have Node-RED running as a service (here’s a hint on how to have this at startup), you also want to start up the mosquitto broker by issuing mosquitto -p 1884 (a port of your choosing).

Basic working understanding of using mqtt with node red using a minecraft exercise.

An example exercise: build a pillar 5 blocks high. first build it in sand, next build it in stone.

Another great example is to build a bridge underneath your avatar that self-bilds out ahead of you as 

long as there is no obstruction. A bridge 4 wide can support a railway as well as protective gates and doors.
