# VIDEO2SCART
<p>this project is about a PCB that connects the Commodore C128 video outputs (RGBi & composite / S-Video) to a SCART display device!
I created this project online on www.easyEDA.com and ordered the PCBs from www.JLCPCB.com and the parts from www.LCSC.com</p> 

<h3>file / directories INFO:</h3>
<p><strong>3DPrint</strong> </br> the STL files and some pictures of the case ... ready for 3D printing</p>
<p><strong>PCB</strong></br> PCB_C128_VIDEO2SCART_JDet_assembling.pdf = PDF for assembling </br> PCB_C128_VIDEO2SCART_JDet_PCB.pdf = the PCB view </br> Gerber_C128_VIDEO2SCART_DET_1_20191116125402.zip = the GERBER Files for ordering the PCB from a PCB manufactorer.</p>
<p><strong>cable_howto</strong></br> read the @cable_info.txt for further information of building the cables. There are also links to reichelt.de ... a electronic store where you can order the cables. look at the pictures ... they are showing the whole building process.</p>
<p>Schematic_C128_VIDEO2SCART_JDet.pdf = the schematic that shows the circuit of all components.</p>
<p>partslist.csv = a list of all components and the part number to order them from LCSC.</p>
<p>Please read the cable assembling INFO PDFs ... coming soon.</p>
<p>special thanks to Peter Grigull for designing the case and sharing the STL files.</p>

<p><strong>switches:</strong></br> SW1 switches between the 80 col. and the 40 col. mode.</br> SW2 switches between video (composite) or s-video signal in the 40 col. mode</p>
<p><strong>jumper function:</strong></br> short left&middle pin - monochrome is syncing the 80 col. mode - that works GOOD.</br> short right&middle pin - NOR generated HSync&VSync signal (generated with the JFET) is syncing the 80 col. mode. I noticed that this function do not work! during testing on the bredboard it went all well ... that is a little bit odd ... but you do not need this, because the monochrome sync works GOOD. SORRY for that ...</p>

<p>cheers ... <strong>JDet</strong></p>
