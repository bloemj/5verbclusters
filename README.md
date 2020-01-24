# 5verbclusters
Dit is de repository die hoort bij het paper "Een corpus waar alle constructies in gevonden zouden moeten kunnen worden?". Hier zijn de XPath-queries en de zoekresultaten te vinden.

De volledige queries zijn te lang om direct in PaQu te plakken, dus daarom hieronder zowel de volledige query als een versie met macro's. Om in PaQu te zoeken moet u eerst [inloggen](https://www.let.rug.nl/~kleiweg/paqulogin/) en het bestand met macro's uploaden, waarna de verkorte query kan worden uitgevoerd.

[Download hier de macro's voor vijfledige werkwoordsclusters](5v-clustermacros.txt)

[Overzicht van alle gevonden vijfledige werkwoordsclusters, met annotaties](dact-allcorrect-syntactic.csv)

## Syntactisch zoeken

### 5-1-2-3-4-clusters
Verkorte query met macro's: [1c-5verbs-tang-51234-query.txt](1c-5verbs-tang-51234-query.txt)  
Volledige query: [1c-5verbs-tang-51234-expandedquery.txt](1c-5verbs-tang-51234-expandedquery.txt)  

#### Wiki-corpus Lassy Groot:  
[Resultaten uit DACT](dact-nlwiki-5verbs-tang-generalized-query1c.csv)  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassywiki&xpath=%2F%2Fnode%5B%28%25v%25+and%0D%0A++++++++++++++%28+some+%24x+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++%25vhead%25+and%0D%0A+++++++++++++++++++++++%28+some+%24y+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++++++++++%28+some+%24z+in+%2F%2Fnode%5B%25v%25+and%0D%0A+++++++++++++++++++++++++++++++++++++++%28+some+%24n+in+%2F%2Fnode%5B%25v%25%5D%0D%0A+++++++++++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24n%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++and+%25sameclausen%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24z%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++and+%25sameclause3%25%29%0D%0A+++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24y%2F%25b%25%29%0D%0A+++++++++++++++++++++++++and+%25sameclause2%25%29%0D%0A+++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++%5D%0D%0A+++++++++++++++satisfies+%28%28%25e%25%3D%24x%2F%25b%25%29+%0D%0A+++++++++++++++and+%25sameclause%25%29%0D%0A++++++++++++++%29%0D%0A+++++++++%29%5D&mt=std&xn=100) (deze link werkt alleen als u ingelogd bent op PaQu en na het uploaden van het bestand met de clustermacro's, en het zoeken kan lang duren)

#### Krantencorpus Lassy Groot:  
[Resultaten uit DACT](dact-krant-5verbs-tang-generalized-query1c.csv)  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassynewspapers&xpath=%2F%2Fnode%5B%28%25v%25+and%0D%0A++++++++++++++%28+some+%24x+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++%25vhead%25+and%0D%0A+++++++++++++++++++++++%28+some+%24y+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++++++++++%28+some+%24z+in+%2F%2Fnode%5B%25v%25+and%0D%0A+++++++++++++++++++++++++++++++++++++++%28+some+%24n+in+%2F%2Fnode%5B%25v%25%5D%0D%0A+++++++++++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24n%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++and+%25sameclausen%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24z%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++and+%25sameclause3%25%29%0D%0A+++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24y%2F%25b%25%29%0D%0A+++++++++++++++++++++++++and+%25sameclause2%25%29%0D%0A+++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++%5D%0D%0A+++++++++++++++satisfies+%28%28%25e%25%3D%24x%2F%25b%25%29+%0D%0A+++++++++++++++and+%25sameclause%25%29%0D%0A++++++++++++++%29%0D%0A+++++++++%29%5D&mt=std&xn=100) (deze link werkt alleen als u ingelogd bent op PaQu en na het uploaden van het bestand met de clustermacro's, en het zoeken kan lang duren)

### 1-2-3-4-5-cluster
Verkorte query met macro's: [2c-5verbs-asc-12345-query.txt](2c-5verbs-asc-12345-query.txt)  
Volledige query: [2c-5verbs-asc-12345-expandedquery.txt](2c-5verbs-asc-12345-expandedquery.txt)  

#### Wiki-corpus Lassy Groot:  
[Resultaten uit DACT](dact-nlwiki-5verbs-asc-generalized-query2c.csv)  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassywiki&xpath=%2F%2Fnode%5B%28%25v%25+and%0D%0A++++++++++++++%28+some+%24x+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++%25vhead%25+and%0D%0A+++++++++++++++++++++++%28+some+%24y+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++++++++++%28+some+%24z+in+%2F%2Fnode%5B%25v%25+and%0D%0A+++++++++++++++++++++++++++++++++++++++%28+some+%24n+in+%2F%2Fnode%5B%25v%25%5D%0D%0A+++++++++++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24n%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++and+%25sameclausen%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24z%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++and+%25sameclause3%25%29%0D%0A+++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24y%2F%25b%25%29%0D%0A+++++++++++++++++++++++++and+%25sameclause2%25%29%0D%0A+++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++%5D%0D%0A+++++++++++++++satisfies+%28%28%25b%25%3D%24x%2F%25e%25%2B3%29+%0D%0A+++++++++++++++and+%25sameclause%25%29%0D%0A++++++++++++++%29%0D%0A%29%5D&mt=std&xn=100) (deze link werkt alleen als u ingelogd bent op PaQu en na het uploaden van het bestand met de clustermacro's, en het zoeken kan lang duren)

#### Krantencorpus Lassy Groot:  
De zoekopdracht naar 1-2-3-4-5-clusters in het krantencorpus levert geen resultaten op. Als u het toch wilt proberen:  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassynewspapers&xpath=%2F%2Fnode%5B%28%25v%25+and%0D%0A++++++++++++++%28+some+%24x+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++%25vhead%25+and%0D%0A+++++++++++++++++++++++%28+some+%24y+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++++++++++%28+some+%24z+in+%2F%2Fnode%5B%25v%25+and%0D%0A+++++++++++++++++++++++++++++++++++++++%28+some+%24n+in+%2F%2Fnode%5B%25v%25%5D%0D%0A+++++++++++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24n%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++and+%25sameclausen%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24z%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++and+%25sameclause3%25%29%0D%0A+++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24y%2F%25b%25%29%0D%0A+++++++++++++++++++++++++and+%25sameclause2%25%29%0D%0A+++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++%5D%0D%0A+++++++++++++++satisfies+%28%28%25b%25%3D%24x%2F%25e%25%2B3%29+%0D%0A+++++++++++++++and+%25sameclause%25%29%0D%0A++++++++++++++%29%0D%0A%29%5D&mt=std&xn=100)

### 5-4-3-2-1-clusters
Verkorte query met macro's: [3c-5verbs-dsc-54321-query.txt](3c-5verbs-dsc-54321-query.txt)  
Volledige query: [3c-5verbs-dsc-54321-expandedquery.txt](3c-5verbs-dsc-54321-expandedquery.txt)  

#### Wiki-corpus Lassy Groot: 
De zoekopdrachten naar 5-4-3-2-1-clusters leveren geen resultaten op. Als u het toch wilt proberen:  
[Zoeken met PaQu in het Wiki-corpus](https://paqu.let.rug.nl:8068/xpath?db=lassywiki&xpath=%2F%2Fnode%5B%28%25v%25+and%0D%0A++++++++++++++%28+some+%24x+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++%28+some+%24y+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++++++++++%28+some+%24z+in+%2F%2Fnode%5B%25v%25+and%0D%0A+++++++++++++++++++++++++++++++++++++++%28+some+%24n+in+%2F%2Fnode%5B%25vhead%25%5D%0D%0A+++++++++++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24n%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++and+%25sameclausen%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24z%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++and+%25sameclause3%25%29%0D%0A+++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24y%2F%25b%25%29%0D%0A+++++++++++++++++++++++++and+%25sameclause2%25%29%0D%0A+++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++%5D%0D%0A+++++++++++++++satisfies+%28%28%25e%25%3D%24x%2F%25b%25%29+%0D%0A+++++++++++++++and+%25sameclause%25%29%0D%0A++++++++++++++%29%0D%0A+++++++++%29%5D&mt=std&xn=100)  
[Zoeken met PaQu in het krantencorpus](https://paqu.let.rug.nl:8068/xpath?db=lassynewspapers&xpath=%2F%2Fnode%5B%28%25v%25+and%0D%0A++++++++++++++%28+some+%24x+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++%28+some+%24y+in+%2F%2Fnode%5B%0D%0A+++++++++++++++++++++++++++++++%25v%25+and%0D%0A+++++++++++++++++++++++++++++++%28+some+%24z+in+%2F%2Fnode%5B%25v%25+and%0D%0A+++++++++++++++++++++++++++++++++++++++%28+some+%24n+in+%2F%2Fnode%5B%25vhead%25%5D%0D%0A+++++++++++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24n%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++and+%25sameclausen%25%29%0D%0A+++++++++++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24z%2F%25b%25%29%0D%0A+++++++++++++++++++++++++++++++++and+%25sameclause3%25%29%0D%0A+++++++++++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++++++++++%5D%0D%0A+++++++++++++++++++++++++satisfies+%28%28%25e%25%3D%24y%2F%25b%25%29%0D%0A+++++++++++++++++++++++++and+%25sameclause2%25%29%0D%0A+++++++++++++++++++++++++%29%0D%0A+++++++++++++++++++++++%5D%0D%0A+++++++++++++++satisfies+%28%28%25e%25%3D%24x%2F%25b%25%29+%0D%0A+++++++++++++++and+%25sameclause%25%29%0D%0A++++++++++++++%29%0D%0A+++++++++%29%5D&mt=std&xn=100)
## Zoeken op woordsoort

### Reeksen van vijf werkwoorden
Volledige query: [1-5verbspos-vvvvv-query.txt](1-5verbspos-vvvvv-query.txt)  

#### Wiki-corpus Lassy Groot:  
[Resultaten uit DACT](dact-nlwiki-5verbspos-query1.csv)  
[Resultaten uit PaQu](paqu-nlwiki-5verbspos-query1.txt)  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassywiki&xpath=%2F%2Fnode%5B%28%40pos%3D%22verb%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40pos%3D%22verb%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40pos%3D%22verb%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40pos%3D%22verb%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40pos%3D%22verb%22%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%29%5D&mt=std&xn=100)

#### Krantencorpus Lassy Groot:  
[Resultaten uit DACT](dact-krant-5verbspos-query1.csv)  
[Resultaten uit PaQu](paqu-krant-5verbspos-query1.txt)  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassynewspapers&xpath=%2F%2Fnode%5B%28%40pos%3D%22verb%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40pos%3D%22verb%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40pos%3D%22verb%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40pos%3D%22verb%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40pos%3D%22verb%22%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%29%5D&mt=std&xn=100)

## Zoeken naar specifieke gevallen

### Zullen moeten kunnen worden (lemma's)
Volledige query: [4-5verbs-zullenmoetenkunnenworden-query.txt](4-5verbs-zullenmoetenkunnenworden-query.txt)  

#### Wiki-corpus Lassy Groot:  
[Resultaten uit DACT](dact-nlwiki-zullenmoetenkunnenworden-lemma.csv)  
[Resultaten uit PaQu](paqu-nlwiki-zullenmoetenkunnenworden-lemma.txt)  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassywiki&xpath=%2F%2Fnode%5B%28%40lemma%3D%22zullen%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40lemma%3D%22moeten%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40lemma%3D%22kunnen%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40lemma%3D%22worden%22%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%29%5D&mt=std&xn=100)

#### Krantencorpus Lassy Groot:  
[Resultaten uit DACT](dact-krant-zullenmoetenkunnenworden-lemma.csv)   
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassynewspapers&xpath=%2F%2Fnode%5B%28%40lemma%3D%22zullen%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40lemma%3D%22moeten%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40lemma%3D%22kunnen%22+and+%28number%28%40end%29%3D%2F%2Fnode%5B%40lemma%3D%22worden%22%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%5D%2Fnumber%28%40begin%29%29%29%5D&mt=std&xn=100)

### Zou moeten kunnen worden (woorden)
Volledige query: [5-5verbs-zoumoetenkunnenworden-query.txt](5-5verbs-zoumoetenkunnenworden-query.txt)  

#### Wiki-corpus Lassy Groot:  
[Resultaten uit PaQu](paqu-nlwiki-zoumoetenkunnenworden-word.txt)  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassywiki&xpath=%2F%2Fnode%5B%28%40word%3D%22zou%22+and+%28%25e%25%3D%2F%2Fnode%5B%40word%3D%22moeten%22+and+%28%25e%25%3D%2F%2Fnode%5B%40word%3D%22kunnen%22+and+%28%25e%25%3D%2F%2Fnode%5B%40word%3D%22worden%22%5D%2F%25b%25%29%5D%2F%25b%25%29%5D%2F%25b%25%29%29%5D&mt=std&xn=100)

#### Krantencorpus Lassy Groot:  
[Zoeken met PaQu](https://paqu.let.rug.nl:8068/xpath?db=lassynewspapers&xpath=%2F%2Fnode%5B%28%40word%3D%22zou%22+and+%28%25e%25%3D%2F%2Fnode%5B%40word%3D%22moeten%22+and+%28%25e%25%3D%2F%2Fnode%5B%40word%3D%22kunnen%22+and+%28%25e%25%3D%2F%2Fnode%5B%40word%3D%22worden%22%5D%2F%25b%25%29%5D%2F%25b%25%29%5D%2F%25b%25%29%29%5D&mt=std&xn=100)

