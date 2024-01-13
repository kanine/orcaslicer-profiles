# About orcaslicer-profiles
This is a repository for my personal Orca Slicer presets for use with the Kobra 2 Plus. I've done some test prints and built this up using built in Orca Slicer 1.9.0 presets. Orac Slicer presets use an additive method where each file builds on it's dependencies so I think this is one of the cleaner ways to do this.

I've checked generated gcode vs output from the official Anycubic Prusaslicer profile and tried to match up as best as I can for now. I do notice some changes in speed / fan settings etc between the two so I expect this will evolve over time.

# Installation
Copy the respository files using which ever method you prefer and copy the contents of the two folders to the Orca Slicer Application Data area.

For example in Windows: %APPDATA%\Roaming\OrcaSlicer\user

# Known Issues
The Anycubic Cloud appears to validate that the uploaded files have been generated from Prusaslicer (and I assume Cura too). So uploading the output to Anycubic Cloud generates an error but testing showed that the generated output from the presets worked from the USB directly.

# Filament
The filament labeled here as Inkstation may go by other names, that's just where I get it in Australia. The box is branded as Tecor, likely quite a generic PLA+ filament.

# Disclaimer
Please use at your own risk, if you have the skills I recommend comparing the generated gcode with that produced using the manufacturers recommended slicers. Particularly start up, shutdown and layer start/end code.