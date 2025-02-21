# Deployment Documentation  

This repository includes all the resources required to deploy the **Base IMIS** application for a new city, including essential documentation, configuration files, and database backups. The deployment process is supported by three key components:  

- [**Deployment Manual**](https://github.com/birendranagar-imis/deployment_documentation/tree/master/deployment_manual): A detailed guide outlining the step-by-step process to ensure a smooth and efficient IMIS deployment. Two manuals are available, one for production on Linux- Ubuntu OS and one for development on Windows OS.  
- [**Docker Configuration**](https://github.com/birendranagar-imis/deployment_documentation/tree/master/docker_config): A folder containing all the necessary files and directories for the Docker-Compose setup, enabling the deployment of the IMIS web application.  
- [**Database**](https://github.com/birendranagar-imis/deployment_documentation/tree/master/database): A folder containing a blank IMIS database to initialize a new instance with the required database structure, along with a database populated with dummy data for demonstration purposes only.  
- [**Geoserver Setup**](https://github.com/birendranagar-imis/deployment_documentation/tree/master/geoserver_setup): A folder containing the config.yml file required for setting up the printing for MapFish Print in Geoserver, and the zipped workspace required to import the workspace of IMIS directly to geoserver.
- [**Sample Data for Import**](https://github.com/birendranagar-imis/deployment_documentation/tree/master/sample_import_data): A folder containing sample datasets in GeoPackage (GPKG) format, intended for import during IMIS deployment. These datasets are provided solely for demonstration and practice purposes.

These resources ensure a seamless and standardized deployment of IMIS across different instances of IMIS.
