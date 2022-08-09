//This design has not been validated but in theory the values are all correct and it should work. however I need to verify 
if the dimensions are actually correct in real life when PCB manufacturer produces it for me. up to then I keep this note.

# eurorack_panels
This File is a KiCAD File providing a template for blank Panels fitting the Eurorack Definition from Doepfer.

It consists of
  - The drawings on the CUT layer which is to have the Panel Cut by the PCB manufacturer.
  - The Vias placed on the right spots to fit into the 19" Rack.
  - All dimensions taken into account from this reference: https://doepfer.de/a100_man/a100m_e.htm

HowTo Use:
  1) Open KiCAD project and pcb file of your project in KiCAD
  2) Open pcbfile in PCB editor to have both open simultaneously. 
  3) pick the Group of the panelsize you want (i.e. 10HP) 
  [A group consists of the Panel Frame, the Vias and the description in HPSize, 
  selecting with the mouse from bottom right to top left should select the panel 
  you want and a purple frame appears, indicating the selection you made]
  4) Copy that selection and paste it into your project.
  5) Modify according to your needs (adding "Vias" for Potentiometers or inputs/outputs ....)
  
This template shall just make your life easier to draw front panels with the right sizes and mounting holes
