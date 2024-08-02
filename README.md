# Inverts-and-Soil-Carbon-in-Hogacre-Ecopark
NOTES ON REPOSITORY ------------
This repository is for the purposes of making my code and data available to all and make my work transparent. To run the code for yourself, you will need to download it and the data and set the directories yourself.
The code itself, made in R version 4.3.2, is in the 'src' folder. It utilises packages 'car' (version 3.1-2), 'tidyverse' (version 2.0.0), 'vegan' (version 2.6-4), 'writexl' (version 1.5.0)

NOTES ON STUDY -----------------
This code and data is associated with my Mbiol project with the University of Oxford in the academic year of 2023-24. For more information the context, goals, methods and results of this study, see my dissertation 'Difference in invertebrate biodiversity and soil carbon between small-scale habitats in Hogacre Common Ecopark, Oxford'.

NOTES ON DATA ------------------
In 'pitfalls.csv', 'Block' refers to the habitat section (otherwise referred to as 'plot') of the trap, while 'plot' refers to the specific trap i.e. Hogacre Woodland North (JHWN).
The 'J' in the 'Block' column entries refers to July, the month of data collection. This is an artefact of cancelled plans for a second round of sampling in October.
The column '9046' is an artefact of a previous version of this table from which I adapted. It does nothing.

The soil datasets, created later, don't have the 'J'. 'soilcarb.csv' combines 'Block' and 'Plot' into 'Soil ID' which contains the site, habitat and specific trap i.e. Hogacre Woodland North (HWN).

1st letter:
H = Hogacre Common
P = Pembroke Sports Ground

2nd letter:
W = Young Woodland
B = Birches
H = Hazel Coppice
G = Neglected Grassland
M = Meadow
O = Orchard
N = Pembroke North Corner
S = Pembroke South Corner
E = Pembroke East Corner
W = Pembroke West Corner

3rd letter:
N = North Trap
S = South Trap
E = East Trap
W = West Trap
C = Central Trap

In 'soilmass.csv', the 'Plot' column repeats the site letter from the 'Site' column.
'Total Wet Weight' refers to the combined mass of the wet soil sample and the tray it's weighed in.
'Total Dry Weight' refers to the combined mass of the dried soil sample and the tray it's weighed in. A soil sample is in the same tray for this measurement as when wet, so the tray's mass can be subtracted in both cases, assumed to have not changed during the drying process.
'<2mm tare' refers to the small plastic bag the <2mm soil fraction is placed in, weighed before it is filled with the sample.
'<2mm total' refers to the combined mass of the plastic bag and the soil fraction.
'Analysis mass' refers to the small amount of <2mm soil fraction placed in a crucible for the CNS analyser.

NOTES ON THE CODE -----------------------
Set the working directory before running the code.
On page 582 of the code, you must un-hash the line and set the directory to output the .xlsx file.
The code does not output pngs of the graphs automatically, these were produced manually using the export button.
The code contains inefficiencies - these are a result of my inexperience.
