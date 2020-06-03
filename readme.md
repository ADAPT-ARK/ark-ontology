# ARK Ontologies
This repository is used to update the ARK ontologies (Cube, Amarach, Projects and Terminologies) and provides a content negotiation configuration following Linked Data guidelines.
	
## To update the ontologies on your local machine
1. Clone the repository to your local machine
1. Update the ontologies (owl files)
1. Generate the documentation into their specific folders - ARKAmarach, ARKCube, ARKProjects, etc. Documentation can be generated using using [WIDOCO](https://github.com/dgarijo/Widoco) (jar available in the repository)
1. Note that the .htaccess file in the Ontologies folder redirects to ARKCube/index-en.html 
1. If you generate a new .htaccess file then you must update it in each folder changing `RewriteBase /ONTOLOGY_NAME` to `RewriteBase /Ontologies/ONTOLOGY_NAME`
	
##	Server side
	
Considering that Apache server has been installed, you can pull the repository under your web folder (e.g /var/www/html/ if using default configurations).
