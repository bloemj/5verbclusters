# 5verbclusters
Dit is de repository die hoort bij het paper "Een corpus waar alle constructies in gevonden zouden moeten kunnen worden?". Hier zijn de XPath-queries en de zoekresultaten te vinden.

De volledige queries zijn te lang om direct in PaQu te plakken, dus daarom hieronder zowel de volledige query als een versie met macro's. Om in PaQu te zoeken moet u eerst [inloggen](https://www.let.rug.nl/~kleiweg/paqulogin/) en het bestand met macro's uploaden, waarna de verkorte query kan worden uitgevoerd.

[Download hier de macro's voor vijfledige werkwoordsclusters](5v-clustermacros.txt)

## 5-1-2-3-4-clusters
Verkorte query met macro's: [1b-5verbs-tang-51234-query.txt](1b-5verbs-tang-51234-query.txt)  
Volledige query: [1b-5verbs-tang-51234-expandedquery.txt](1b-5verbs-tang-51234-expandedquery.txt)  

### Wiki-corpus Lassy Groot:  
[Resultaten uit DACT](dact-nlwiki-5verbs-tang-generalized-query1b.csv)  
[Resultaten uit PaQu](paqu-nlwiki-5verbs-tang-generalized-query1b.csv)  

## 1-2-3-4-5-clusters
Verkorte query met macro's: [2b-5verbs-asc-12345-query.txt](2b-5verbs-asc-12345-query.txt)  
Volledige query: [2b-5verbs-asc-12345-expandedquery.txt](2b-5verbs-asc-12345-expandedquery.txt)  

### Wiki-corpus Lassy Groot:  
[Resultaten uit DACT](dact-nlwiki-5verbs-asc-generalized-query2b.csv)  
[Resultaten uit PaQu](paqu-nlwiki-5verbs-asc-generalized-query2b.csv)  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassywiki&xpath=%2F%2Fnode%5B%28%25v%25+and%0D%0A++++++++++++++%28+some+%24x+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++%25vhead%25+and%0D%0A+++++++++++++++++++++++%28+some+%24y+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++++++++++%28+some+%24z+in+%2F%2Fnode%5B%25v%25+and%0D%0A+++++++++++++++++++++++++++++++++++++++%28+some+%24n+in+%2F%2Fnode%5B%25v%25%5D%0D%0A+++++++++++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24n%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++and+%25sameclausen%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24z%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++and+%25sameclause3%25%29%0D%0A+++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24y%2F%25b%25%29%0D%0A+++++++++++++++++++++++++and+%25sameclause2%25%29%0D%0A+++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++%5D%0D%0A+++++++++++++++satisfies+%28%28%25b%25%3D%24x%2F%25e%25%2B3%29+%0D%0A+++++++++++++++and+%25sameclause%25%29%0D%0A++++++++++++++%29%0D%0A%29%5D&mt=std&xn=100) (deze link werkt alleen als u ingelogd bent op PaQu en na het uploaden van het bestand met de clustermacro's, en het zoeken kan lang duren)

### Krantencorpus Lassy Groot:  
[Resultaten uit DACT](dact-krant-5verbs-asc-generalized-query2b.csv)  
[Resultaten uit PaQu](paqu-krant-5verbs-asc-generalized-query2b.csv)  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassynewspapers&xpath=%2F%2Fnode%5B%28%25v%25+and%0D%0A++++++++++++++%28+some+%24x+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++%25vhead%25+and%0D%0A+++++++++++++++++++++++%28+some+%24y+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++++++++++%28+some+%24z+in+%2F%2Fnode%5B%25v%25+and%0D%0A+++++++++++++++++++++++++++++++++++++++%28+some+%24n+in+%2F%2Fnode%5B%25v%25%5D%0D%0A+++++++++++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24n%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++and+%25sameclausen%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24z%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++and+%25sameclause3%25%29%0D%0A+++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24y%2F%25b%25%29%0D%0A+++++++++++++++++++++++++and+%25sameclause2%25%29%0D%0A+++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++%5D%0D%0A+++++++++++++++satisfies+%28%28%25b%25%3D%24x%2F%25e%25%2B3%29+%0D%0A+++++++++++++++and+%25sameclause%25%29%0D%0A++++++++++++++%29%0D%0A%29%5D&mt=std&xn=100) (deze link werkt alleen als u ingelogd bent op PaQu en na het uploaden van het bestand met de clustermacro's, en het zoeken kan lang duren)


