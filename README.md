# Cameron Tech Offroad CPU

Here is the Eagle schematic and board layout for the CTAIM1. Software can be found here: https://github.com/camerontech/offroad-cpu

If picking up and assembling all of these parts yourself is a bit daunting, you can purchase a kit or pre-assembled
unit here: http://store.camerontech.io/products/offroad-cpu

![Schematic](http://camerontech.github.io/offroad-cpu-hardware/images/schematic.png)

## Parts

**1 x ATMEGA328P-PU** [Cameron Tech ATMEGA-UNO](http://store.camerontech.io/products/atmega)

**1 x LCD** [SparkFun LCD-00709](https://www.sparkfun.com/products/709)

**1 x Multi-sensor** [Sunkee 10DOF](http://www.amazon.com/Attitude-Indicator-L3G4200D-ADXL345-HMC5883L/dp/B00CD239UG)

**1 x 5v Regulator** [Digikey MC7805CT-BPMS-ND]( http://www.digikey.com/product-search/en?WT.z_header=search_go&lang=en&site=us&keywords=mc7805ct-bpms-nd&x=-1136&y=-51&formaction=on)

**1 x 16MHz Clock Crystal** [Mouser 815-ABL-16-B2](http://www.mouser.com/Search/ProductDetail.aspx?R=ABL-16.000MHZ-B2virtualkey52750000virtualkey815-ABL-16-B2)

**1 x 10kΩ Potentiometer** [Digikey D4AA14-ND](http://www.digikey.com/product-search/en?WT.z_header=search_go&lang=en&site=us&keywords=D4AA14-ND&x=-1136&y=-51&formaction=on)

**2 x 10µF Capacitor** [Digikey P975-ND](http://www.digikey.com/product-search/en/capacitors/aluminum-capacitors/131081?k=p975-ND)

**1 x 0.1F Capacitor** [Digikey 399-4266-ND](http://www.digikey.com/product-search/en?WT.z_header=search_go&lang=en&site=us&keywords=399-4266-ND&x=-1151&y=-51&formaction=on)

**2 x 22pF Capacitor** [Digikey 399-9723-ND](http://www.digikey.com/product-detail/en/C315C220K5G5TA/399-9723-ND/3726119)

**1 x NPN Transistor** [Mouser 512-2N3904BU](http://www.mouser.com/Search/ProductDetail.aspx?R=2N3904BUvirtualkey51210000virtualkey512-2N3904BU)

**1 x 40-pin Straight Header** [SparkFun PRT-00116](https://www.sparkfun.com/products/116)

**1 x 40-pin Right-angle Header** [SparkFun PRT-00553](https://www.sparkfun.com/products/553)

**1 x Three-way switch** [Cameron Tech Three-way Rocker Switch](http://store.camerontech.io/products/three-way-rocker-switch)

That'll get you everything you need to get it working. You'll still need to connect the three-way switch to the board
somehow and get power in. When you buy one of these from Cameron Tech I include a few more parts for easy hookup.

A 4-wire JST connector hooks up the three-way switch to the circuit and also lets you disconnect it:

**1 x 4-pin JST Connector** [SparkFun PRT-09916](https://www.sparkfun.com/products/9916)

You can solder 12v right to your circuit, or use a 9v battery. If you want something less permanent then use a screw
terminal so you can unhook the wires again if necessary:

**1 x 2-pin screw terminal** [SparkFun PRT-08432](https://www.sparkfun.com/products/8432)

**1 x 9v Battery Strap** [Digikey 81-8K-ND](http://www.digikey.com/product-detail/en/81-8/81-8K-ND/303954)

Finally, unless you want to do a lot of wire-routing and excess soldering by hand and manually following the 
schematic to hook everything up, you can also get the circuit board that lays everything out nicely and attaches 
as a backpack to the LCD screen:

**1 x Offroad CPU Circuit Board** [Cameron Tech CTORD100](http://store.camerontech.io/products/offroad-cpu-circuit-board)
