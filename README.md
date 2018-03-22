# Weather-Station
An Environment Controller
For reading data from a Peripheral, "ubit" over BLE to a Pi that will control circuits to maintain an ideal growing environment and logging this data to compare yields and growth during 'cycle/season' 

Environment parameters are Temperature and Humidity
Ideal Temperature range is 75-85 degrees Fahrenheit during 'lights on' and 65-75 degrees Farenheit during 'lights off'
Ideal Humidity range is 60-80% during 'Vegatation' and 40-60% during 'Flowering'

I will be building 3 sets of Weather Stations (ubit and pi) for each of my growing stations

Station 1 'Vegeation' Ideal Parameters = Temp: 75-85; Humdiity: 60-80%
   -When Temperatures 'drop' below 'Ideal' all fans will be turned off
   -When Temperatures 'rise' above 'Ideal' all fans will be turned on
   -When Temperatures are 'Ideal' only circulation fans will be on

   -When Humidity 'drop' below 'Ideal' Extration fan and Dehumidfier will be turned off
   -When Humidity 'rise' above 'Ideal' Extraction fan and Dehumidifier will turn on
   -When Humidity is 'Ideal' Dehumidifier will be turned off
   
Station 2/3 'Flower1/Flower2' Ideal Parameters = Temp: 75-85; Humdiity: 40-60%
   -When Temperatures 'drop' below 'Ideal' all fans will be turned off
   -When Temperatures 'rise' above 'Ideal' all fans will be turned on
   -When Temperatures are 'Ideal' only circulation fans will be on

   -When Humidity 'drop' below 'Ideal' Extration fan will be turned off
   -When Humidity 'rise' above 'Ideal' Extraction fan and Dehumidifier will turn on
   -When Humidity is 'Ideal' Dehumidifier will be turned off
