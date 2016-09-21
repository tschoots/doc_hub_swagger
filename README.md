# doc_hub_swagger

./manageSysProp.sh     



`./manageSysProp.sh: [-b,blackduck] [-a,add | -d,delete | -g,get | -u,update] property_name
[-b,blackduck] -l,list [property_name]`

-bash-4.1$ ./manageSysProp.sh -l blackduck.swagger.displayAll

Enter the name of the space (prop, config, control, solrcloud) the property lives in : config

./manageSysProp.sh: blackduck.swagger.displayAll doesn't exist in config

-bash-4.1$ ./manageSysProp.sh -a blackduck.swagger.displayAll

Enter the name of the space (prop, config, control, solrcloud) the property lives in : config

Please enter property value : true

Add blackduck.swagger.displayAll into config was successful