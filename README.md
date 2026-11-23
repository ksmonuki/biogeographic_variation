# Readme and metadata
Code for the manuscript "Biogeographic variation in reproductive strategy in a range-expanding marine gastropod" in <i>Ecosphere</i>.

# Repository includes:
- R markdown file (.Rmd) of the code used for analyses and data visualization (biogeographic_variation.Rmd)
- R markdown html document of the code and resulting output (biogeographic_variation.html)
- all necessary csv files to run the code in R

# Metadata 
Below is the metadata for the csv files. Each csv contains rows for each unique observation. The "Population" column is described as follows: <b>CB</b> = Cabrillo Beach; <b>YB</b> = Yerba Buena; <b>RP</b> = Rincon Point; <b>MB</b> = Muir Beach; <b>DB</b> = Dillon Beach; <b>CM</b> = Cape Mendocino.  


### field_embryo_number.csv: <i>number of embryos per capsule for field-collected capsules</i>
  * Column names
    - ID (unique identification code); Population (see above description); Aggregation_ID (number identifying the aggregation a capsule was collected from); Capsule_ID (number identifying the capsule dissected); Capsule_Length (mm); Number_embryos (count data); Embryo_size (mm)

### field_embryo_size.csv: <i>embryo size (mm) for field-collected capsules</i>
  * Column names
    - ID (unique identification code); Population (see above description); Aggregation_ID (number identifying the aggregation a capsule was collected from); Capsule_ID (number identifying the capsule dissected); Capsule_Length (mm); Number_embryos (count data); Embryo_size (mm)

### field_hatchling_number.csv: <i>number of hatchlings per capsule for field-collected capsules</i>
  * Column names
    - ID (unique identification code); Population (see above description); Aggregation_ID (number identifying the aggregation a capsule was collected from); Capsule_ID (number identifying the capsule dissected); Hatchling_number (count data)
   
### field_hatchling_size.csv: <i>hatchling size (mm) for field-collected capsules</i>
  * Column names
    - ID (unique identification code); Population (see above description); Aggregation_ID (number identifying the aggregation a capsule was collected from); Capsule_ID (number identifying the capsule dissected); Hatchling_size (mm)

### field_nurse_eggs.csv: <i>nurse egg ratios for field-collected capsules</i>
  * Column names
    - Population (see above description); Aggregation_ID (number identifying the aggregation capsules were collected from); Average_hatchling_number (average number of hatchlings per capsule for that aggregation); Average_embryo_number (average number of embryos per capsule for that aggregation); Nurse_egg (average embryo number - average hatchling number)

### tank_adult_growth.csv: <i>adult growth rates (mm/day) of snails in laboratory experiment</i>
  * Column names
    - Population (see above description); Sex (M = male; F = female); Length (initial length in mm); Cont_ID (Unique ID number for the 1L container with each breeding pair); ID (Unique tag number for each snail); Treatment (C = cool; H = warm); Date (date of initial length measurement); Length_Final (final length in mm); Date_Final (date of final length measurement); Time (days eclipsed between the initial and finial measurement dates); Growth ((Length_Final - Length)/Time; units are mm/day)

### tank_development_time.csv: <i>development time (days) for laboratory-reared capsules </i>
  * Column names
    - ID (unique identification code); Pop (see above description); Treatment (C = cool; H = warm); Breeding_pair (ID number for the breeding pair); Hatch_start (date of the start of hatching); Hatch_end (date of the end of hatching); Time (days eclipsed between the start and end of hatching), Avg_Size (average size of the female in mm)
   
### tank_embryo_number.csv: <i>number of embryos per capsule for laboratory-reared capsules </i>
  * Column names
    - ID (unique identification code); Population (see above description); Treatment (C = cool; H = warm); Breeding_pair (ID number for the breeding pair); Capsule_Num (ID number for the capsule measured); Capsule_Length (mm); Number_embryos (count data); Avg_Size (average size of the female in mm)
   
### tank_embryo_size.csv: <i>embryo size (mm) for laboratory-reared capsules </i>
  * Column names
    - ID (unique identification code); Population (see above description); Treatment (C = cool; H = warm); Breeding_pair (ID number for the breeding pair); Capsule_num (ID number for the capsule measured); Emb_ID (unique number for the embryo measured from each capsule); Embryo_size (mm); Avg_Size (average size of the female in mm)

### tank_fecundity.csv: <i>fecundity (number of hatchlings * number of capsules) for laboratory-reared capsules </i>
  * Column names
    - ID (unique identification code); Pop (see above description); Treatment (C = cool; H = warm); Breeding_pair (ID number for the breeding pair); Num_capsules (number of capsules laid per female); Num_hatchling_avg (average number of hatchlings laid per capsule for each breeding female); Fecundity (number of capsules*average number of hatchlings); Avg_Size (average size of the female in mm)

### tank_hatchling_number.csv: <i>number of hatchlings per capsule for laboratory-reared capsules </i>
  * Column names
    - ID (unique identification code); Pop (see above description); Treatment (C = cool; H = warm); Breeding_pair (ID number for the breeding pair); Capsule_ID (unique number for the capsule measured from each breeding pair); Num_hatch (number of hatchlings hatched from the capsule); Avg_Size (average size of the female in mm)
  
### tank_hatchling_size.csv: <i>hatchling size (mm) for laboratory-reared capsules </i>
  * Column names
    - ID (unique identification code); Pop (see above description); Treatment (C = cool; H = warm); Breeding_pair (ID number for the breeding pair); Capsule_ID (unique number for the capsule measured from each breeding pair); Hatch_ID (unique number for the hatchling measured from each capsule); Hatch_size (hatchling size in mm); Avg_Size (average size of the female in mm)
      
### tank_nurse_eggs.csv: <i>nurse egg ratios for laboratory-reared capsules </i>
  * Column names
    - Breeding_Pair (Unique ID for each breeding pair); Population (see above description); Number_hatch (average number of hatchlings hatched per breeding pair); Embryo_number (average number of embryos per capsule per breeding pair); Ratio (average number of embryos - average number of hatchlings)
