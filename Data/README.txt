This README.txt file was generated on 20231112 by Benjamin Delory

-------------------
GENERAL INFORMATION
-------------------

1. Raw data used for the following paper: Alonso-Crespo et al (2024) Exploring priority and year effects on plant diversity, productivity and vertical root distribution: first insights from a grassland field experiment.  

2. Author Information

  Principal Investigator Contact Information

	Name: Vicky M. Temperton
        Institution: Institute of Ecology, Leuphana University
        Address: Universitaetsallee 1, 21335 Lueneburg, Germany
        Email: vicky.temperton@leuphana.de

        Name: Benjamin M. Delory
        Institution: Copernicus institute of sustainable development, Utrecht University
        Address: Princetonlaan 8a, 3584 CB Utrecht, The Netherlands
        Email: b.m.m.delory@uu.nl

3. Date of data collection (harvest): July 2020 to June 2023 

4. Geographic location of data collection: POEM experimental site, Niederhaverbeck, Germany

5. Data collected by Inés M. Alonso-Crespo, Benjamin M. Delory, Thomas Niemeyer, Vicky M. Temperton

-----------------------------------------------------------------
DATA-SPECIFIC INFORMATION FOR: 
	Data_Biomass_POEM2020_2020-07.xlsx
	Data_Biomass_POEM2020_2021-06.xlsx
	Data_Biomass_POEM2020_2022-06.xlsx
	Data_Biomass_POEM2021_2021-07.xlsx
	Data_Biomass_POEM2021_2022-06.xlsx
	Data_Biomass_POEM2021_2023-06.xlsx
-----------------------------------------------------------------

1. Number of variables: 6

2. Variable List
    A. Name: Year
       Description: the year of initiation of an experiment. This factor has 2 levels: 2020 or 2021.
       Type: integer

    B. Name: Harvest
       Description: the harvest date (year-month)
       Type: character

    C. Name: Plot
       Description: the plot ID (plot number-PFG order of arrival/Replicate). Plant functional group order of arrival has 5 levels (each replicated 5 times in each sub-experiment):
	- S: synchronous plots (forbs, grasses and legumes sown simultaneously at the first sowing event)
	- F: forbs sown 6 weeks before grasses and legumes
	- G: grasses sown 6 weeks before forbs and legumes
	- L: legumes sown 6 weeks before forbs and grasses
	- B: free succession plots
       Type: character

    D. Name: Quadrat
       Description: the quadrat ID number (1 to 4, or 1 to 2)
       Type: integer

    E. Name: Species
       Description: the plant species name
       Type: character

    F. Name: SDW_g
       Description: shoot dry weight
       Type: numeric
       Unit: g

----------------------------------------------------------------
DATA-SPECIFIC INFORMATION FOR:
	Data_presence-absence_species_POEM2020_2021.xlsx
	Data_presence-absence_species_POEM2020_2022.xlsx
	Data_presence-absence_species_POEM2021_2021.xlsx
	Data_presence-absence_species_POEM2021_2022.xlsx
	Data_presence-absence_species_POEM2021_2023.xlsx
----------------------------------------------------------------

1. Number of variables: depends on the file

2. Number of cases/rows: 25

3. Variable List
    A. Name: Name_experiment
       Description: the name of each POEM sub-experiment. This factor has 2 levels: POEM2020 and POEM2021.
       Type: character

    B. Name: Year
       Description: the year of initiation of an experiment. This factor has 2 levels: 2020 or 2021.

    C. Name: Harvest
       Description: the harvest date (year)
       Type: integer

    D. Name: Growing_season
       Description: the number of the growing season
       Type: integer

    E. Name: Name_growing_season
       Description: the name of the growing season
       Type: character

    F. Name: Plot
       Description: the plot ID number
       Type: numeric

    G. Name: Arrival
       Description: plant functional group order of arrival. This factor has 5 levels:
	- S: synchronous plots (forbs, grasses and legumes sown simultaneously at the first sowing event)
	- F: forbs sown 6 weeks before grasses and legumes
	- G: grasses sown 6 weeks before forbs and legumes
	- L: legumes sown 6 weeks before forbs and grasses
	- B: free succession plots
       Type: character

    H. Name: Replicate
       Description: the replicate number (1 to 5)
       Type: integer

    Column I and following: presence (1) or absence (0) of each species in a plot.

--------------------------------------------
DATA-SPECIFIC INFORMATION FOR: features.csv
--------------------------------------------

1. Number of variables: 18

2. Number of cases/rows: 17960 (for 2022 data) or 5760 (for 2023 data)

3. Variable List
    A. Name: File.Name
       Description: the name of each image processed by RhizoVision Explorer
       Type: character
       Format: NameExperiment_TubeNumber_LocationNumber_Date(YYYY.MM.DD)_Time(HHMMSS)_SessionNumber_OperatorName.png

    B. Name: Region.of.Interest
       Description: the region of interest used for the analysis
       Type: character

    C. Name: Number.of.Root.Tips
       Description: the number of root tips
       Type: integer

    D. Name: Number.of.Branch.Points
       Description: the number of branch points
       Type: integer

    E. Name: Total.Root.Length.mm
       Description: the total root length
       Type: numeric
       Unit: mm

    F. Name: Branching.frequency.per.mm
       Description: the branching frequency
       Type: numeric
       Unit: mm-1

    G. Name: Network.Area.mm2
       Description: the network area
       Type: numeric
       Unit: mm²

    H. Name: Average.Diameter.mm
       Description: the average root diameter
       Type: numeric
       Unit: mm

    I. Name: Median.Diameter.mm
       Description: the median root diameter
       Type: numeric
       Unit: mm

    J. Name: Maximum.Diameter.mm
       Description: the maximum root diameter
       Type: numeric
       Unit: mm

    K. Name: Perimeter.mm
       Description: the perimeter
       Type: numeric
       Unit: mm

    L. Name: Volume.mm3
       Description: the root volume
       Type: numeric
       Unit: mm³

    M. Name: Surface.Area.mm2
       Description: the root surface area
       Type: numeric
       Unit: mm²

    N. Name: Computation.Time.s
       Description: the computation time
       Type: numeric
       Unit: s

    O. Name: Root.Length.Diameter.Range.1.mm
       Description: the total root length measured in the first diameter class
       Type: numeric
       Unit: mm

    P. Name: Projected.Area.Diameter.Range.1.mm2
       Description: the projected area measured in the first diameter class
       Type: numeric
       Unit: mm²

    Q. Name: Surface.Area.Diameter.Range.1.mm2
       Description: the root surface area measured in the first diameter class
       Type: numeric
       Unit: mm²

    R. Name: Volume.Diameter.Range.1.mm3
       Description: the root volume measured in the first diameter class
       Type: numeric
       Unit: mm³