# Module 3

## Learning Goals

<a id="lg1"></a>
### LG1

Explain what an overlay network is and when it beats a port forward: changing WAN addresses, campus firewalls, CGNAT/DS-Lite, hole punching. (The NAT variants are optional depth; know the shape of the problem.)

**Evidence:** [Task 4](#task-4) [Task 5](#task-5)

<a id="lg2"></a>
### LG2

Deploy a Nebula node from a bundle on the router, and explain what the CA, the certificate, the key, and the config each do.

**Evidence:** [Task 1](#task-1) 

<a id="lg3"></a>
### LG3

Draw a network architecture involving an overlay network and explain the network and the roles in the mesh (nodes, certificate, peer, lighthouse).

**Evidence:** [Task 4](#task-4) 

<a id="lg4"></a>
### LG4

Make the router the pod's gateway into the overlay, reach your Node-RED instance on the Optiplex cluster through the overlay, and move one MQTT message each way.

**Evidence:** [Task 2](#task-2) 

## Tasks

<a id="task-1"></a>
### Task 1 — Connect your router to the overlay

Some step-by-step-screenshots from Sven:  
[Sven's module 3](https://github.com/Svenjjamin/net-iot-hsbi-2026-portfolio/blob/main/Module03/ReadME.md)
![lighthousepan_from_LAN](./pictures/lighthouseping.png)

**Proves:** [LG2](#lg2)


<a id="task-2"></a>
### Task 2 — Reach Node-RED and move one message

![nodeRED](./pictures/nodered.png)  
![sketch](./pictures/sketch.png)  

**Proves:** [LG4](#lg4)


<a id="task-4"></a>
### Task 4 — Draw the networks and name the layers

[Sven has documented this](https://github.com/Svenjjamin/net-iot-hsbi-2026-portfolio/blob/main/Module03/ReadME.md)

**Proves:** [LG1](#lg1)[LG3](#lg3)


<a id="task-5"></a>
### Task 5 — Measure it

[Sven has documented this](https://github.com/Svenjjamin/net-iot-hsbi-2026-portfolio/blob/main/Module03/ReadME.md)

**Proves:** [LG1](#lg1)


<a id="task-6"></a>
### Task 6 — The router as a node

![mqtt_on_router_sven](https://github.com/Svenjjamin/net-iot-hsbi-2026-portfolio/blob/main/Module03/pictures/Round6.png)  
![mqtt_on_router](./pictures/mqtt_on_router.png)  

**Proves:** [LG4](#lg4)

## Reflection 3

[Reflection 3](../Reflections/ref03.md)