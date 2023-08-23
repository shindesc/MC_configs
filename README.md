# MuCol
Various code I wrote for Muon Collider detector studies

config.xml and config_10tev.xml are used to run the digitization in the two different geometries.

The files in trackperf are used to run the analysis on the output of the digitization to make tracking performance plots.

The "time filtered" configurations use a timing cut that adjusts for the TOF of a photon.
The "loose" and "tight" filters use the timing cut and the cluster filter (from TrackPerf repo)
