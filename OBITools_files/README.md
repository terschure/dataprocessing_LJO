# OBITools demultiplexing
The raw data for this project is divided over 2 pools, representing both the mammal and plant amplicons of a subset of samples.
The first steps in the dataprocessing are in parallel for these 2 pools, each needing seperate sample description files for the demultiplexing using OBITools *ngsfilter*:

 - pool1_plants_description.txt
 - pool1_mammals_description.txt
 - pool2_plants_description.txt
 - pool1_mammals_description.txt

The sample names used in these sample descriptions contain the following information:
[sample_number]\_[sample_type]\_[replicate]

- [sample_type] can be 's' for sample, 'pnc' for PRC negative control or 'enc' for extraction negative control
- [replicate] can be '1' to '6' and represent the different PCR replicates used for amplification
