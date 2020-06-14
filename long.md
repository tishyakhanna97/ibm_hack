# Welcome to LiveIntel!

## Overview
Firefighting is hard enough. Therefore, we at LiveIntel have found the right balance of technology and usability in order to ensure that firefighters are able to operate safely and effectively. Below, we have explained the 2 key components of LiveIntel which make it the ultimate intelligence solution.

### Live Intelligence
By making use of Watson Studio's Visual Recognition, we have trained our model to effectively identify objects of interest (eg. fire, rubble, civilians, etc.). Images captured on every firefighter's camera will be sent to a central server to be analysed by the model. If the model identifies an image to contain an object of interest, the object, as well the location of the object, will be plotted on the user interface immediately. As firemen progress through the building, more information will be updated on the user interface, eventually providing them with an informative map of the area.
 
### Sentiment and Environment Analysis
In order to gauge the welfare of the firefighters, we made use of Watson’s speech-to-text and Natural Language Understanding modules to understand the sentiment and distress levels of firefighters while they are deployed in the field. Firstly, speech of firefighters will be recorded and sent to a central server. For each firefighter, speech will be converted to text using IBM Watson’s speech-to-text module, then passed into Watson’s Natural Language Understanding module, which will output the emotion and overall sentiment of firefighters based on their speech. This information will then be displayed on a user interface, together with a humidity and temperature gauge. 

There is also a priority based table listing the names, location and distress level of all the firefighters. This table will constantly update in real-time and display firefighters with higher distress levels on top. Commanders may then make use of such information to allocate resources and aid their firefighters.

