# ClusterFinder

#A quick, visual way to spot clusters in Gaia DR2 data, using
distance, proper motion, and error cuts!

#Instructions: Get Gaia DR2 Vizier data by querying Gaia DR2, typing in some object or coordiantes, picking a search radius (I like 2 deg), deselecting all parameters, selecting Plx, e_Plx, pmRA, e_pmRA, pmDE, e_pmDE, Gmag, e_Gmag, BPmag, e_BPmag, RPmag, e_RPmag, RV, and e_RV, and outputting unlimited values as tab separated values file type. If you know the approximate distance range to your target range, you are encouraged to enter a rough, somewhat generous parallax range into Vizier, as this will greatly cut down on the perhaps irrelevant targets and make the data file way more manageable. The .tsv file should show up in your downloads folder (specify path in Setup below). Place Padova isochrones files PadovaGaiaDR2Isochrones.dat in data folder (also specify path in Setup below). Trim the file with viztrim function. Explore distance, proper motion, and error cuts with plotcut function until you see a bunch of stars of one color in distance, proper motion in RA, and proper motion in Dec. Produce a data file and final plot with finalcut function. Plot Gaia DR2 BP-RP color-magnitude diagram of the stars. Note that dim scattered points near bottom are probably garbage. Happy hunting!

#If you use this code and find it helpful, please cite Yep & White 2020, in prep.
