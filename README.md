# Readme and metadata
Code for the manuscript "Biogeographic variation in reproductive strategy in a range-expanding marine gastropod" in <i>Ecosphere</i>.

# Repository includes:
- R markdown file (.Rmd) of the code used for analyses and data visualization (biogeographic_variation.Rmd)
- R markdown html document of the code and resulting output (biogeographic_variation.html)
- all necessary csv files to run the code in R

# Metadata 
Below is the metadata for the csv files. Each csv contains rows for each observation. The "Population" column is described as follows: <b>CB</b> = Cabrillo Beach; <b>YB</b> = Yerba Buena; <b>RP</b> = Rincon Point; <b>MB</b> = Muir Beach; <b>DB</b> = Dillon Beach; <b>CM</b> = Cape Mendocino.  


### field_embryo_number.csv: <i>number of embryos per capsule for field-collected capsules</i>
  * Column names
    - ID (unique identification code); Population (see above description); Aggregation_ID (number identifying the aggregation a capsule was collected from); Capsule_ID (number identifying the capsule dissected); Capsule_Length (mm); Number_embryos (count data); Embryo_size (mm)

### field_embryo_size.csv: <i>embryo size (mm) for field-collected capsules</i>
  * Column names
    - ID (unique identification code); Population (see above description); Aggregation_ID (number identifying the aggregation a capsule was collected from); Capsule_ID (number identifying the capsule dissected); Capsule_Length (mm); Number_embryos (count data); Embryo_size (mm)

### field_hatchling_number.csv: <i>number of hatchlings per capsule for field-collected capsules</i>
  * Column names
    - ID (unique identification code); Population (see above description); Aggregation_ID (number identifying the aggregation a capsule was collected from); Capsule_ID (number identifying the capsule dissected); Hatchling_number (count data)
   


- field_hatchling_size.csv: <i>hatchling size (mm) for field-collected capsules</i>
- field_nurse_eggs.csv: <i>nurse egg ratios for field-collected capsules</i>
- tank_adult_growth.csv: <i>adult growth rates (mm/day) of snails in laboratory experiment</i>
- tank_development_time.csv: <i>development time (days) for laboratory-reared capsules </i>
- tank_embryo_number.csv: <i>number of embryos per capsule for laboratory-reared capsules </i>
- tank_embryo_size.csv: <i>embryo size (mm) for laboratory-reared capsules </i>
- tank_fecundity.csv: <i>fecundity (number of hatchlings * number of capsules) for laboratory-reared capsules </i>
- tank_hatchling_number.csv: <i>number of hatchlings per capsule for laboratory-reared capsules </i>
- tank_hatchling_size.csv: <i>hatchling size (mm) for laboratory-reared capsules </i>
- tank_nurse_eggs.csv: <i>nurse egg ratios for laboratory-reared capsules </i>

