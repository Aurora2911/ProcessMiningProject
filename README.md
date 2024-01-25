INTO ELDERLY LIFE

The context of this project is defined by the usage of a dataset that stores information collected by sensors regarding an elderly individual living in a smart home. 
Indeed, while the increase in life expectancy represents a significant milestone for humanity, it concurrently gives rise to ever-growing challenges related to elderly care, 
high costs for medical treatments, and more. Therefore, the application of artificial intelligence, robotics, and cutting-edge technologies can aid in addressing these difficulties.
Given that, dataset employed in this project was found using those provided by Center for Advanced Studies in Adaptive Systems (CASAS).

The chosen dataset is called ‘hh123’ and stores information about activities carried out by a volunteer over a period of one month: from 2/03/2013 to 1/04/2013. 
Therefore, the main goal of this project could be to identify habits of the considered individual and define if something could be improved, leading to healthier lifestyle or not.

This task was possible using ProM software, usefull for applying Process Mining techniques.
This task has been carried out taking into account different periods of time: weekly case and daily case.

Features needed:
- Case is represented by the column ‘Date’.
- Events inside a case are defined by the feature ‘Activity’.
- Events are described by 'Starting Time' and 'Ending Time'.
Details regarding pre-processing work to obtained the above structure are in following google colab link: https://colab.research.google.com/drive/1XQDs9VpBkuich90e9_ui6eLoASQqNNqC?usp=sharing 

Datasets needed:
- Weekly case represents activities carried out during a week, therefore it’s required a dataset containing rows regarding all the available four weeks.
The created dataset is called ‘WeekDataset-31days’.
- Daily case corresponds to activities carried out during each single day of the week, there will be needed seven different datasets containing all rows of each single day considered.
In this case the created datasets are called as weekday’s names (Monday, Tuesday and so on).
Details regarding this datasets division are in following google colab link: https://colab.research.google.com/drive/1XswYzo13ORCauur1l_JrAXNhhhi9Mfzj?usp=sharing

