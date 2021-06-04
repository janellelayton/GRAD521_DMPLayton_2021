# Data Description

  Primarily quantitative data has been collected to better understand a general description of the larval fish community of the Cayman Islands from 2007-2009. This data is being used to calculate and compare species diversity by habitat type, year, Little Cayman vs Grand Cayman, and North vs South Little Cayman. There are a total of three main data sets needed and each were collected for the years 2007, 2008, and 2009. 
  
  The first set includes the following: (1) family, genus, and species of fish larvae observed; (2) date collected; (3) trap used to collect the fish; (4) collection location; and (5) the amount of each species collected. All data was collected by professional taxonomists in the field. ALl data for this set was documented in an Excel file saved as a .xlsx file sized at 282.8 KB. The second set included photographs of identified species from field collections. All photographs were saved as .jpg files sized at approximately 0.5 GB. This data was collected using GoPro cameras in the field.  The third set of data includes the Shannon diversity index calculations by (1) each year from pooled data of all sample sites and taxonomic levels; (2) family where data was collected for each sample site and grouped by year, and species where data was collected for each sample site and grouped by year. All data collected for this set will be documented in an Excel file saved as a .xlsx file sized at about 70 KB. This data was created using the 'vegan' package in R.

# Roles and Responsibilities

  The graduate student will draft the data management plan for the PI to review and revise. The PI will be responsible for the data management plan implementation which means they will confirm the data management plan is being followed throughout the project. Data has already been collected by project volunteers and co-authors during the month of March from 2007-2009. 
  
  The PI is responsible for access control, managing, archiving and the preservation of the data in the Box folder while the graduate student is responsible for data organization, data analysis, and metadata generation. Project volunteers and co-authors were responsible for instrumentation maintenance and quality control along with data collection that occurred in 2007-2009. In a scenario where volunteers and/or co-authors are lost, their responsibilities will be equally spread among other volunteers, co-authors, and the graduate student. In a scenario where the PI would no longer be able to work with this project, one of the co-authors on the project that qualifies as a later career scientist would take their responsibilities. Lastly in a situation where the graduate student is no longer able to work on the project, it is the responsibility of the PI to find another student willing to take over the responsibilities left by the previous graduate student. The PI will also be responsible for assigning data management duties to other members of the team while the search for a student is taking place.

# Data Standards and Metadata

  There are no data or metadata standards that are required for this project in the field of Fisheries Science. However, a metadata file structure is pre-defined and will be followed to maintain data generated throughout the study. All data files will be stored in one Box folder, subfolders will store raw data and data analysis procedures associated with each topic, and other appropriate subsections to store data that are collected with different environmental standards). There are three main datasets being collected. One being the quantitative data, the other being images, and the last being diversity data. The following content provides a description of what data and metadata will be generated for each and the version control measures that will be taken for the three datasets.
  
•	Dataset 1

To keep the data organized all the primary quantitative data will be collected directly on excel spreadsheets that would later be converted to .csv files. A master data dictionary will be established and used to guide entries on excel spreadsheets. This dictionary will also contain methods and protocols used in the project. Files will be stored in a directory with the project name, sample year, and subfolders for genera, families, and species collected. Raw datasets will be maintained intact, and subsequent versions or subsets labeled sequentially. Excel spreadsheet file names will include lighttrap_year_description_DDMMYYYY_reviewer.

•	Dataset 2

All images saved as .jpeg files will be labeled in the master data dictionary with the date, geographic location, taxa sampled, reviewer, equipment, habitat type, sample measurements, and sample number. 

•	Dataset 3

Diversity data will be directly collected into an excel document. Additionally, these sheets will contain methodology that includes data sources and manipulation to the data. The excel spreadsheets will be saved and exported as .csv files for analysis and preservation. This information will be stored in the master data dictionary to guide entries on excel spreadsheets and .csv files, placed in metadata files. Files will be stored in a directory with the project name, sample year, and subfolders for Grand Cayman vs Little Cayman sites, and other appropriate subsection of the project i.e., light traps, North Little Cayman vs South Little Cayman, and habitat type. Raw datasets will be maintained intact, and subsequent versions or subsets labeled sequentially. Excel spreadsheets and .csv file names will include island_year_description_DDMMYYYY_reviewer. R scripts will be stored with the associated results of analysis or datasets. For each R script there will be headers with information on the purpose of the script and how to use it. These scrips will also be publicly available under a universal license. Git will also be used as a version control software for these scripts.

  I will use the data tool Github to create, edit and export metadata files in a format that is similar to the ABCD (Access to Biological Collection Data) metadata standard. Below is a link to an example using ABCD for a botanical specimen collection in Turkey. This is a great example as it shows the ABCD schema is highly structured to manage the large quantity of data that a record may contain. You can see how the top level of the schema is arranged and then you can see the two major groups, one holding metadata about the entire dataset (Metadata) and the other holding the actual data records (Units).
https://abcd.tdwg.org/xml/documentation/primer/2.06/#appendix

# Storage and Security

According to OSU’s definition of sensitive and confidential data, none of the data being collected is considered sensitive and it does not need protected. The backup strategy for this dataset is quite simple. There are always 3 copies in total of the original dataset. One saved with the PI, one with graduate student, and one on a shared network drive on Box. The Box folder is always backed up on a hard drive stored in the office of the PI. Saving new data to this Box folder and to the hard drive is a manual process. The Box folder is available to the PI, co-authors, and all volunteers so when the graduate student graduates all data will still be accessible. The copu backed up to the Box folder will be known as the reference copy. This copy is the one that will be updated first, so that everybody can access it and update their own copy. Data will be kept organized using the following file names island_year_description_DDMMYYYY_reviewrer.csv for data set 3, lighttrap_year_description_DDMMYYYY_reviewer.csv for data set 1, and taxa_lighttrap_year_reviewer.jpeg .

# Access and Data Sharing

  Currently there are no factors that limit the availability to share this data publicly. The data collected for this research will be shared publicly, since there is no sensitive data that requires legal or financial considerations.
  All data will be made publicly available at the time of publication on the ScholarArchive@OSU repository under the public domain with a CC 1.0 Universal license. Under this license, the reuse, redistribution, and creation of derivatives of the data is permitted. This license also indicates that the person associated with this work had dedicated the work to a public domain by waiving all their rights to the work worldwide under copyright law. The spreadsheets will be published in the form of .csv and .pdf files and photos in the form of .jpeg files. GitHub will be the tool used for data sharing in this project.

  
# Archiving and Preservation
  
  The long-term plan for preservation will depend on the ScholarArchive@OSU rules and regulations.ScholarsArchive@OSU is an institutional repository, maintained by OSU libraries and press, and that its goal is preservation of OSU scholarship, including data. There are no plans to remove the data from ScholarArchive@OSU and it is expected they will preserve the datasets for as long as possible and ensure the data remain available to the public. In addition, there will be backup copies of the data on GitHub and with the PI in a Box folder for at least the next five years. All archives will be stored in csv, pdf, and jpeg format.
  
  

