# Public Goods Tool
## Background
The PG Tool was built to allow researchers and land managers alike to easily identify the public
goods that are being created on their land through data collected under various indicators. The
tool was also built with flexibility and adaptability in mind, with numerous custom versions being
built over the years to address specific research interests.

This REFOREST version of the PG Tool was developed by [Organic Research Centre](https://www.organicresearchcentre.com) and [University of Reading](https://www.reading.ac.uk/), based on an [original version](https://github.com/organicresearchcentre/pgtool-api) of the online PG Tool. The tool offers an interface that increases accessibility for farmers, advisors and researchers to interact and learn with it.

You can access the REFOREST version of the PG Tool at the [REFOREST website toolbox](https://reforest.euromed-economists.org/).

A [user guide for self-assessments](https://github.com/organicresearchcentre/pgtool-reforest-gui/blob/main/REFOREST%20PG%20Tool%20Online%20Manual.md) has also been created for the REFOREST version of PG Tool.

For developers there is [further infromation](https://github.com/organicresearchcentre/pgtool-gui/blob/main/PG%20Tool%20Online%20Development.md) about the design and future development of the PG Tool.

For any queries about the PG Tool please contact christian.g@organicresearchcentre.com.

## How to host the website

If you want to host this version of the PG Tool on your local computer or server, then simply download the files for the GUI and the [API](https://github.com/organicresearchcentre/pgtool-reforest-api) and place them in the desired directory.

![Directory Guide](https://github.com/organicresearchcentre/pgtool-gui/blob/main/Directory%20Guide.png)

The GUI is currently configured to run in the path "/pgtool-gui". If you wish to use another path i.e. for a customised version, then there are two required alterations:

- in the `.htaccess` file: replace all "pgtool-gui" string occurrences with the desired path.

- in the `js/script.js` file: replace `base: '/pgtool-gui'` with the desired path.



