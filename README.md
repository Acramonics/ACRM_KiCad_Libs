ACRM_KiCad_Libs
===============

Symbol and Footprint Libraries for KiCad
----------------------------------------

The ACRM libraries provide the following symbols and footprints.

### Symbols

#### Transistors
- 2N5088
- 2N5457
- AC128
- LM2904

#### ICs
- TL022

#### Switches
- SW_Foot_3PDT
- SW_SP5T_NR01105
- SW_SP8T_NR01105

#### Transformers (PCB mounted)
- Transformer_VTX-121-3832-2xx


### Footprints

#### Transistors
- TO-1-3 - TO1 transistor (such as AC128)

#### Switches
- 3PDT_FS - a standard guitar pedal footswitch
- SPDT_SlideSwitch - a small (cheap) slide switch

#### Relays
- Relay_DPDT_20x10 - 20mm x 10mm PCB relays

#### Transformers (PCB mounted)
- Transformer_VTX-121-3832-2xx-35x42 - VTX PCB-mounted transformer

Using the Library
-----------------

First create a path name for the ACRM Library:

1. In the main KiCad window, select `Preferences>Configure Paths`

2. Click the `+` sign and add a path called `KICAD_ACRM_LIBS` and pointing to wherever the `libs` directory is in the unpacked ACRM_KiCad_Libs.

3. Click OK

Next, configure the symbol library:

1. In the main KiCad window, select `Preferences>Manage Symbol Libraries`
2. Click the `+` sign and add a new library:

-`Nickname` = `ACRM`

-`Library Path` = `${KICAD_ACRM_LIBS}/Symbols/ACRM.kicad_sym`

-`Description` = `ACRM Symbols`

Finally, configure the footprints library:

1. In the main KiCad window, select `Preferences>Manage Footprint Libraries`
2. Click the `+` sign and add a new library:

-`Nickname` = `ACRM`

-`Library Path` = `${KICAD_ACRM_LIBS}/ACRMFootprints`

-`Description` = `ACRM Footprints`


