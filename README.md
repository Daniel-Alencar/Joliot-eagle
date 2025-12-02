# Avionics Boards for the Joliot Rocket

This repository contains the design files for the avionics boards used in the **Joliot rocket** developed by **Cactus Rockets Design**.

### Description

The avionics system is composed of two main boards:

* **Processing Board**
* **Actuation Board**

The **Processing Board** is responsible for handling sensor data, data logging, and telemetry transmission.
The **Actuation Board** contains the circuitry required for the correct activation of the *Skib* (the recovery deployment mechanism).

*Note:* All board files can be opened using **Autodesk Eagle**.

### Schematics and Layouts

(Insert links or images here.)

### Board Interconnections

(Insert connection diagrams or pin mapping as needed.)

### Operation

The Processing Board includes a system-activation switch. Once the switch is pressed, the system powers on and begins reading all onboard modules. After each reading, the data is stored on a microSD card and transmitted via telemetry.

When the Processing Board detects a fall event, it sends a signal to the Actuation Board, which then activates the *Skib* to deploy the recovery system.


Se quiser, posso melhorar o texto para ficar mais técnico, criar diagramas ASCII para as conexões ou organizar o README em um formato mais sofisticado.
