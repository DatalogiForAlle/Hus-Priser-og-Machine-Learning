# Ændringer fra original -> Draft 1
- Flyttede visualisering af data foran data rengøring
- Har rykket alle funktions definitionerne ind i et modul
Dette indebærer: fetch_housing_data, load_housing_data, split_train_test, test_set_check, split_train_test_by_id,CombinedAttributesAdder, CalculateAccuracy
- Har fjernet Housing data med Identifieren "id"
- Har fjernet fremvisningen af OneHotEncoder funktionaliteten.
- Har fjernet "ocean proximity", da det ellers ville være nødvendigt at transformere det med OneHotEncoder 

# Noter
- burde vi simplificere Pipeline delen? Er det interessant at vide at tingene sker i en defineret rækkefølge