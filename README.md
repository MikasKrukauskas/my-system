# System name
- [Weather tracker] 

# Description
- [Track weather] 

# Entities
- [Weather]  
    - [ID:Mandatory Number (0<ID<150)]
    - [City:Mandatory String (<30 char)]  
    - [Country:Mandatory String (<30 char)]
    - [Date:Mandatory Date]
    - [Temperature:Mandatory String(<4 char)] 
    - [Icon:Blob(<250 MB)] 
    - [WeatherDescription:String(<250 char)] 
    - [Wind:String(<100 char)] 
    - [Humidity:String(<100 char)] 
    - [Cloudiness:String(<50 char)]
    
# Api methods
        - [ Get weather report by its id Method: Get /api/weather/:id] 
        - [ Get weathers list by selected country Get /api/weather/:country ] 
        - [ Delete a weather report Delete /api/weather/:id ] 
        - [ Edit a weather report Put /api/weather/:id ] 
        - [ Post a weather report Post /api/weather/:id]  
# UI https://bit.ly/2THCoVr
- [ There will be two windows:main, second ]
    - [Main: A list of weathers in selected country: city, weather, icon ]
     - [Possible actions:]
         -[Find: find cities]
         -[Select: select a city]
         -[GiveMoreInformation: open a second window)]
    - [Second: ] 
      - [Possible actions: ]
          - [Edit: edit selected date range]
          - [Delete: delete selected weather report]
          - [Post: post an information about weather by selected date]
          - [PostWeatherDescription: post a description about weaher]
          - [PostWind: post an information about wind]
          - [PostHumidity: post an information about humidity]
          - [PostCloudness: post an information about cloudness]
            
