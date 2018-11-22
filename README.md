# Honeypot-Week-9
Setup a honeypot and intercept some attempted attacks in the wild.

Time spent: 15 hours spent in total

> Objective: Configuring a basic honeypot and demonstrate its effectiveness at detecting and/or collecting data about an attack.

* Milestone 0: To the Cloud!

Google Cloud Platform was used.

* Milestone 1: Create MHN Admin VM

A MHN Admin VM was created via Google Cloud Platform.

* Milestone 2: Install the MHN Admin Application

After having established SSH access the MHN Admin VM, instructions were provided to install the MHN Admin Application.
This part consumed a lot time due to github link. A new link was provided in order to replace the given link.

* Milestone 3: Create a MHN Honeypot VM

Mhn-honeypot-1 was created (Dionaea over HTTP). This honeypot was used to trap malware samples.

* Milestone 4: Install the Honeypot Application

Honeypot application was install into the VM and wire it to connect back to the admin server.

* Milestone 5: Attack!

An attack to the honeypot is made to make sure it is all working.
Nmap is used and pass it the IP of the honeypot VM

Nmap Installation:

$sudo apt-get install nmap

<img src="https://github.com/gvero89/Honeypot-Week-9/blob/master/nmap%20honeypot1.JPG" width=600>

# Attacks
Honeypot Intercepted my attacks

<img src="https://github.com/gvero89/Honeypot-Week-9/blob/master/honeypot1attacked.JPG" width=600>

# Summary

Honeyplots deployed: 2 Dionaea (Honeypot-1 & Honeypot-3) and 1 Suricata (Honeypot-Suricata)

<img src="https://github.com/gvero89/Honeypot-Week-9/blob/master/sensors.JPG" width=600>

After learning how to create the first Honeypot-1 it was easy to create the other two honeypots.
The first issue that I encounter was the GitHub link for Milestone 2. In order to complete this Milestone, guidance from the TA and advice from other students was needed. 



