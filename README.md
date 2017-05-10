# DEMLAS warehouse code base
Data and metadata management system composed of the following components:
### 1. Discovery map portal
Web application developed in HTML / JavaScript using Bootstrap, Openlayers 3 and JQuery APIs offering users discovery and geo visualization options. 

Online app is available here: https://demlas.geof.unizg.hr/warehouse/portal/
### 2. Data uploader and manager
PHP, HTML and JavaScript web application capable to browse data in preconfigured root directory, create new dir structure, upload new files and create descriptive information - metadata using metadata editor described above. Datasets get uploaded as files on the server, plus in addition if geospatial data formats, e.g. GeoTIFF, ShapeFile, they get published in platform geoserver. Corresponding metadata encoded in Dublin Core XML get generated automatelly during file upload, which can later be updated by user using Metadata editor.

App is powered by [Evoluted Directory Listing Script](https://github.com/XnSger/EvoDire)

### 3. Metadata editor
### 4. Geoserver
### 5. Catalogue
