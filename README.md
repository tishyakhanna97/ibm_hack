# Welcome to LiveIntel!
About us + challenge statement

## Short Description
### The uncomfortable truth
On our wonderful island home Singapore, we are thankfully protected from the impacts of natural disasters. However, even Singapore is not immune to climate change. Temperatures have steadily increased over the last 2 decades, and are projected to increase by a [whopping 4.6 degrees](https://www.nccs.gov.sg/singapores-climate-action/impact-of-climate-change-in-singapore/) 

 This does not bode well for the SCDF firefighters, who already contend with highly dangerous and stressful situations during active operations, whether its responding to fires, rescue missions or evacuations. This increase in temperature is compounded by the metropolitan nature of Singapore, making the environments that firefighters have to contend with that much more warmer and challenging. 

In addition, [studies](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5715452/) have shown that the increasing temperatures during firefights reduce the firefighters ability to process and recall information.  **This is not something to be taken lightly. Climate change is affecting the ability of our firefighters to save lives, both of civilians and their own.**

### Our Solution
We at LiveIntel believe that the best way for us to support our firefighters is with information. By providing firefighters with the right monitoring and intelligence tools, we will be able to maximise the power of information. Increasing temperatures and [fire incidents](https://www.scdf.gov.sg/docs/default-source/scdf-library/amb-fire-inspection-statistics/scdf-annual-statistics-2019.pdf) are already making things tougher for firefighters, so minimising uncertainty will allow firefighters and commanders to make better, more well informed decisions, without sacrificing their own safety. 

**With information, we believe that we can save lives.**


## Video

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## Architecture 
 1. The sensors attached to the firefighters in the heat of battle transmit the relevant information (images, recorded speech, temperature and humidity readings) to the IBM Cloud server.
 
 2. Visual recognition on the images allows us to plot the highlighted areas on our blueprint using MazeMap
 3. The recorded speech is converted to text using Speech to Text and is then analysed using the Natural Language Understanding for distress levels. 
 4. Using the IoT platform, we are able to monitor and track the incoming temperature and humidity readings
 5. Finally, all this information is presented on a single tab of the Node-Red Dashboard



## Long Description

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## Roadmap

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Getting started with our Live Demo

### MazeMap
 1. Click on this [link](https://tishyakhanna97.github.io/ibm_hack/)
 2. You will see a template map of a bookstore which is currently facing a fire incident
 3. The blue dot is a brave firefighter, who is equipped with his camera. 
 4. Now, **Press Enter twice**
 5. Our firefighter has just moved to hall 2. Throughout the journey, the camera was tracking his surroundings.
 6. In hall 2, his camera **recognises that the left path is blocked by rubble**, and this is plotted on the map.
 7. Now, **Press Enter twice**
 8. After choosing the right path, the firefighter and the camera note the presence of a victim and the fire.
 9. Now, **Press Enter once**
 10. The fire has been extinguished.
 11. With this, we have plotted the inside of the building, allowing commanders outside to make more informed decisions when moving their firefighters/
 
### Node Red
 1. Click on this [link.](https://node-red-paqpj.mybluemix.net/ui/#!/1?socketid=voWzvcUAlTyvbrFgAAA4)
 2. Immediately, you will be able to see the sentiment and environment analysis of Peter, one of our firefighters.
 3. **Press the three lines at the top left and select Live Voice Recording**
 4. On this page, you can record something that you feel a firefighter would say during a firefight.
 5. **Try recording something and then click on the 3 lines at the top left and choose Firefighter(Peter)**
 6. Here, you will see the changes in Peter's emotions based on the input speech.
 7. **Click on the 3 lines at the top left and choose Live Firefighter Status**
 8. Here, you (as the commander) can see the statuses of all your firefighters. As they are live, the firefighters who are in the most distress will be pushed to the top of the table, for immediate attention and help.




## Built With

 - IBM Watson’s speech-to-text
 - IBM Watson’s Natural Language Understanding
 - Node Red
 - IBM’s Visual Recognition
 - IBM's Internet of Things Platform
 - [Mazemap](https://www.mazemap.com/)
