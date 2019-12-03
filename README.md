# Flood-gate for naked mole rats

The project describes the flood-gate for installation into the colony of naked mole rats or other small animals.

![Grayscale image of the flood-gate in an assembly](https://github.com/comcon1/nmr-flood-gate/flood-gate-drafts/3d/grayscale_details/shluz_1.9.19.1.jpg)

Flood-gate includes two doors with solenoid locks. There are four lines of IR beam interrupt detectors: one before every door and one after every door. 
Before the door, we have two beams perpendicular to each other and commutated with 'OR' logic. After the door, we have a single ray from up to bottom.

Beams are designed as four boards connected with wires located around the central tube: two beam receiver boards and, correspondingly, two beam transmitter boards.

# Project structure

Into the `flood-gate-3d`, we put 3D drafts of the general structure of the flood-gate.

2D drafts suitable for laser cut or CNC milling are located in `flood-gate-2d`.

The KICAD project for receiver and transmitter boards is in `emitter-reciever`.
