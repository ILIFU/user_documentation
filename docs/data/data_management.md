# Data management

The following describes the directory structure and data migration process as related to the ILIFU data management policies.

## Directory structure

Users' home directories are located in `/users/`. This directory is for users' scripts. No large files should be stored in `/users/`. It is recommended that users make use of a repository such as Github to backup scripts and files.

`/scratch/` is the primary directory for data processing. `/scratch/` is for **short-term**storage only. Only temporary data required for processing should be moved here. After processing, data products should be moved to the relevant project or group directory, and intermediate data products should be removed **immediately** after processing.
`/scratch/users/` is a user specific directory for processing data, while `/scratch/projects/` is for data processing related to a project where multiple users will be involved in the data processing.

There are a number of groups within the ILIFU cloud computing community, including IDIA, CBIO and SANBI among others. For **medium- and long-term storage**, the directory structure has been broken down by group.

Information relating to the CBIO group directory structure can be found [here](https://docs.ilifu.ac.za/#/cbio/setup).



## Data migration
