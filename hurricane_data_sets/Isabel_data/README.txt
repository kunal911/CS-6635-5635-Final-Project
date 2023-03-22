This directory contains 3 folders. raw_data, gz, and bin_data
Each file is named VARfNN.ftype where VAR is the variable name and NN is the time step, and ftype is the file type.

gz: These .gz files are the original source files from https://www.earthsystemgrid.org/dataset/isabeldata/file.html
These files are zipped therefore they have an additional .gz on the end

bin_data: Each file is unzipped into a binary file, however unusable in Paraview

raw_data: Each .bin file is converted into a readable format in Paraview (.raw). All files have a dimension of 500x500x100 except HGTdata.raw which has dimensions 500x500x1

