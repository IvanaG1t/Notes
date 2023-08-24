# About NIH Genomic Data Commons Data Portal

A comprehensive platform gathering data and providing eploration options from Cancer patients' samples. More details could be found [here](https://github.com/NCI-GDC/gdc-docs) or on [their website](https://gdc.cancer.gov/).
 
 
## Downloading datasets of interest
 
Data is mostly in BAM file format so it would be faster to download and ready to process. 
The portal recommends using [GDC Data Transfer Tool](https://gdc.cancer.gov/access-data/gdc-data-transfer-tool), 
which is a command-line operated application with a lot of explanation on the link provided here.


### System Recommendations 

**The system recommendations** for using the GDC Data Transfer Tool are as follows:

- OS: Linux (Ubuntu 16.x or later), OS X (10.9 Mavericks or later), or Windows (8 or later)
- CPU: At least two 64-bit cores, Intel or AMD
- RAM: At least 8 GiB
- Storage: Enterprise-class storage system capable of at least 1 Gb/s (gigabit per second) write throughput and sufficient free space for BAM files.
 
A personal laptop should be fine, but with a lot of storage space!

## How to actualy start
 
 There is comprahensive [documentation](https://docs.gdc.cancer.gov/Data_Transfer_Tool/Users_Guide/Preparing_for_Data_Download_and_Upload/) manual about this provided by GDC that shows in greater detail what I'sumarized here.
 The tool comunicates with online data portal. There are a few sequential steps to be taken:
  1. In the [portal]() select the cancer you are exploring.
  2. Click on the "View files in repository" (*because that's where raw data is kept*). Try to narrow down the search to 10 000 files (each case can have multiple types of files), or you would need to repeat these steps few times.
  3. Add cases to cart. Go to cart. Click on "Download" button and select Manifest. This way you would use their tool to pull the data onto your working machine based on the list in the manifest file.
 
GDC is neat source of data because they provide [analysis-ready reference](https://gdc.cancer.gov/about-data/gdc-data-processing/gdc-reference-files) and index files, as well as annotation files for transcriptomics. 
