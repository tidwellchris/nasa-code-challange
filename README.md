#Setup Before Interview
1. Download and install Community Edition of IntelliJ - https://www.jetbrains.com/idea/download/#section=mac 
2. Make sure you have Java 11 SDK installed
3. Make sure you can reach Maven Repo from within IntelliJ - https://mvnrepository.com/

##Setup During Interview
1. Install this.. from Git or download from Git and setup on your PC/Mac

#Objective
Here is the Base EndPoint https://api.nasa.gov/mars-photos/api/v1/rovers/curiosity/photos  
Here is the ApiKey - sx13z1ze9eBrM0uE5Y8DZfksuaqmIM1juWXwNZ1q --Don't publish to github...
Here are the params
- earth_date 
- camera


###What We Want
1. Make a call to get photos from a specific camera on a specific day
   1. Create a Proxy for the new call
   2. Create a Controller that we can hit
   3. Create a Transfomer to transfrom the data into the final contract
   4. Use your browser to curl your endpoint 
2. Make a call to get photos from more than one specific camera on a specific day (Merged the Calls together)
3. Testing


###Final Contract
```
[
    {
        roverName: "Curiosity",
        cameraName: "CHEMCAM",
        imageUrl: "http://mars.jpl.nasa.gov/msl-raw-images/proj/msl/redops/ods/surface/sol/02426/opgs/edr/ccam/CR0_612857715EDR_F0752860CCAM05424M_.JPG",
        date: "2019-06-03"
    }
]
```
