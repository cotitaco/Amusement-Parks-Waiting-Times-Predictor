# Amusement-Parks-Waiting-Times-Predictor
What is the worst part of going to Disney World or to the Wizarding World of Harry Potter?
For me it is having to be in line for two hours to enjoy four favorite ride.
As stated before the objective of this project is to predcit how much time it will take you to get into a ride. 

To train my model I first needed to get some data. So I consult different web pages who have "real time information" about Orlando's Amusement Parks. I center my efforts on 2 big companies which are Disney and Universal.

Inside Disney I get information from 4 different parks in Orlando: Magik Kingdom, Epcot, Animal Kingdom and Hollywood Studios.
Inside Universal I get information from 2 different parks in Orlando also: Universal Studios and Islands of Adventures. 

In order to extract information from these parks I did tow different types of scripts and then merged them together.

1. In ordert to get weather and climate and make a deep analysis, I connected to a Weather API, so if you are a begginer please have this in mind before doing some copy-paste and expect the code to work. 
2. To check how long queues are inside the parks, I created a web scrapping code. It goes into 3 different web pages and it extracts text from tables. 

Once all information is stored inside my volatile memory I perform only formating of the information and add colums' names. After all formating is done, all information is saved in a .csv.

Finally it is crucial for you to understand my code that I programmed a scheduler. Every 10 minutes my functions runs. So as a result if I run my script from 8 am since the park opens, to 8-9 pm once all parks close, I will have approximatelly 80 different files. Disney Parks rides are all saved inside the same file, same as Universal parks. So you will have 80 different CSVs for Disney and 80 different ones for Universal.
In order to have control please run the concatenador sript. This one will grab all files inside a given folder and will concatenate all csvs in one. So we will end up with 2 different files, one for disney parks and one for universal parks. 
I hope this information is usefull. Good luck with your projects!

Bright Suns ;)
