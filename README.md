# ex-3-Sneyers-Robrecht

 Link gebruikt voor het achterhalen hoe ongeveer : http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api
 andere links: http://apigee.com/about/blog/technology/restful-api-design-nouns-are-good-verbs-are-bad
 http://stackoverflow.com/questions/8275209/how-can-i-create-a-restful-calculator
# REST API --> omschrijving en gebruik welke resources. 
#
Voorbeeld URL dat ik wil bereiken: /calculation/optelling/Var1 --> calculation staat standaard op 0 dus stel dat we uitvoeren /calculation/optelling/3 dan krijgen we 0+3
nu staat calculation op 3 en kunnen we bijvoorbeeld /calculation/optelling/6 dan 3+6 is 9
hiervoor gebruiken we een POST 
voor het krijgen van de current waarde van calculation gebruiken we een GET
voor het verwijderen gebruiken we DELETE om calculation terug te verwijderen en op 0 te zetten.

Verder kan je dan ook breuk,maal,vierkantswortel, ...enz toevoegen als resources.

Ik geloof dat dit REST is omwillen van het feit dat elk getal eigenlijk wordt opgeslagen en de berekening via de URL gebeuren.

Link gebruikt voor Request --> req.params : http://expressjs.com/en/api.html

