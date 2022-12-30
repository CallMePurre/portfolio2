
Utvärdera designprinciper som webbplatser använder sig av
=======================

Urval
-----------------------

Jag har valt att analysera Telias, Nordeas och HBO Max:s hemsidor då de är tidigare arbetsgivare, precis som i föregående analys.

Metod
-----------------------

Mätningarna av respektive sida utfördes med hjälp av verktyget <a href="https://pagespeed.web.dev/">pagespeed</a>. Sidornas laddningstider fastställdes med hjälp av ett Chrome-tillägg som heter <a href="https://chrome.google.com/webstore/detail/page-load-time/fploionmjgeclbkemipmkogoaohcdbig">Page load time</a>. De övriga värdena hämtades från fliken Nätverk i DevTools och analyserades för de relevanta objekten.

Resultat
-----------------------

<h2><a href="https://docs.google.com/spreadsheets/d/13MYRTHljCHIYYj4vwE0wdhNNLNqfnWRu5F_mBHrVsgQ/edit#gid=0">Data</a></h2>
<iframe class="data" title="spreadsheet" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSuAqZlpirxSSD9o6iaQES-CjiaOAGZG4j1ID8cxU-8pLqCn0X1Ot5E7YNSlFQn7ra3gN0pq9Ww2kJM/pubhtml?widget=true&amp;headers=false"></iframe>


## Telia

<img src="%base_url%/image/Telia.png" alt="Telia">

I det här testet genomfördes mätningarna på förstasidan samt Telias mobil- och bredbandsflikar. Det noterades att denna webbplats använde bilder och animationer av hög kvalitet, ofta i PNG-format. Även om PNG är ett mångsidigt format som ofta kan konverteras till andra format, t.ex. JPEG, skulle en konvertering av dessa element till ett effektivare format potentiellt kunna minska dataanvändningen och förbättra sidans prestanda. Istället för GIF-filer kan de även konverteras till PNG.


## Nordea

<img src="%base_url%/image/Nordea.png" alt="Nordea">

I det här testet genomfördes mätningarna på förstasidan, köpa hus- och sälja hussidan på Nordeas webbplats. Det observerades att denna webbplats var relativt liten och fick bra resultat i de flesta kategorier. Därför finns det kanske inte något större utrymme för förbättringar när det gäller prestanda på denna webbplats.

## HBO Max

<img src="%base_url%/image/HBOMax.png" alt="HBOMax">

I det här testet utfördes mätningarna på HBO Max' förstasida, play-sida och filmsida, med målet att ladda ett maximalt antal bilder. En analys av webbplatsens kod avslöjade potentiella områden för optimering för att förbättra prestandan. Det noterades att de övergripande poängen för denna webbplats var låga, vilket delvis kan tillskrivas suboptimala kodningsmetoder.

Analys
-----------------------

Sammafattningsvis så fick alla sidor ofta dåliga betyg för sin mobiloptimisering. Det finns ingen generell åtgärd alla sidor kan genomföra, utan de hade egna problem med sin webbplats. Nordea hittade vi inte många förbättringsåtgärder då sidan är väldigt liten och det finns inte jättemycket rum för optimisering. 

En utvärdering av HBO Max webbplats visade att det fanns brister i kodningsmetoderna, vilket kan ha bidragit till dess relativt låga resultat. Det är värt att notera att denna webbplats hade en större volym resurser och data att ladda ner, vilket kan bero på att den innehöll trailers och omslagsbilder av hög kvalitet. Trots detta hade sidan relativt snabba laddningstider. Telias webbplats fick däremot lägre betyg på grund av suboptimal formatering av bilder och animationer. Detta observerades ha en negativ inverkan på laddningstiderna, trots att webbplatsens totala storlek var rimlig.


Vinnare
-----------------------

Resultatet av denna undersökning placerade HBO Max på tredje plats, med låga betyg på både mobila och stationära enheter. Detta berodde på grundläggande fel i webbplatsens utformning och funktionalitet. På andra plats kom Telia, som fick generellt sett bra betyg men som överträffades av den högst rankade webbplatsen på grund av suboptimal optimering av bilder. Nordea framträdde som den bästa, fick toppbetyg i alla kategorier och uppvisade en väl utformad och funktionell webbplats.

Laddningstid
-----------------------

Laddningstiderna för hemsidorna var runt 1.5 sekunder i snitt. HBO Max's sida laddades in väldigt snabbt även fast de hade många förfrågningar och större sida. Nordeas hemsida hade också snabba laddningstider, men detta är nog ett resultat av att sidan är liten. Telias sida hade lite högre laddningstiden trots att de inte hade lika stora sidor som HBO Max, dock lite mer förfrågningar.

Den genomsnittliga laddningstiden för webbplatserna i den här studien var cirka 1,5 sekunder. Det observerades att HBO Max sida hade snabba laddningstider trots att den hade en större mängd förfrågningar och en större total storlek. Nordeas webbplats hade också snabba laddningstider, vilket sannolikt berodde på dess mindre storlek. Telias sida hade något långsammare laddningstider, trots att den hade en mindre storlek och ett liknande antal förfrågningar jämfört med HBO Max. På grundval av dessa resultat kan en laddningstid på cirka 1 sekund anses vara ett rimligt mål för dessa webbplatser att sträva efter.

Övrigt
-----------------------
Patrik Lindblom