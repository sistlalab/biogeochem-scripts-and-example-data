All example data in: 'biogeochem_example.xlsx'
Format your data exactly this way or the scripts will not run! 

For lab set up, basic soil processing you must have been completed.

**Metadata file**: note of project objectives, sample layout, depth and width samples, number of samples, labeling scheme, timing, personnel, how samples were processed and where archived.
All (soil) samples need at a minimum:
 * number of replicates per treatment, pseudoreplicates if applicable (i.e., pseudoreplicates for SIR-biomass, respiration, extractable nutrients)
 * total collected fresh weight (g) per sample
 * sample depth and width, or area if sampling surface plant biomass
 * gravimetric soil moisture on subsample of each sample
 * pH on subsample of each sample
 * whether sieved or not and sieving protocol
 * What downstream analyses are done/to be done (e.g., extractable nutrients, pH, gravmiteric soil moisture, enzyme assays, DNA extractions, respiration, microbial biomass, percent C/N, etc.)

After running standard curves, always check to see R^2 are high >> 0.97  (i.e., for respiration, SIR-biomass, POXC, inorganic nutrients, enzyme assays). When you have analyzed your data, confirm the analyses are within reasonable ranges from other similar data sets:
https://cpslo-my.sharepoint.com/:p:/g/personal/ssistla_calpoly_edu/Ef9cJ9DEl1NKn6Xam74VtzsBNvZXCMU6VGIyMzJBMXC3Tw?e=hF7mNZ



# respiration/microbial biomass C, mason jar incubations
incubation and field respiration flux code

This folder contains R scripts for calculation incubation and field CO2 flux, (ugCO2-C/ g soil*time) as well as soil microbial biomass from substrate induced respiration (ug C/ g soil)

To run this code, you must always:
1) have recorded soil fresh weight (g) for your incubations and dry weight/fresh weight (gravimetric soil moisture) of a subsample
2) have at least three time points in yor incubations, run pseudoreplicates (duplicates of sample) incubations, had a  negative control
3)  make sure you data sheet is formatted exactly as show in 'biogoechem_example.xlsx'
4) check to see your values are in line with realistic data from the field! 


# permanganate oxidizable carbon (POXC) -  fraction of the SOM pool that is oxidizable in the presence of potassium permanganate in solution. (https://lter.kbs.msu.edu/protocols/133)

To run this code, you must always follow protocol and have:
1)  recorded soil air weight in kg that was used in the POXC reaction
2)  run a standard curve (see example of standard POXC curve here: https://cpslo-my.sharepoint.com/:p:/g/personal/ssistla_calpoly_edu/EYifgo2Y48hNnkb9PsXT4hwBmQSNKMfBewx2RHiS9WJF3w?e=Nq5aAu)
3)  recorded the tecan absorbance data at 550 nm
 4) check to see your values are in line with realistic data from the field! 
