# Dissertation
This is a place to put my code and extended results so it can easily be checked. 

# Saichev and Sornette Function and Widget

To see the code for Saichev and Sornettes click on the file. 
If you wish to try out the code you can then copy and paste it into Juytper notebooks (a interactive online python tool). 
Or straight copy the code into a python command

# Synthetic Earthquake catalogues by ETAS.inlabru

You can see my motified code from Naylor (2022), 
link to the orginal code: https://github.com/edinburgh-seismicity-hub/ETAS.inlabru/tree/main/notebooks/generateSyntheticCatalogues
If you want to try it out you will need to download R, R Studio and ETAS.inlabru on your device. 


N=length(cat$ts)
iet =cat$ts[2:N]-cat$ts[1:N-1]

directory <-getwd()
directory
write.csv(iet, "Interevent_time_catalog_Touatis.csv")
