# Videology@Onion_Math

This is a data mining project about teaching videos!

In the first stage, we try to extract some data from database and clean them to make visualization to confirm the demand of analysis.

Then, we could find the data are saved in a 2-dimension .csv file after using sparkSQL to extract from database, which is inconvenient for us to make analysis. Therefore, we want to save the data into a nested structure satisfied our need in MongoDB. After that, we clean out the invalid data and transform the data structure into different type. 

When we have the data we want, we could carry out some simple extracting algorithms to analyze ‘drag progress bar’, ‘quit video’, and ‘finish video’ operations and correct rate for interactive questions of customers. 

However, we could see that the operations during videos are always influenced by the type of content. Therefore, if we want to get some meaningful analysis, we need to find out the turn over point which is similar to the change of slides. We now use the compare between images per half second in a video to find the turn over.

In the next stage, we will design improved algrithms to apply on every part in a video to drive some conclusions.
