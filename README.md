# bag_deep_ckt
genetic and neural net optimization for circuit design

NGspice:

NGspice 27 should be installed on the system, this code was developed on a linux machine but also worked on macos.

First thing that needs to be done is to go to eval_engines/NGspice/ngspice_inputs and run:
python correct_inputs.py

This will make all the netlist files point to the correct 45nm model file which is located in eval_engines/NGspice/ngspice_inputs/spice_models/45nm_bulk.txt

make sure in the yaml file, the .cir files are pointing to the correct files.
