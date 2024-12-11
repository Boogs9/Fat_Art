
# Fat Art at the MET

This is a collection of fatness represented in museums.

The rationale behind this project is to explore the frequency and art mediums that use fatness in the artwork. This project explores the meaning of fatness over time in the MET's digital collections. 

### Workflow

For this project, I used the following libraries; 
- Requests to make API calls
- Pandas to set up data frames and clean the data pulled from the API calls. 
- Seaborn to visualize data from multiple data frames. 
- Matplotlib to analyze data and display images of the art.

### Further Uses 

Someone might build on this work if they're interested in the representation of fat people in art. They can use this to interrogate the historical shifts in the meaning of fatness as well as which narratives of fatness are overrepresented by cultural institutions like the Met. Through this project, I found the most representations of fatness in the MET when the work used fatness as a stand-in for the greed or laziness of wealthy elites. Someone could take my project and rework the code to produce a better organization of the images of the work and their meanings of fatness. Charting the artwork and its meanings over time, whether it's currently on display, and who is represented.      


### File List 

* Python Notebook [MET_Api_(Fat_in_Art)_.ipynb, contains all the code I used for this project 
* MET_fat_ART.csv This CSV is the initial data frame I created after my API call. 
* MET_fat_ART_cleaned - MET_fat_ART (3).csv This is the CSV file with reformatted dates done in Google Sheets to remove BCE, century, and date ranges. After this new file contains all numerical data for the dates column. 
