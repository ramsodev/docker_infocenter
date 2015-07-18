## ramso/infocenter
A docker with eclipse infocenter ans scripts to load your documentation plugins in 


#Usage
'docker run -d --name testlink -p 8080:8080 -v ~/infocenter:/var/plugins ramso/infocenter


Access to the infocenter in the url http://localhost:8080/help/index.jsp 

For add your documentation to the infocenter use the volume folder, in every restart the plugins in the volumen folder are copied to the eclipse plugin folder. 
