## ex-3-Sneyers-Robrecht 3 INF

### REST API --> omschrijving en uitleg resources.    
***
     

**calculation**    
`toont het antwoord standaard op 0`          
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
Voorbeeld: POST http://localhost:4567/calculation/optelling/6   _calculation=0 dus 0 +6 =6_    
   
**Uitvoeren van een vermenigvuldiging**    
      
`URL: POST http://localhost:4567/calculation/maal/<getal>`   
Voorbeeld: POST http://localhost:4567/calculation/maal/6   _calculation*6_    
     
**Uitvoeren van een deling**    
       
`URL: POST http://localhost:4567/calculation/deling/<getal>`    
Voorbeeld: POST http://localhost:4567/calculation/deling/6   _calculation/6_    
    
***    
**GET**     
     
**Het tonen van het resultaat**
     
`URL: GET http://localhost:4567/calculation/`      
    
***
      
**DELETE**    
     
**Indien een fout gemaakt kan men de hele calculatie verwijderen via volgende URL**
    
`URL: DELETE http://localhost:4567/calculation`    
    
****
    
**TO DO**
   
een andere resource maken voor het standaard getal in te geven ipv van constant optelling te gebruiken om een getal bij 0 op te tellen.    
Een delete die enkel de vorige stap verwijderd ?    
    
**NOTES**    
    
Ik geloof dat dit REST is omwillen van het feit dat elk getal eigenlijk wordt opgeslagen en de berekening via de URL gebeuren.    
     

**Bronnen**     
Link gebruikt voor het achterhalen hoe ongeveer : http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api     
http://apigee.com/about/blog/technology/restful-api-design-nouns-are-good-verbs-are-bad      
http://stackoverflow.com/questions/8275209/how-can-i-create-a-restful-calculator      
Link gebruikt voor Request --> req.params : http://expressjs.com/en/api.html     
     
**END**

