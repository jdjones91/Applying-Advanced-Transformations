# Applying Advanced Transformations
 
### Loaded in 2 pandas DFs and proceeded with cleaning, filtering, splitting, exploding, etc.
- Per a list of attributes that our employer wanted in the final DF, I performed many transformations on this data set. 
  - After assessing for duplicates and null values, I split the Hero|Publisher column into 2 new Hero and Publisher columns
  - I also employed json.loads() followed by .str.replace to begin converting a height, weight dictionary column to separate columns with corresponding values.
  - I exploded the 'Powers' column, which contained the hero's powers as lists, and created a separate, One Hot Encoded column for each of power
  - Finally after setting all of the data types, merging our 2 DFs back together, dropping unnecessary columns (such as the Hero|Publisher column after splitting), I was able to answer 2 questions posed by our employer using EDA.
     - For Example, "What is the average height of heroes for each publisher?"
     - Below is a visual representation:
     
     <img width="529" alt="Screenshot 2022-12-15 at 11 15 26 AM" src="https://user-images.githubusercontent.com/109368648/207937121-db902b44-e285-415e-be55-30b63bbb4a69.png">
