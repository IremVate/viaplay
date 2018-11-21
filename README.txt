# Project Title

Viaplay technical test

## Solution
- The first screen contains the section list. Using retrofit, if the device is online, I get the data from the service and populate the table in the database, post the value to my MutableLiveData List to show the content to screen.
If the device is offline I get the section list from my database. 

- Choosing one of the sections a new screen appears with the details information of the choosen section. Basically to get the appropriate details for the choosen section, the key parameter is the sectionID. 
Based on the the section type and section name the corresponding API is called.
If the device is online the table will be filled and data will be shown on the screen. If the device is offline I get the data from the database with the sectionID parameter.


## Disclaimer

Used:
- MVVM architecture(databinding)
- ROOM for storing data.
- RESTROFIT - for the network layer.



