# RSUrecordedData
Neighbor tables and similarity/dissimilarity matrixes recorded by RSU in a simulated vehicular network (VN) 
The VN model was simulated using OMNET++ 5.6.2, Veins 5.2, and SUMO 1.8 on a computer running Ubuntu 20.04 OS.
The simualted maps are Highway, Roundabout, and Traffic Light with high and low traffic flows scenarios for each map.
The RSU is deployed in the middle of the map to record the information sent by the vehicles through BSM messages.
The data are recorded at the end of ten simualtion runs.  
The data are in form of CSV files with comma-separated values.
the files with names start with "Table" hold the RSU neighbor tables, while the ones start with Simi or Diss hold the similarity or the dissimilarity matrixes generated based on the tables.
The files' names also contain the name of the map beside the simulation period in second.
the files' names end with the number of the run.
