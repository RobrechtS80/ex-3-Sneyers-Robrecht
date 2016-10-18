## ex-3-Sneyers-Robrecht 3 INF

REST API --> omschrijving en gebruik welke resources. 

`calculation`    
**toont het antwoord standaard op 0**       
`URL: http://localhost:4567/calculation`

| Field         | Type          |
| ------------- |:-------------:|
| optelling     | integer       |
| maal          | integer       |
| deling        | integer       |
***
**POST**    
      

**Uitvoeren van een optelling**    
     
`URL: POST http://localhost:4567/calculation/optelling/<optetellen getal>`      
Voorbeeld: POST http://localhost:4567/calculation/optelling/6 _calculation=0 dus 0 +6 =6_    
   
**Uitvoeren van een vermenigvuldiging**    
`URL: POST http://localhost:4567/calculation/maal/<getal>`   
Voorbeeld: POST http://localhost:4567/calculation/maal/6 _calculation*6_    
     
**Uitvoeren van een deling**    
`URL: POST http://localhost:4567/calculation/deling/<getal>`    
Voorbeeld: POST http://localhost:4567/calculation/deling/6 _calculation/6_    
     
  
     




Voorbeeld URL dat ik wil bereiken: /calculation/optelling/Var1 --> calculation staat standaard op 0 dus stel dat we uitvoeren /calculation/optelling/3 dan krijgen we 0+3
nu staat calculation op 3 en kunnen we bijvoorbeeld /calculation/optelling/6 dan 3+6 is 9
hiervoor gebruiken we een POST 
voor het krijgen van de current waarde van calculation gebruiken we een GET
voor het verwijderen gebruiken we DELETE om calculation terug te verwijderen en op 0 te zetten.

Verder kan je dan ook breuk,maal,vierkantswortel, ...enz toevoegen als resources.

Ik geloof dat dit REST is omwillen van het feit dat elk getal eigenlijk wordt opgeslagen en de berekening via de URL gebeuren.

**Bronnen**
Link gebruikt voor het achterhalen hoe ongeveer : http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api
http://apigee.com/about/blog/technology/restful-api-design-nouns-are-good-verbs-are-bad
http://stackoverflow.com/questions/8275209/how-can-i-create-a-restful-calculator
Link gebruikt voor Request --> req.params : http://expressjs.com/en/api.html

