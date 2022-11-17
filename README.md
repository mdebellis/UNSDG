# UNSDG
United Nations Sustainable Development Goals Ontology

This is a small demonstration ontology of the UN Sustainable development goals. The goals can be found at: https://sdgs.un.org/goals 
This ontology covers all of the Goals, Targets and Indicators. The ontology is based on the meta-data from the UN here: 
https://unstats.un.org/sdgs/indicators/Global%20Indicator%20Framework%20after%202022%20refinement.English.xlsx
The ontology was mostly created automatically by using Cellfie to load the data from the spreadsheet into Protégé and then using the Snap SPARQL plugin to create the appropriate relations (object property values) from Goals to Targets and from Targets to indicators. A more detailed description of the development process can be found on my blog: https://www.michaeldebellis.com/post/unsdg-ontology

I'm putting it here because I may integrate it with work that another team is doing and/or with additional data on the UN SDG data hub: https://unstats-undesa.opendata.arcgis.com/  The best way is to fork the project so you get notified of new work. However, if you aren't an experienced Github user and you just want to download the ontology, you can do the following:

1) Click on the ontology file

2) Once in the ontology file, just above the beginning of the actual file there are several buttons above the file on the right: "Raw", "Blame", a pen, etc. Click right on the "Raw" button and you should get an option to "Save link as". Use that and navigate to where you want to save the file. 
