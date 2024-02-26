__Atlas Streams Processing POV__ 
- This is a demo of Atlas Streams processing and how it works

__Pre-requisites:__
- VS Code
- MongoDB plugin
- Setup a sample stream processing instance on Atlas with the MySolar streams instance
- configure another connection on the streams processing instance called mongodb1 to connect to your chosen MongoDB Atlas cluster 

__Demo steps:__
- Connect to the Streams processing instance first in VS Code plugin 
- Run the sp-playground.mongodb file in the MongoDB plugin
  a. Test the functionality of the process function - to see the streams in realtime
- Run the persistent-sp.mongodb file till the line where it starts the streams processing instance
- verify the streams processing instance is running with the stats command
- check the mongodb collection for the MySolar.solar collection on the chosen cluster - see that it has the aggregated data points 
