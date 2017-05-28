#AgData
Provides pricing data for Agricultural commodities in India using a text-message based interface.
Uses data scraped from Agmarket.nic.in.

##Usage:
Text ```<market> <commodity> <date>``` to ```<Twilio number>```.

####Example:
Texting:
```Shimla Potatoes May 28, 2017```
would return:
```
Shimla - Potatoes May 28/2017
Min: 1000, Max: 1200, Mode: 1100
Stock: 0.6 Tonnes.
```

