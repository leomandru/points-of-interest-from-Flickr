# Extracting Points of Interest from Geospatial Data (from Flickr) with KNIME
The paper FSY.pdf describes and makes considerations about the whole project we developed. 

The project (Knime_Flickr_project.knwf) aims to extract points of interest to improve the public transport system of Rennes, France. Firstly, we clustered the data based on the coordinates only. Then, we used a text processing pipeline to extract the bag of words from the dataset. In doing so, we clustered the data again based on both coordinates and captions and compare both models. Lastly, we characterized the points by searching for frequent itemsets within the captions.

The whole project has been developed with Knime and Knime_Flickr_project.knwf represents the workflow we designed.
